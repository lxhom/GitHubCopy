This is the demo page!

The link below and the markdown footer was generated with this NodeJS script:

```js
let GitHubCopy = require("./generator.js"); // Import the generator script
let thisCodeBlock = String(require('fs').readFileSync("./demo.md")).match(new RegExp("\u0060\u0060\u0060js[^\u0060]+\u0060\u0060\u0060"))[0].substr(5,String(require('fs').readFileSync("./demo.md")).match(new RegExp("\u0060\u0060\u0060js[^\u0060]+\u0060\u0060\u0060"))[0].length-8); // horrific regular expressions, just ignore this
let result = GitHubCopy.generate([thisCodeBlock], "https://lxhom.github.io/GitHubCopy/demo", false, true, "JS Footer"); // Call the generate function (see JSDoc in generator.ts for more)
console.log("Copy Link:", result.urls[0].url); // Show the link in the console
console.log("Footer Markdown:", result.markdown); // Show the markdown in the console
```

[<kbd>Copy Code</kbd>](https://lxhom.github.io/GitHubCopy/demo?0)

<details><summary>JS Footer</summary>

Generated by [GitHubCopy](https://github.com/lxhom/GitHubCopy/)

<script>let i=location.search.split('?')[1];i.length?history.back(navigator.clipboard.writeText(unescape(['%0D%0Alet%20GitHubCopy%20%3D%20require%28%22./generator.js%22%29%3B%20//%20Import%20the%20generator%20script%0D%0Alet%20thisCodeBlock%20%3D%20String%28require%28%27fs%27%29.readFileSync%28%22./demo.md%22%29%29.match%28new%20RegExp%28%22%5Cu0060%5Cu0060%5Cu0060js%5B%5E%5Cu0060%5D+%5Cu0060%5Cu0060%5Cu0060%22%29%29%5B0%5D.substr%285%2CString%28require%28%27fs%27%29.readFileSync%28%22./demo.md%22%29%29.match%28new%20RegExp%28%22%5Cu0060%5Cu0060%5Cu0060js%5B%5E%5Cu0060%5D+%5Cu0060%5Cu0060%5Cu0060%22%29%29%5B0%5D.length-8%29%3B%20//%20horrific%20regular%20expressions%2C%20just%20ignore%20this%0D%0Alet%20result%20%3D%20GitHubCopy.generate%28%5BthisCodeBlock%5D%2C%20%22https%3A//lxhom.github.io/GitHubCopy/demo%22%2C%20false%2C%20true%2C%20%22JS%20Footer%22%29%3B%20//%20Call%20the%20generate%20function%20%28see%20JSDoc%20in%20generator.ts%20for%20more%29%0D%0Aconsole.log%28%22Copy%20Link%3A%22%2C%20result.urls%5B0%5D.url%29%3B%20//%20Show%20the%20link%20in%20the%20console%0D%0Aconsole.log%28%22Footer%20Markdown%3A%22%2C%20result.markdown%29%3B%20//%20Show%20the%20markdown%20in%20the%20console%0D%0A',][+i]))):i</script>

</details>

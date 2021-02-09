# GitHub Copy Code Button
# WIP
## Introduction

GitHubCopy is a simple TypeScript program that generates Markdown code. Combined with the free service GitHub Pages, you can integrate a <kbd>Copy code</kbd> button or link directly into your Markdown files. The button/link is completely customizable because it's just a regular URL. No servers needed. No additional files needed. The only visible modification you need to add to your Markdown files is a little arrow. It would look like this:

> ```class Animal extends Dog;```
>
> <kbd>Copy code</kbd>
>
> More content...
>
> <details><summary></summary>Here would be a JS Script tag.</details>

## Usage

You can use the GitHubCopy generator in every JavaScript environment, either as a module or as a function as the TS source or as compiled JS. For more infos about the generator, read the JSDoc comments in the [TS source code](generator.ts).

To integrate the code into your Markdown file, just paste the `[result].markdown` at the end of your markdown file, and then you just have to link to your GitHub Page with the link provided by the script (`[result].urls[x].url`).

Creating a GitHub Page is pretty easy:

- Go to your repository page.
- Click on the settings tab.
- Scroll to the GitHub Pages section
- Select a branch that you want to publish
- Click on save
- *(Optional)* Enter your domain to use your own instead of a GitHub.io subdomain

## Example/Demonstration

See [demo.md](demo.md).

## Special Thanks

Special thanks to my Insomnia. This project was created at 3am on a thursday because I couln't sleep so I spent my time coding this while watching [Tofu-chan](https://youtu.be/Cw_f4OgW0vQ) (the only thing thats keeping me sâne p*le****aş<s>έ śƎήĎ ђξҐſ</s>***)

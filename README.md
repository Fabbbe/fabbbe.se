# FABBBE.SE

This is the git repo for my website [fabbbe.se](http://fabbbe.se/). A small POSIX-compliant shell script is used to generate the website. If you in any way want to adapt this generator to your own website you are welcome to do so!

## Usage
`./generate` generates the pages and copies them to the output directory defined in the script.

## Directories
Create all these directories in the same directory as this script file:

* `content` - *only* markdown files that are going to be made into html, end filename with `.draft` if it is not finished.
* `layouts` - to be supplied with a `top.html` and `bot.html` that is shown on all pages, and a `home.html` that includes all content for the main page.
* `static` - all content that is to be *directly copied* to the output directory.

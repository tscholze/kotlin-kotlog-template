# kotlin-kotlog-template
**Kot**lin B**log** is a CLI static blog generator - not intended for public or productional use. It features some handy shortcuts to streamline my content creation workflows.

## tl;dr
No, I do not think that you wanna use this Kotlin CLI. It is meant as a content creation helper for me needs. But if you find it interessering, awesome!

![](https://github.com/tscholze/kotlin-kotlog-cli/blob/main/docs/kotlog-markdown2html.png?raw=true)

## Development
The development of kotlog cli happens at the [repository 'tscholze/kotlin-kotlog-cli'](https://github.com/tscholze/kotlin-kotlog-cli). Please have a look there if you are interested in the development aspect of the program.

## Structure
- `__posts/` - contains all Markdown posts that will be rendered
- `__styles` - contains all drop-in css style files
- `docs` - is the regenerated html output directory

## Usage

Clone the this repository first, then you are ready to run the CLI. This will not work on Windows systems if you use Git-Bash, PowerShell or the DOS terminal.

```
./kotlog [options]
 -c 'My awesome title'  : Creates a new blog post
 -y 'beYqB6QXQuY'       : Creates a YouTube post
 -g                     :  Generates HTML output
 -p                     : Publish aka pushes changes to remote
 -co                    : Clears the output
```

## Features

### Blogging
- Creates pre-configurated Markdown files for blog posts 
- Supports Frontmatter for meta information
- Renders markdown files into HTML blog articles
- Renders a feed.json with snippets of blog articles

### Content creation
- Shortcut for YouTube video announcements just with its video id

### Social media
 - Creates social media preview images for each blog post

## Warning
Do not use this tool in production or something else besides education! I just started studying Kotlin and have no idea if the source generated or consumed by the CSS is GDPR or something else compliant.
If you have any other warnings for me, please open an issue. I'm here to learn!
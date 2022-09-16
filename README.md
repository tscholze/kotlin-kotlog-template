# kotlin-kotlog-template
**Kot**lin B**log** is a CLI static blog generator - not intended for public or productional use. It features some handy shortcuts to streamline my content creation workflows.

## tl;dr
No, I do not think that you wanna use this Kotlin CLI. It is meant as a content creation helper for me needs. But if you find it interessering, awesome!

![](https://github.com/tscholze/kotlin-kotlog-cli/blob/main/docs/kotlog-markdown2html.png?raw=true)

## Development
The development of kotlog cli happens at the [repository 'tscholze/kotlin-kotlog-cli'](tscholze/kotlin-kotlog-cli). Please have a look there if you are interested in the development aspect of the program.

## Structure
- `__posts/` - contains all Markdown posts that will be rendered
- `__templates` - contains all Markdown or html templates that will be used
- `__styles` - contains all drop-in css style files
- `__output` - is the regenerated html output directory

## Usage

```
java -jar kotlog.jar [...]
 -c: 'My awesome title'`: Creates a new blog post
 -y: beYqB6QXQuY`: Creates a YouTube post
 -g: Generates html output
 -p: Publish aka pushes changes to remote
```
## Warning
Do not use this tool in production or something else besides education. I just started studying Kotlin and I have no idea if the source that's generated or consumed by the CSS is GDPR or something else complient.

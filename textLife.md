# Living in Text

So for a couple of days now I have been playing around with [Markdown](https://en.wikipedia.org/wiki/Markdown), specifically with the Github-Flavored Markdown. I chose GFM because it allows me to do some things that basic markdown doesn't allow. These are some things that I need for work purposes. Basic Markdown is more than enough for my writing career.

Over the last couple of days I have learned a ton about what I can and can not do with Markdown, or I should say with Markdown and the Markdown viewer on my text editor of choice [VS Code](https://code.visualstudio.com).

A short list of the power I have in my hands now is:
- I can add svg files to the document and they render in the viewer. SVG, for those that don't know is an image file that can be created and edited in a text editor.
- Entity codes will be rendered correctly in the viewer. Entity codes are codes for those fun little symbols like &COPY;
- The same applies to Unicode characters. If you ever type something out in a foreign script or use emojis you'll need to know some of these. Things like &#x10450; &#x10451; &#x10452; &#x10453; &#x10454; &#x10455; &#x10456; &#x10457; or :blush: :moyai: :coffee: :see_no_evil: :moai: &#128512; &#x1F601; &#x1F47D;. This is trivial, of course, but it is fun.
- This very morning a thing called [Mermaid](https://mermaidjs.org) came into my view. This wonderful little gem allows one to make flowcharts and graphs using a Markdown-like syntax in your text editor. So things like this become possible. 
 ```mermaid
flowchart TD
A[Deploy to production] ---> B{Is it Friday?};
B -- Yes ---> C[Do NOT deploy!];
B -- No ---> D[Run deploy.sh to deploy!];
C ----> E((Enjoy your weekend!));
D ----> E((Enjoy your weekend!));
```
- I need to hunt it down again but I did bump into a website that advertised that one could take a spreadsheet program and make it work with the tables in Markdown. [Markdown Formula](
https://github.com/cescript/MarkdownFormula)
- Most of the means that I have to convert a markdown file to a pdf are crap. But I have an extension on VS Code that will convert the md file to html and I can open that in a browser and then save it as a pdf and that works real well.

So while a couple of things will be much more difficult in a text editor (like drafting cabinet plans), I truly can live most of my *important* computer life in the text editor.  
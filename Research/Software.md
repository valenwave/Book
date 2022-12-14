# Atom vs. Visual Studio Code
## Pro Atom
* For some reason, it is quicker to load images in Atom.
* Has default highlighting for code blocks.

## Pro Visual Studio Code
* The preview sidebar allows for quicker finding of code sections.
* `CTRL+Left-click` on a link will open up the link the browser. To do this in Atom, you have to right-click and select "Open Link". Also internal links doesn't appear to work at all for Atom. You'll want to use Visual Studio Code for this kind of navigation.
* When creating an internal Markdown link and you start typing #, it will auto suggest based on existing headers on that page.

## Cons for both
There's no easy way to access on other devices. I have resorted to committing folders to GitHub. However, it's not as convenient as cloud saving.

## Relearning
* Markdown preview: In Atom, `CTRL+SHIFT+M`. In Visual Studio Code, `CTRL+K V`

## Making Atom Better
* You can install [Document Outline](https://atom.io/packages/document-outline) to have a similar outline feature that Visual Studio Code has. The way that the package implement outline is better than the native outline that Visual Studio Code has. In Atom, the outline is dedicated to the right side of the document and it automatically removes the pound symbol (#) from the outline. However, You can collapse nested headings in the outline but if you click anywhere in the document, it all expands again. This limits the number of headers in your document if you want it to be the most maintainable. Visual Studio Code doesn't have the problem of the outline auto-expanding, but you have to manually delicate how much space you want the outline to take up on the left side.

## Making Visual Studio Code Better
* Outline: The Outline pane can be dragged to the right to create a right panel area allowing the Outline to have an entire panel all to itself.
* Spellchecking: There's package called [Code Spell Checker](https://marketplace.visualstudio.com/items?itemName=streetsidesoftware.code-spell-checker) to will add spell checking. However, in Atom, you can simply right-click to see possible spellcheck option. While in Visual Studio code, you have to wait for and look for the light bulb icon, use the `CTRL+.` shortcut, or right-click and also select, "Spelling Suggestions...". Even with the extension, Atom is better with spell checking. I'll need to investigate options for editing the spell checker.
* Workspace: In Visual Studio Code, when you open up a folder, it replaces the existing one. However, if you right-click on the workspace area, you can select "Add Folder to Workspace..." to be able to have multiple folders open simultaneously. With multiple files open in your workspace, you can save your workspace to be opened later (I haven't tried this).

## Themes
* `CTRL+K, CTRL+T`
* Dark+ (Default Dark): Bulleted list are white. Headers are blue.
* Monokai Dimmed: I don't like that my bulleted list are a shade of green. 

## In Summary
* Atom is better at... screenshots, spell checking
* Visual Studio Code is better at... bookmarking, reading markdown

# Diagrams.net
## Pros
* Copy and paste from clipboard
* Save sections into Scratchpad for re-use.
* Scratchpad persist between documents.

## Cons
* Not a very good mobile presence.

# MediaWiki vs. GitLab Wiki
## GitLab Wiki
* Can insert screenshots via the `CTRL+V` shortcut
* Can use Markdown

# MindMeister
Supports up to 3 mind maps on the free version. This is enough for me at the moment. I just have the one map to use for planning out team meetings. 

# Wireshark
```
ip.src == 10.150.0.103

ip.dst != 10.149.2.41 && ip.dst != 10.150.0.255 && ip.dst != 255.255.255.255 && ip.dst != 104.43.22.36 && ip.dst != 10.150.0.82 && ip.dst != 142.250.191.234 && ip.dst != 20.189.173.14 && ip.dst != 20.189.173.9 && ip.dst != 10.149.2.1 && ip.dst != 20.44.10.123 && ip.dst != 10.149.2.11 && ip.dst != 13.69.116.104 && ip.dst != 52.168.112.67 && ip.dst != 52.191.219.104 && ip.dst != 52.96.163.50
```

# Links
* [Wireshark](https://www.wireshark.org/#download)


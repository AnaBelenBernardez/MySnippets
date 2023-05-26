# ✂ My Snippets
I have created my own Emmet snippets in VSCode. 
I frequently use some specific abbreviations, so I saved them as snippets to enhance my workflow even further.

## ⚙ How to start: 
* Create a file called "snippets.json" and add the following basic code to it:

```
{
  "html": {
    "snippets": { }
  },
  "css": {
    "snippets": { }
  }
}
```

* Open the VSCode settings and locate the "Emmet Extensions Path" option. Add the path of the folder where the "snippets.json" file is located. Note that you should provide the folder path, not the file path itself. I created the file in a directory that I synchronize with my cloud storage to avoid losing it in the future.

* Add your own abbreviations.  I found some helpful resources, particularly the first one, which provides common examples and an breakdown of how they work:
  * [Creating Custom Emmet Snippets In VS Code](https://www.smashingmagazine.com/2021/06/custom-emmet-snippets-vscode/#lazy-loading)
  * [How to expand Emmet abbreviations and snippets](https://code.visualstudio.com/docs/editor/emmet)
  * [Personalizar Emmet en Visual Studio Code](https://www.jasoft.org/Blog/post/personalizar-emmet-en-visual-studio-code-y-librarse-del-meta-x-ua-compatible-ie-edge)

* You may need to restart VSCode for the changes to take effect. I created an HTML and CSS file to test if the snippets work correctly, and I might come up with more ideas 🚀.

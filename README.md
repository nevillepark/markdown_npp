# Markdown for Notepad++

This project is a user-defined language that adds Markdown syntax highlighting to [Notepad++](http://notepad-plus-plus.org). Dissatisfied with other people's versions, I made my own. Due to the limitations of user-defined languages, not all Markdown features are supported; however, this will probably be enough for most people.

Two styles are included: one meant for dark themes, one for light. 

## How to use it

1. Click on the link to `userDefineLang.xml` to get the code you need. (You can also download the file and open it in a text editor, if you like.) 
1. Open File Explorer and enter `%APPDATA%\Notepad++\` in the location bar. 
2. If there is a file called `userDefineLang.xml`, open it in any text editor. If not, create it: right-click, choose `New > Text Document`, and save the file as `userDefineLang.xml`.
3. If this is the first user-defined language you are adding, copy and paste everything from my version of `userDefineLang.xml` into the version on your computer, replacing anything that was there. If you already have user-defined languages, just copy everything from my version between `<NotepadPlus>` and `</NotepadPlus>`, then paste it into your `userDefineLang.xml` file right before `</NotepadPlus>`.
4. Save your file and restart Notepad++.
5. Markdown and Markdown Dark will now appear as options at the very bottom of the `Language` menu.

## More customization options

You can make changes to these user-defined languages by opening the `Language` menu, choosing `Define your language...`, and selecting the one you want to change in the `User language `drop-down list in the User Defined Language window.

Personally, I like using the font [Input](http://input.fontbureau.com/) and Chris Kempson's [Tomorrow theme](https://github.com/ChrisKempson/Tomorrow-Theme).

## Copyright and License

Copyright (c) 2010 Thomas Smits

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

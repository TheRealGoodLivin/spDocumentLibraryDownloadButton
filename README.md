# LICENSE
MIT License

Copyright (c) 2021 Austin Livengood

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.

# Document Library Download Button
Used to display a download button for legacy SharePoint Document Library Pages.

# Notes
 > - Purely written with HTML, CSS, and Javascript.
 > - Uses images that can be found within SharePoint Sprites.
 > - This will only show a download button on files and not folders.
 > - Two Versions.
 > - - spDocumentLibraryDownloadButton: Used for direct use with your document library page.
 > - - spDocumentLibraryDownloadButtonSelective: Used for setting the download button to specific library that can be found on your page.

## How To Use
In SharePoint, the best place to store a .js file is within your Site Assets (Document Library) folder within your Site. You can use link the text file via a Content Editor or even place it in a Script Editor on the Document Library page itself.

1. Upload text file within your sites 'Site Assets' folder. 
2. Open Document Library that you wish to add Download Button too.
3. Edit Page.
4. Add Content Editor or Script Editor Web Part to the page.
5. Link text or paste code into script editor.
6. Save the page.

### Image Map Versions:
#### SharePoint Online CSS:
```CSS
<style>
 .downloadButton {
   display: inline-block;
   border: none !important;
   width: 22px;
   height: 21.3px;
   cursor: pointer;
   background-size: 374px 340px;
   background-position: -330px -42.6px;
   background-image: url('/_layouts/15/1033/images/formatmap32x32.png?rev=47');
   background-repeat: no-repeat;
   -webkit-filter: brightness(100%);
   filter: brightness(100%);
 }
</style>
```

#### SharePoint 2016 CSS:
```CSS
<style>
 .downloadButton {
   display: inline-block;
   border: none !important;
   width: 22px;
   height: 21.3px;
   cursor: pointer;
   background-size: 374px 340px;
   background-position: -330px -21.3px;
   background-image: url('/_layouts/15/1033/images/formatmap32x32.png?rev=40');
   background-repeat: no-repeat;
   -webkit-filter: brightness(100%);
   filter: brightness(100%);
 }
</style>
```

#### SharePoint 2013 CSS:
```CSS
<style>
 .downloadButton {
   display: inline-block;
   border: none !important;
   width: 22px;
   height: 21.3px;
   cursor: pointer;
   background-size: 374px 340px;
   background-position: -211px -298px;
   background-image: url('/_layouts/15/1033/images/formatmap32x32.png?rev=40');
   background-repeat: no-repeat;
   -webkit-filter: brightness(100%);
   filter: brightness(100%);
 }
</style>
```

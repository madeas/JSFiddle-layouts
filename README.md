# JSFiddle Recomended Layouts

Hey, folks!  
The grid data can be used as a tool for users, for a more convenient viewing of your creation on JSFiddle.  
For ease of use, the grid is divided into 4 containers. Choose the container you need and paste it into your project on the jsfiddle.  
[Code example on JSFiddle][id1]

## Application

1. insert in **Resources - URL** a code snippet or [link][id2] on the JSFiddle website
2. copy the desired fragment of the html grid and install it into your project:  
>
    <div class="rec">
    <em>Recommended layout</em>
    </div>
### add  
>
    <div class="layout">
      <label>
        <input name="editor_mode" type="radio" value="grid_4">
        <span class="gridMode grid_4"></span>
        Right results
        </label>
    </div>
### result
>
    <!-- jsfiddle-layouts.css -->
    <div class="rec">
      <em>Recommended layout</em>
      <div class="layout">
        <label>
            <input name="editor_mode" type="radio" value="grid_4">
            <span class="gridMode grid_4"></span>
            Right results
        </label>
      </div>
    </div>
    <!--/ jsfiddle-layouts.css -->

To change the layout, edit the **grid_4** digit to 1, 2 or 3, and the **span** content to Classic, Columns, Bottom results.

[View example on JSFiddle][id3]

Change the text color from black to white - add class **invers**
>
    <div class="rec invers">

[id1]: https://jsfiddle.net/madeas/ouLehk70/ "Code example on JSFiddle"
[id2]: https://madeas.ru/css/jsfiddle-layouts.css "jsfiddle-layouts.css"
[id3]: https://jsfiddle.net/madeas/b0oL001v/ "Full example on JSFiddle"

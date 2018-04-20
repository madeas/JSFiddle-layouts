# JSFiddle Recommended Layouts

<a href="/LICENSE.md"><img src="https://camo.githubusercontent.com/85e1dd5bc10efc714bde30575f2ba9720ef1d235/68747470733a2f2f696d672e736869656c64732e696f2f6e706d2f6c2f6e6f726d616c697a652e6373732e7376673f7374796c653d666c61742d737175617265" alt="license" style="max-width:100%;"></a> <a href="/CHANGELOG.md"><img src="https://camo.githubusercontent.com/e105f99fc4e9949b153a9de29f1eadbc3c33df23/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f6368616e67656c6f672d6d642d626c75652e7376673f7374796c653d666c61742d737175617265" alt="changelog" style="max-width:100%;"></a>

Hey, folks!  
The grid data can be used as a tool for users, for a more convenient viewing of your creation on JSFiddle.  
For ease of use, the grid is divided into 4 containers. Choose the container you need and paste it into your project on the jsfiddle.  

#### Example
See [on JSFiddle][id1]

### Download
See https://madeas.ru/css/jsfiddle-layouts.css

## Application

1. insert in **Resources - URL** a code snippet or [link][id2] on the JSFiddle website
2. copy the desired fragment of the html grid and install it into your project:  
>
    <!-- jsfiddle-layouts.css -->
    <div class="rec">
        <em>Recommended layout</em>
    </div>
    <!--/ jsfiddle-layouts.css -->
    
### + add  
>
    <div class="layout">
        <label>
            <input name="editor_mode" type="radio" value="grid_4">
            <span class="gridMode grid_4"></span>
            Right results
        </label>
    </div>
    
### = result
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
<a href="/layouts"><img src="http://madeas.ru/img/git/layouts.svg" alt="changelog" style="max-width:100%;"></a>
#### Example
See [on JSFiddle][id3]

Change the text color from black to white - add class **invers**
>
    <!-- jsfiddle-layouts.css -->
    <div class="rec invers">
      <em>Recommended layout</em>
      <div class="layout">
        <label>
            <input name="editor_mode" type="radio" value="grid_1">
            <span class="gridMode grid_1"></span>
            Classic
        </label>
      </div>
    </div>
    <!--/ jsfiddle-layouts.css -->
    
You can also copy all the code and specify the recommended fragment in it by adding the **active** class
>
    <!-- jsfiddle-layouts.css -->
    <div class="rec">
        <em>Recommended layout</em>
        <div class="layout">
          <label>
            <input name="editor_mode" type="radio" value="grid_1">
            <span class="gridMode active grid_1"></span>
            Classic
          </label>
        </div>
        <div class="layout">
          <label>
            <input name="editor_mode" type="radio" value="grid_2">
            <span class="gridMode grid_2"></span>
            Columns
          </label>
        </div>
        <div class="layout">
          <label>
            <input name="editor_mode" type="radio" value="grid_3">
            <span class="gridMode grid_3"></span>
            Bottom results
          </label>
        </div>
        <div class="layout">
          <label>
            <input name="editor_mode" type="radio" value="grid_4">
            <span class="gridMode grid_4"></span>
            Right results
          </label>
        </div>
        <small>JSFiddle-layouts — <a href="https://github.com/madeas/JSFiddle-layouts" title="JSFiddle Recommended Layouts" target="_blank">GitHub</a></small>
    </div>
    <!--/ jsfiddle-layouts.css -->

On example of an active class grid_1 

#### Example
See [on JSFiddle][id4]

![JSFiddle-Layouts](https://madeas.ru/wp-content/uploads/2018/04/bg-art_22.png "JSFiddle Recommended Layouts")

[id1]: https://jsfiddle.net/madeas/ouLehk70/2/ "Code example on JSFiddle"
[id2]: https://madeas.ru/css/jsfiddle-layouts.css "jsfiddle-layouts.css"
[id3]: https://jsfiddle.net/madeas/q2p2ydk6/3/ "Full example on JSFiddle"
[id4]: https://jsfiddle.net/madeas/L54xt3ej/ "Example on JSFiddle"

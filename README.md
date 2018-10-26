# JSFiddle Recommended Layouts

<a href="/LICENSE.md"><img src="http://madeas.ru/img/git/license.svg" alt="license" ></a> <a href="/CHANGELOG.md"><img src="http://madeas.ru/img/git/changelog.svg" alt="changelog"></a> <a href="/layouts"><img src="http://madeas.ru/img/git/layout.svg" alt="layout"></a>

Hello!
I want to introduce a small tool based on the jsfiddle project layouts - JSFiddle-layouts. The grid data can be used as a tool for users, for a more convenient viewing of your creation on JSFiddle. For ease of use, the grid is divided into 4 containers. Choose the container you need and paste it into your project on the site jsFiddle.net.  

See [on JSFiddle][id1]

## Download

[style.css][id2]
[style.min.css][id5]

## Application

1. insert in **Resources - URL** a code snippet or [link][id2] on the JSFiddle website
2. copy the desired fragment of the html grid and install it into your project:

```html
    <!-- jsfiddle-layouts.css -->
    <div class="rec">
        <em>Recommended layout</em>
    </div>
    <!--/ jsfiddle-layouts.css -->
```

### + add  

```html
    <div class="layout">
        <label>
            <input name="editor_mode" type="radio" value="grid_4">
            <span class="gridMode grid_4"></span>
            Right results
        </label>
    </div>
```

### = result

```html
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
```

To change the layout, edit the **grid_4** digit to 1, 2 or 3, and the **span** content to Classic, Columns, Bottom results.  
<a href="/layouts"><img src="http://madeas.ru/img/git/layout.svg" alt="layout"></a>

See [on JSFiddle][id3]

Change the text color from black to white - add class **invers**

```html
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
```

You can also copy all the code and specify the recommended fragment in it by adding the **active** class

```html
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
```

On example of an active class grid_1

See [on JSFiddle][id4]

![JSFiddle-Layouts](https://madeas.ru/wp-content/uploads/2018/04/bg-art_22-1.png "JSFiddle Recommended Layouts")

Русская <a href="https://madeas.ru/jsfiddle-recommended-layouts/"> документация »</a>

[id1]: https://jsfiddle.net/madeas/ouLehk70/2/ "Code example on JSFiddle"
[id2]: https://raw.githubusercontent.com/madeas/JSFiddle-layouts/master/style.css "jsfiddle-layouts.css"
[id3]: https://jsfiddle.net/madeas/q2p2ydk6/3/ "Full example on JSFiddle"
[id4]: https://jsfiddle.net/madeas/L54xt3ej/ "Example on JSFiddle"
[id5]: https://raw.githubusercontent.com/madeas/JSFiddle-layouts/master/style.min.css

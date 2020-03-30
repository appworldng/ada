# glory
A simplistic, bare bones CSS framework based on CSS grids.

## NPM
You can install directly via NPM to your project folder.
```
npm install glory
```

## CDN
The CDN is updated after the release is made public. Always, check the GitHub page for the latest release.
<ul>
  <li>
    <a href="https://cdn.jsdelivr.net/gh/chigozieorunta/glory/glory.css">
      https://cdn.jsdelivr.net/gh/chigozieorunta/glory/glory.css
    </a>
  </li>
  <li>
    <a href="https://cdn.jsdelivr.net/gh/chigozieorunta/glory/glory.min.css">
      https://cdn.jsdelivr.net/gh/chigozieorunta/glory/glory.min.css
    </a>
  </li>
</ul> 

### Why Glory?
Now, I know what you may be thinking, we don't need yet another CSS framework! There are already tons of them out there. You're right! However, lately I find myself building websites using the latest CSS grid feature and I felt in order to avoid repeating myself, I might as well build a super simple framework that contains the popular CSS style definitions captured in my everyday work. 

### Usage
Glory comes with standard classes which you can use to style the various number of columns you want by simply including them in your html file.

#### Grid Classes
The **grid** classes provides column styling for various types of scenarios. For instance, if you wish to style a 3 column row, all you have to do is:
```
<div class="grid-3">
  <div>
  </div>
  <div>
  </div>
  <div>
  </div>
</div>
```

#### Column Styling
The **row-col-spacer** class provides spacing between bootstrap columns within a row by providing a default bottom margin of 3em to the columns.
```
<div class="row row-col-spacer">
  <div class="col-md-4">
  </div>
  <div class="col-md-4">
  </div>
  <div class="col-md-4">
  </div>
</div>
```

#### Combining Classes
The **row-spacer** and **row-col-spacer** classes can be combined to achieve spacing between rows and columns together.
```
<div class="row row-spacer row-col-spacer">
  <div class="col-md-4">
  </div>
  <div class="col-md-4">
  </div>
  <div class="col-md-4">
  </div>
</div>
```

#### Other Classes
The **xs**, **sm**, **md**, **lg** options can be used to modify spacing dimensions. By default, the **row-spacer-md** class's dimension is the default size utilized and is the same as the **row-spacer** default class.
```
<!--Row Spacer Classes-->
.row-spacer-xs
.row-spacer-sm
.row-spacer-md (default, same as .row-spacer)
.row-spacer-lg

<!--Row Column Spacer Classes-->
.row-col-spacer-xs
.row-col-spacer-sm
.row-col-spacer-md (default, same as .row-col-spacer)
.row-col-spacer-lg
```

### Contributions
Anyone and everyone is welcome to contribute. Make sure you're using the latest version of bootstrap-spacer before submitting an issue. 


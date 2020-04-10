# ada
A simplistic, bare bones CSS framework based on CSS grids.

## NPM
You can install directly via NPM to your project folder.
```
npm install ada
```

## CDN
The CDN is updated after the release is made public. Always, check the GitHub page for the latest release.
<ul>
  <li>
    <a href="https://cdn.jsdelivr.net/gh/chigozieorunta/ada/ada.css">
      https://cdn.jsdelivr.net/gh/chigozieorunta/ada/ada.css
    </a>
  </li>
  <li>
    <a href="https://cdn.jsdelivr.net/gh/chigozieorunta/ada/ada.min.css">
      https://cdn.jsdelivr.net/gh/chigozieorunta/ada/ada.min.css
    </a>
  </li>
</ul> 

### Why Ada?
Now, I know what you may be thinking, we don't need yet another CSS framework! There are already tons of them out there. You're probably right! Although, I find myself building websites using the latest CSS grid feature and I felt in order to avoid repeating myself, I might as well build a super simple framework that contains the popular CSS style definitions captured in my every day work. 

### Usage
Ada comes with standard classes which you can use to style the various number of columns you want by simply including them in your html file.

#### Grid Classes
The **grid** classes (**grid-md-1**, **grid-md-2** .... **grid-md-10**) provides column styling for various types of scenarios. For instance, if you wish to style a 3 column row, all you have to do is:
```
<div class="grid-md-3">
  <div>
  </div>
  <div>
  </div>
  <div>
  </div>
</div>
```
**The numbering system applied to any grid class represents the number of columns that is applied to that row, for e.g. grid-sm-4 means four columns will be applied to that row for devices that have at least 520px viewport width. This is different from what is obtainable in Bootstrap and should not be confused with it.**

#### Uneven Grid Column Classes
The uneven grid column classes numbering (**11**, **12**, **13**, **14**, **41**, **31**, **21**, **11**) help you acheive uneven column effects. For e.g. if you need to style a **25%:75% column**, the **grid-sm-13**, **grid-md-13** & **grid-lg-13** can be used to a acheive such effect like so:
```
<div class="grid-md-13">
  <div>
  </div>
  <div>
  </div>
</div>
```

Here's how you can acheive a **66.66%:33.33%** column styling using the **grid-sm-21**, **grid-md-21** & **grid-lg-21**:
```
<div class="grid-md-21">
  <div>
  </div>
  <div>
  </div>
</div>
```

### Classes
<table>
  <tr>
    <td>
      <strong>grid-xs-1</strong><br/>
      <strong>grid-xs-2</strong><br/>
      <strong>grid-xs-3</strong><br/>
      <strong>grid-xs-4</strong><br/>
      <strong>grid-xs-5</strong><br/>
      <strong>grid-xs-6</strong><br/>
      <strong>grid-xs-7</strong><br/>
      <strong>grid-xs-8</strong><br/>
      <strong>grid-xs-9</strong><br/>
      <strong>grid-xs-10</strong><br/>
    </td>
    <td>
      <strong>grid-sm-1</strong>
    </td>
    <td>
      <strong>grid-md-1</strong>
    </td>
    <td>
      <strong>grid-lg-1</strong>
    </td>
  </tr>
</table>

### Break Points
The **grid** classes resolve to various screen sizes at 520px (sm), 1024px (md) & 1960px (lg) respectively.

### Contributions
Anyone and everyone is welcome to contribute. Make sure you're using the latest version of Ada before submitting an issue. 


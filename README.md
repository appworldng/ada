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
<table width="100%">
  <tr>
    <td><strong>Columns</strong></td>
    <td><strong>xs</strong></td>
    <td><strong>sm</strong></td>
    <td><strong>md</strong></td>
    <td><strong>lg</strong></td>
  </tr>
  <tr>
    <td>
      <strong>1 equal column</strong><br/>
      <strong>2 equal columns</strong><br/>
      <strong>3 equal columns</strong><br/>
      <strong>4 equal columns</strong><br/>
      <strong>5 equal columns</strong><br/>
      <strong>6 equal columns</strong><br/>
      <strong>7 equal columns</strong><br/>
      <strong>8 equal columns</strong><br/>
      <strong>9 equal columns</strong><br/>
      <strong>10 equal columns</strong><br/>
    </td>
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
      <strong>grid-sm-1</strong><br/>
      <strong>grid-sm-2</strong><br/>
      <strong>grid-sm-3</strong><br/>
      <strong>grid-sm-4</strong><br/>
      <strong>grid-sm-5</strong><br/>
      <strong>grid-sm-6</strong><br/>
      <strong>grid-sm-7</strong><br/>
      <strong>grid-sm-8</strong><br/>
      <strong>grid-sm-9</strong><br/>
      <strong>grid-sm-10</strong><br/>
    </td>
    <td>
      <strong>grid-md-1</strong><br/>
      <strong>grid-md-2</strong><br/>
      <strong>grid-md-3</strong><br/>
      <strong>grid-md-4</strong><br/>
      <strong>grid-md-5</strong><br/>
      <strong>grid-md-6</strong><br/>
      <strong>grid-md-7</strong><br/>
      <strong>grid-md-8</strong><br/>
      <strong>grid-md-9</strong><br/>
      <strong>grid-md-10</strong><br/>
    </td>
    <td>
      <strong>grid-lg-1</strong><br/>
      <strong>grid-lg-2</strong><br/>
      <strong>grid-lg-3</strong><br/>
      <strong>grid-lg-4</strong><br/>
      <strong>grid-lg-5</strong><br/>
      <strong>grid-lg-6</strong><br/>
      <strong>grid-lg-7</strong><br/>
      <strong>grid-lg-8</strong><br/>
      <strong>grid-lg-9</strong><br/>
      <strong>grid-lg-10</strong><br/>
    </td>
  </tr>
</table>

<table width="100%">
  <tr>
    <td><strong>Columns</strong></td>
    <td><strong>xs</strong></td>
    <td><strong>sm</strong></td>
    <td><strong>md</strong></td>
    <td><strong>lg</strong></td>
  </tr>
  <tr>
    <td>
      <strong>50% : 50%</strong><br/>
      <strong>33.33% : 66.66%</strong><br/>
      <strong>25% : 75%</strong><br/>
      <strong>20% : 80%</strong><br/>
      <strong>66.66% : 33.33%</strong><br/>
      <strong>75% : 25%</strong><br/>
      <strong>80% : 20%</strong><br/>
      <strong>40% : 60%</strong><br/>
      <strong>60% : 40%</strong><br/>
    </td>
    <td>
      <strong>grid-xs-11</strong><br/>
      <strong>grid-xs-12</strong><br/>
      <strong>grid-xs-13</strong><br/>
      <strong>grid-xs-14</strong><br/>
      <strong>grid-xs-21</strong><br/>
      <strong>grid-xs-31</strong><br/>
      <strong>grid-xs-41</strong><br/>
      <strong>grid-xs-23</strong><br/>
      <strong>grid-xs-32</strong><br/>
    </td>
    <td>
      <strong>grid-sm-11</strong><br/>
      <strong>grid-sm-12</strong><br/>
      <strong>grid-sm-13</strong><br/>
      <strong>grid-sm-14</strong><br/>
      <strong>grid-sm-21</strong><br/>
      <strong>grid-sm-31</strong><br/>
      <strong>grid-sm-41</strong><br/>
      <strong>grid-sm-23</strong><br/>
      <strong>grid-sm-32</strong><br/>
    </td>
    <td>
      <strong>grid-md-11</strong><br/>
      <strong>grid-md-12</strong><br/>
      <strong>grid-md-13</strong><br/>
      <strong>grid-md-14</strong><br/>
      <strong>grid-md-21</strong><br/>
      <strong>grid-md-31</strong><br/>
      <strong>grid-md-41</strong><br/>
      <strong>grid-md-23</strong><br/>
      <strong>grid-md-32</strong><br/>
    </td>
    <td>
      <strong>grid-lg-11</strong><br/>
      <strong>grid-lg-12</strong><br/>
      <strong>grid-lg-13</strong><br/>
      <strong>grid-lg-14</strong><br/>
      <strong>grid-lg-21</strong><br/>
      <strong>grid-lg-31</strong><br/>
      <strong>grid-lg-41</strong><br/>
      <strong>grid-lg-23</strong><br/>
      <strong>grid-lg-32</strong><br/>
    </td>
  </tr>
</table>

### Break Points
The **grid** classes resolve to various screen sizes at 520px (sm), 1024px (md) & 1960px (lg) respectively.

### Contributions
Anyone and everyone is welcome to contribute. Make sure you're using the latest version of Ada before submitting an issue... 


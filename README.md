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

#### Break Points
The **grid** classes resolve to various screen sizes at 520px (sm), 1024px (md) & 1960px (lg) respectively.

### Contributions
Anyone and everyone is welcome to contribute. Make sure you're using the latest version of Ada before submitting an issue. 


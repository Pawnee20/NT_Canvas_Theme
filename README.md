# NT Canvas Theme

The NT Canvas Theme is a set of CSS style rules that instructional designers and teachers can leverage to quickly create page layouts that update and enhance the experience for both desktop and mobile users. 

- <a href="https://github.com/Pawnee20/NT_Canvas_Theme/blob/master/README.md#updates">Updates</a>
- <a href="https://github.com/Pawnee20/NT_Canvas_Theme/blob/master/README.md#installation">Installation</a>
- <a href="https://github.com/Pawnee20/NT_Canvas_Theme/blob/master/README.md#usage-guide">Usage Guide</a>

## Updates
1.0 Initial Commit
## Installation

Please [follow this guide](https://community.canvaslms.com/docs/DOC-10862-4214724282) to apply these custom css rules to both your desktop and mobile versions of your Canvas LMS. You will need admin rights or consult with your Canvas admin.

## Usage Guide
### Navigation Layout

#### Example
```
<div class="grid-main gl--right-nav">
  <ul class="nav-box blue-box">
    <li><a href="">...</a></li>
  </ul>
  <div class="grid-header">
    <img src="..." />
  </div>
  <div class="grid-body">
  </div>
</div>
```
#### Properties
Navigation Layout
- *Right-side Navigation*
```<div class="grid-main gl--right-nav">```
- *Left-side Navigation*
```<div class="grid-main gl--left-nav">```

Navigation Color
- *Blue Navigation Buttons*
```<ul class="nav-box blue-box">```
- *Green Navigation Buttons*
```<ul class="nav-box green-box">```

*Navigation Links*
- *Selected Navigation Item* 
```<li class="nav-selected"><a href="">...</a></li>```

### Headers
#### Example
```
<h1 class="hdr hdr-green">Header</h1>
```
#### Properties
- *Blue Header*
```<h1 class="hdr hdr-green">Header</h1>```
- *Green Header*
```<h1 class="hdr hdr-blue">Header</h1>```
  

### Message Boxes
#### Example
```
<div class="msg-box msg-info">
  <img class="icon" src="..." />
  <p class="body drop-cap">...</p>
</div>
```
#### Properties
- *Icon Resizing*
```<img class="icon" src="..." />```
- *Drop-cap*
```<p class="body drop-cap">```

### Icon Grids
#### Example
```
<div class="grid-table grid-3">
  <div class="grid-table-item">
    <a href="..."><img src..." ... /></a>
    <p><a href="...">...</a></p>
  </div>
  <div class="grid-table-item"><img src="..." /><p>...</p></div>
  ...
</div>
```
#### Properties
Grid Item ```<div class="grid-table-item"></div>```

Grid Length
- *3x3 Grid* ```<div class="grid-table grid-3"></div>```
- *4x4 Grid* ```<div class="grid-table grid-4"></div>```

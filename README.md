# NT Canvas Theme

The NT Canvas Theme is a set of CSS style rules that instructional designers and teachers can leverage to quickly create page layouts that update and enhance the experience for both desktop and mobile users. 

- <a href="https://github.com/Pawnee20/NT_Canvas_Theme/blob/master/README.md#updates">Updates</a>
- <a href="https://github.com/Pawnee20/NT_Canvas_Theme/blob/master/README.md#installation">Installation</a>
- <a href="https://github.com/Pawnee20/NT_Canvas_Theme/blob/master/README.md#usage-guide">Usage Guide</a>

## Updates
2.0 Updated Header Class, New Alert/Notification Class. New mobile specific rules. Bugfixes.

1.0 Initial Commit
## Installation

Please [follow this guide](https://community.canvaslms.com/docs/DOC-10862-4214724282) to apply these custom css rules to both your desktop and mobile versions of your Canvas LMS. You will need admin rights or consult with your Canvas admin.

## Usage Guide
### Navigation Layout
![Image of Grid Layout](https://github.com/Pawnee20/NT_Canvas_Theme/blob/master/Documentation/Screenshots/grid_layout.png)
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

*Blue Navigation Buttons*
```<ul class="nav-box blue-box">```

![Blue Nav](https://github.com/Pawnee20/NT_Canvas_Theme/blob/master/Documentation/Screenshots/blue-nav.png)

*Green Navigation Buttons*
```<ul class="nav-box green-box">```

![Green Nav](https://github.com/Pawnee20/NT_Canvas_Theme/blob/master/Documentation/Screenshots/green-nav.png)


*Navigation Links*
- *Selected Navigation Item* 
```<li class="nav-selected"><a href="">...</a></li>```

*Header Dimming and Text*
```
<div class="grid-header hdr-image">
<img src="header.jpg" />
<h1>This is part of the banner</h1>
</div>
```

### Headers
#### Example
```
<h1 class="hdr hdr-green">Header</h1>
```
#### Properties
*Blue Header*
```<h1 class="hdr hdr-blue">Header</h1>```
![Blue Nav](https://github.com/Pawnee20/NT_Canvas_Theme/blob/master/Documentation/Screenshots/h_series-blue.png)

*Green Header*
```<h1 class="hdr hdr-green">Header</h1>```
![Green Nav](https://github.com/Pawnee20/NT_Canvas_Theme/blob/master/Documentation/Screenshots/h_series-green.png)
  
### Message Boxes
#### Example
![No Drop Cap](https://github.com/Pawnee20/NT_Canvas_Theme/blob/master/Documentation/Screenshots/no_drop.png)
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
![Drop Cap](https://github.com/Pawnee20/NT_Canvas_Theme/blob/master/Documentation/Screenshots/notifications-dropcap.png)
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
![3 Grid](https://github.com/Pawnee20/NT_Canvas_Theme/blob/master/Documentation/Screenshots/3x3_grid.png)
- *4x4 Grid* ```<div class="grid-table grid-4"></div>```
![4 Grid](https://github.com/Pawnee20/NT_Canvas_Theme/blob/master/Documentation/Screenshots/4x4_grid.png)

### Notifications/Alerts
#### Example
```
<div class="c-alert c-alert-blue">Header</div>
```
#### Properties
Colors
```
<div class="c-alert c-alert-blue">Alert or Notification</div>
```
```
<div class="c-alert c-alert-green">Alert or Notification</div>
```
```
<div class="c-alert c-alert-gray">Alert or Notification</div>
```
Inverted Colors
```
<div class="c-alert c-alert-blue-invert">Alert or Notification</div>
```
```
<div class="c-alert c-alert-green-invert">Alert or Notification</div>
```
```
<div class="c-alert c-alert-gray-invert">Alert or Notification</div>
```
### Misc Classes
Text-Wrap Pictures
```
<img class="text-wrap" src="..." />
```

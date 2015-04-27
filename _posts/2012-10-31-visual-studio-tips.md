---
layout: articles-post
title: "Visual Studio Tips"
description: "Tips and tricks around using Visual Studio efficiently."
category: article
postimg: /blog/assets/imgs/vs2012-logo.png
tags: [ Visual Studio, tooling]
reposts: ["http://dotnet.dzone.com/articles/visual-studio-tips"]
---


At work, I spend a huge amount of my time working with Microsoft Technologies. As such, I also use Visual Studio. Here are some of the tipps and tricks to efficiently work with it.

## Plugins

- [ASP.net and Web Tools 2012](http://www.asp.net/vnext)
- [MultiEdit](http://visualstudiogallery.msdn.microsoft.com/2beb9705-b568-45d1-8550-751e181e3aef)
- [Productivity Power Tools 2013](http://visualstudiogallery.msdn.microsoft.com/3a96a4dc-ba9c-4589-92c5-640e07332afd)

## Keystrokes
Here are my preferred keystrokes. Note, keystrokes separated by a comma mean you have to use them in sequence in order to activate the command.  
They refer to VS2012 but some may also work in previous versions.

### Generic Ones
<table class="table table-striped">
<thead>
    <th width="35%">Shortcut</th>
    <th>Description</th>
</thead>
<tbody>
    <tr>
        <td><kbd>Ctrl</kbd>+<kbd>F5</kbd></td>
        <td>Launch Application without debugging (usually faster than with debugging enabled)</td>
    </tr>
    <tr>
        <td><kbd>Shift</kbd>+<kbd>F5</kbd></td>
        <td>Stop a debugging session</td>
    </tr>
</tbody>
</table>

### Code Editing

<table class="table table-striped">
<thead>
    <th width="35%">Shortcut</th>
    <th>Description</th>
</thead>
<tbody>
    <tr>
        <td><kbd>Ctrl</kbd>+<kbd>K</kbd>, <kbd>Ctrl</kbd>+<kbd>D</kbd></td>
        <td>Autoformat the document, whether it is an HTML page, CS or JavaScript file</td>
    </tr>
    <tr>
        <td><kbd>Ctrl</kbd>+<kbd>K</kbd>,<kbd>C</kbd></td>
        <td>Comment the selected part</td>
    </tr>
    <tr>
        <td><kbd>Ctrl</kbd>+<kbd>K</kbd>,<kbd>U</kbd></td>
        <td>Un-comment the selected part</td>
    </tr>
</tbody>
</table>

### Code Navigation

<table class="table table-striped">
<thead>
    <th width="35%">Shortcut</th>
    <th>Description</th>
</thead>
<tbody>
    <tr>
        <td><kbd>F12</kbd></td>
        <td>Goto Definition</td>
    </tr>
    <tr>
        <td><kbd>Shift</kbd>+<kbd>F12</kbd></td>
        <td>Goto Definition</td>
    </tr>    
    <tr>
        <td><kbd>Ctrl</kbd>+<kbd>Q</kbd></td>
        <td>Place the cursor in the Quick-Launch box for then executing some menu command</td>
    </tr>
    <tr>
        <td><kbd>Ctrl</kbd>+<kbd>,</kbd></td>
        <td>Open the "Navigate to" dialog...probably the most powerful command for mouse-less navigation</td>
    </tr>
    <tr>
        <td><kbd>Ctrl</kbd>+<kbd>-</kbd></td>
        <td>Navigate backwards in the cursor position history</td>
    </tr>        
    <tr>
        <td><kbd>Ctrl</kbd>+<kbd>Shift</kbd>+<kbd>-</kbd></td>
        <td>Navigate forwards in the cursor position history</td>
    </tr>    
    <tr>
        <td><kbd>Ctrl</kbd>+<kbd>M</kbd>,<kbd>Ctrl</kbd>+<kbd>O</kbd></td>
        <td>Collapse to definitions</td>
    </tr>
</tbody>
</table>

### Custom mapped ###

<table class="table table-striped">
<thead>
    <th width="35%">Shortcut</th>
    <th>Description</th>
</thead>
<tbody>
    <tr>
        <td><kbd>Ctrl</kbd>+<kbd>W</kbd></td>
        <td>This is the default combination for closing windows on nearly all win apps I know, but strangely not on Visual Studio. Therefore, the first thing I do is to remap it to `File.Close`.</td>
    </tr>    
    <tr>
        <td><kbd>Ctrl</kbd>+<kbd>R</kbd>, <kbd>Ctrl</kbd>+<kbd>S</kbd></td>
        <td>Rebuild solution</td>
    </tr>
</tbody>
</table>

## Features

### Go To Test/Code

Quickly jumping to the according test class. Just right-click and select the corresponding menu item.

![](/blog/assets/imgs/vs_gototestcode.png)

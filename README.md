# BULB-ON-or-OFF-PROJECT IN JAVASCRIPT

This is a simple JavaScript project that allows you to control a virtual bulb, turning it on and off.

## Installation

To get started with this project, you'll need to have [Visual Studio Code (VS Code)](https://code.visualstudio.com/) or another code editor of your choice installed on your computer.

## Usage

1. Open the `BULB.html` file in your web browser.
2. For Bulb javascript as been used `BULB.JS`
3. Click on the Bulb to turn on
4. click on the same to turn off

## Code Example

```javascript
// JavaScript code to control the bulb
function changeImage() {
  var image = document.getElementById('myImage');
  if (image.src.match("bulbon")) {
    image.src = "pic_bulboff.gif";
  } else {
    image.src = "pic_bulbon.gif";
  }
}

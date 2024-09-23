# Gallery Table
![Fluent Dialogs Image](/FluentDialogs/Assets/FluentDialogs.gif)
## Description
Create a "Dialog" experience on your screen. Dialogs can be centered or left sided.
## Properties
- [x] Using modern controls
- [x] Using preview controls (as of 24-09-23)
## Usage instructions
The `cntDialog` main container must be at the upfront of all other controls on the screen to have this "on top of" experience. It has a semi-transparent white background.

In the `cntDialog` you can create as much dialogs as you need on your screen, each one should be a different container. The `Visible` property of the dialog container is defined by a local variable.

The behavior property triggering the display of a dialog is simulated by the 2 buttons on this sample. Displaying the dialog or not is done using a local variable `locDialog`, a record that has 2 properties :
- `Type` : String : Can be "center" or "side", to define the positioning of the dialog.
- `Code` : String : Custom unique identifier to know which dialog to display.

## Author & Contributors
Author : @tchinnin





# TemplateUI

A set of templated controls.

<img src="images/templateui-home.gif" Width="300" />

_What is a templated control?_

It is a control defined by a template. Every control has a **ControlTemplate** property and can modify the structure that defines the control.

## Overview

There are currently **18 controls**. The controls available are:

### AvatarView

Is a graphical representation of the user image view that can be customized by adding icon, text, etc.

<img src="images/templateui-avatarview.png" Width="300" />

### BadgeView

Control used to  used to notify users notifications, or status of something.

<img src="images/templateui-badgeview.png" Width="300" />

### CarouselView

Allow to navigate through a collection of views.

<img src="images/templateui-carouselview.gif" Width="300" />

### ChatBubble

Allow to show a speech bubble message.

<img src="images/templateui-chatbubble.png" Width="300" />

### CircleProgressBar

Shows a control that indicates the progress percentage of an on-going operation by circular shape.

<img src="images/templateui-circleprogressbar.png" Width="300" />

### ComparerView

Provides an option for displaying a split-screen of two views, which can help you to make comparisons.

<img src="images/templateui-comparerview.gif" Width="300" />

### DataVisualization

Several series graphs.

<img src="images/templateui-datavisualization.gif" Width="300" />

### GridSplitter

Represents the control that redistributes space between columns or rows of a Grid control.

<img src="images/templateui-gridsplitter.gif" Width="300" />

### Marquee

Use this control to add an attention–getting text message that scrolls continuously across the screen.

<img src="images/templateui-marquee.gif" Width="300" />

### PinBox

Allow to introduce a PIN or verification Code.

<img src="images/templateui-pinbox.png" Width="300" />

### ProgressBar

Represents progress as a horizontal bar that is filled to a percentage represented by a float value.

<img src="images/templateui-progressbar.gif" Width="300" />

### Rate

Allows users to select a rating value from a group of visual symbols like stars.

<img src="images/templateui-rate.png" Width="300" />

### SegmentedControl

Is a linear segment made up of multiple segments and allow users to select between multiple options.

<img src="images/templateui-segmentedcontrol.png" Width="300" />

### Shield

Shield is a type of badge.

<img src="images/templateui-shield.png" Width="300" />

### Slider

Is a horizontal bar that can be manipulated by the user to select a double value from a continuous range.

<img src="images/templateui-slider.gif" Width="300" />

### Tag

Is a tagging control.

<img src="images/templateui-tag.png" Width="300" />

### ToggleSwitch

A View control that provides a toggled value.

<img src="images/templateui-toggleswitch.png" Width="120" />

### TreeView

Enables a hierarchical list with expanding and collapsing nodes that contain nested items.

<img src="images/templateui-treeview.gif" Width="300" />

## Contribute

Do you want to contribute?.

**Found a Bug?**

If you find a bug, you can help me by submitting an [issue](https://github.com/jsuarezruiz/TemplateUI/issues). Even better, you can submit a [Pull Request](https://github.com/jsuarezruiz/TemplateUI/pulls) with a fix.

**Submitting a pull request**

For every contribution, you must:
- Test your code.
- target master branch (or an appropriate release branch if appropriate for a bug fix).

**Adding documentation**

To update the documentation, you must submit a  Pull Request adding or updating the existing markdowns.

## Feedback or Requests

Use GitHub [Issues](https://github.com/jsuarezruiz/TemplateUI/issues) for bug reports and feature requests.

## Principles

* Principle #1: Kept TemplateUI simple.
* Principle #2: Any control added must allow customization using the ControlTemplate property.

## Known Issues

* A lot of the controls are made up of basic shapes. Gestures don't work with Shapes on iOS. This affects some control like Rate. (waiting [PR #11419](https://github.com/xamarin/Xamarin.Forms/pull/11419))

## What's next

The next controls will be:
* Divider
* TabView

In addition, there are ideas for a wide variety of controls like:
* Clock
* Calendar
* ColorPicker
* DataGrid
* Loading
* Pagination
* StepBar
* TimeBar

And much more!

## Copyright and license

Code released under the [MIT license](https://opensource.org/licenses/MIT).
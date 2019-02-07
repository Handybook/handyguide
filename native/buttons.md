---
description: >-
  Call to Actions, or CTAs, communicate the action that will occur when a user
  taps them.
---

# Call to Actions

## Usage of CTAs

CTAs allow users to trigger an action. They may take the form of buttons, text links, or icon links. 

![](../.gitbook/assets/buttons-example.png)

## General CTA Guidelines

1. Labels are always title case 
2. Labels clear and succinct 
3. Labels are verbs or adverbs that express the action the button will trigger
4. Icons links should only be used when representing common paradigms

![](../.gitbook/assets/button-right-wrong.png)

## Button CTAs

### Primary Button CTAs

Opaque, primary CTA buttons are used for the most important action on a page. There should only be one primary CTA per page.

![](../.gitbook/assets/group-6.png)

### Secondary Button CTAs

Transparent secondary CTA buttons are used for subordinate actions. There can be multiple secondary CTAs per page. 

![](../.gitbook/assets/secondary.png)

## Other Types of CTAs

### Text Links

Text links are used for non-essential actions, like changes to existing content. 

![](../.gitbook/assets/text-links.png)

```text
font: Circular-Book
font-size: 16px
font-color: #0BB8E3
```

### Icon Links

Icon links are used in the header of certain pages to communicate the ability to execute common tasks, such as filtering a list. 

![](../.gitbook/assets/icon-links.png)

```text
height: 20px 
width: 20px
color: #0BB8E3
```

### Keyboard CTA

In flows where the keyboard is activated, there will be a custom button that moves the user forward in the low.

![](../.gitbook/assets/keyboard.png)

#### Container

```text
Background: #FFFFFF.
max-height: 57px
border-top: #E8EFF2
```

#### Text

```text
font-size: 20px
font-color: #0BB8E3
```

## 

```text
max-width: 343px
max-height: 57px
border-radius: 5px
color: #0BB8E3

font-family: Circular
font-size: 20px;
font-color: #FFFFFF
```

### Secondary CTA

The transparent secondary button with a thin stroke is used for subordinate actions.

```text
max-width: 343px
max-height: 57px
border-radius: 5px
border: 1px
border-color: #0BB8E3

font-family: Circular
font-size: 20px;
font-color: #0BB8E3
```

### Sizes for Primary & Secondary CTAs

In instances where primary and secondary CTAs need to be smaller, these styles can be used.

```text
Primary:
max-width: 167.5px
max-height: 44px
border-radius: 5px
border: 1px
border-color: #0BB8E3

font-family: Circular
font-size: 20px;
font-color: #0BB8E3
```

### Disabled Buttons

If an action must be take on a page before moving onto the next page, buttons need to be disabled. We need to convey to the user that an action must be taken before moving forward.

![Disabled CTAs](../.gitbook/assets/disabled-button.png)

## Small Button Sizes

For product marketing components and small touch points throughout the app.

Small:

```text
font-size: 16px
height: 44px
width: 109px
```

![Small CTAs](../.gitbook/assets/small-cta.png)

Medium:

```text
font-size: 16px
height: 44px
width: 167.5px
```

![](../.gitbook/assets/medium-cta.png)

## Button Groups

There are some instances where there are multiple actions on a single page. The number of buttons should be easy for the user to grasp.

### Primary & Secondary Button Groups

A single, important action can be emphasized as the primary button in order to guide the user.

![Button Group Styles](../.gitbook/assets/sec-button-group%20%281%29.png)

### Secondary Button Groups

Unlike primary CTAs, secondary CTAs can be combined together.

![Secondary Button Group](../.gitbook/assets/sec-button-group.png)

## Other CTA Styles

We have button styles in set for certain types of pages.

### Scroll Page

In pages that have a scroll view \(Pro Profiles\), the primary CTA will be in a container and the content on the page will scroll underneath it.

![](../.gitbook/assets/scroll-page.png)

1. Container:
   * Background: Container background will always adapt to the background of the page the component is on.

```text
max-height: 89px. 
padding: 16px
border-top: #E8EFF2
```

  2. Button: Primary button styles will be applied here

![Example of scroll page CTA \(Pro Profile\)](../.gitbook/assets/example-of-scroll-ex.png)


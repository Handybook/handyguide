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

Opaque, primary CTA buttons are used for the most important action on a page. There should only be one primary CTA per page. When the content is longer than the page and scroll is enabled, primary buttons sit in a container that sticks to the bottom of the page. 

![](../.gitbook/assets/group-6.png)

#### Button Properties \(Enabled\)

```text
max-width: 343px
max-height: 57px
border-radius: 5px
color: #0BB8E3
font-family: Circular
font-size: 20px;
font-color: #FFFFFF
```

#### Button Properties \(Disabled\)

If an action must be take on a page before moving onto the next page, buttons need to be disabled. We need to convey to the user that an action must be taken before moving forward.

```text
color: #0BB8E3
opacity: 0.4
```

#### Sticky Container Properties

```text
max-height: 89px
padding: 16px
border-top: #E8EFF2
background-color: *match to page background*
```

### 

### Secondary Button CTAs

Transparent secondary CTA buttons are used for subordinate actions. There can be multiple secondary CTAs per page. 

![](../.gitbook/assets/secondary.png)

#### Button Properties

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

#### Button Properties \(Disabled\)

 If an action must be take on a page before moving onto the next page, buttons need to be disabled. We need to convey to the user that an action must be taken before moving forward.

```text
border-color: #0BB8E3
font-color: #0BB8E3
opactiy: 0.4
```

### 

### Small Buttons CTAs

In instances where primary and secondary CTAs need to be smaller, these styles can be used.

#### Half-Size Buttons

```text
max-height: 44px
width: 167.5px
border-radius: 3px
border: 1px
font-family: Circular
font-size: 16px;
```

#### Small Buttons

```text
max-height: 44px
width: 109px
border-radius: 3px
border: 1px
font-family: Circular
font-size: 16px
```

## Other Types of CTAs

### Text Links

Text links are used for non-essential actions, like changes to existing content. 

![](../.gitbook/assets/text-links.png)

```text
font: Circular-Book
font-size: 16px
font-color: #0BB8E3
```

### 

### Icon Links

Icon links are used in the header of certain pages to communicate the ability to execute common tasks, such as filtering a list. 

![](../.gitbook/assets/icon-links.png)

```text
height: 20px 
width: 20px
color: #0BB8E3
```

### 

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


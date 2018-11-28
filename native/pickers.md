---
description: Stylings and rules for the types of pickers on our platform.
---

# Pickers

## Radio Groups

Radio groups are used when the user has to select a single option from a short list. For example, selecting bedrooms in the booking flow. Radio buttons describe complex choices or provide all the available options next to each other. Radio groups must be stacked vertically.

![](../.gitbook/assets/radio.png)

1. Current Selection:

```text
border: 1px
border-color: #0BB8E3 

Fill:
color: #0BB8E3
size: 16px
```

2. Unselected Option:

```text
border: 1px
border-color: #C2CED3
```

3. Dividing Line:

```text
border: 1px
color: #DAE2E6
width: 343px
```

## Checkboxes

Checkboxes are used when the user can select multiple options. For example, adding extras in the booking flow. Each checkbox is independent of all other checkboxes in the list.

![](../.gitbook/assets/checkboxes.png)

1. Current Selection: There can be multiple selections.

```text
border-radius: 3px
color: #0BB8E3
```

2. Option:

```text
border radius: 3px
border: 1px
border-color: #C2CED3
```

3. Dividing Line:

```text
border: 1px
color: #DAE2E6
width: 343px
```

## Filter

Filter pickers are used when the user can only select one option, the options are short \(only one word or number\) and there are less than 5 options in total.

![](../.gitbook/assets/filter.png)

1. Current Selection: There cannot be multiple selections

```text
fill: #0BB8E3
text: Circular-book
text-color: #ffffff (selected)
```

2. Corner Radius

```text
border-radius: 5px
```

3. Structure

```text
border: 1px
border-color: #C2CED3
max-width: 343px

Text:
padding-top: 16px
padding-bottom: 16px 
text-color: #434343 (unselected)
```

## Toggle

Toggles are used specifically for settings & preferences \(Account, Pro Settings\) when the user has a choice turning a certain state on or off.

![](../.gitbook/assets/toggle.png)

1. Pill Structure: Off

```text
Pill
max-height: 26px
max-width: 46px
box-shadow: inset 0px 1px 3px rgba(0, 0, 0, .2)

Circle
border: 1px
box-shadow: 0px 1px 1px rgba (0, 0, 0, .2)
```

2. Pill Structure: On

```text
Pill
max-height: 26px
max-width: 46px
box-shadow: inset 0px 1px 3px rgba(0, 0, 0, .2)
color: #0BB8E3

Circle
border: 1px
border-color: #0BB8E3
box-shadow: 0px 1px 1px rgba (0, 0, 0, .2)
```


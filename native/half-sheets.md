---
description: >-
  Half sheets contain supplementary actions or content and are anchored to the
  bottom of the screen.
---

# Half Sheets

## Usage of Half Sheets

Half sheets display supplementary actions \(filtering a list\) or content \(from tool tips\). Half sheets slide up from the bottom of the screen.

![](../.gitbook/assets/half-sheet-overview.png)

## Types of Half Sheets

\*\*\*\*[**1. Action Half Sheet \(m-half\_sheet-action\)**](half-sheets.md#action-half-sheet-m-half_sheet-action)\*\*\*\*

![](../.gitbook/assets/action-half-sheet.png)

\*\*\*\*[**2. Informational Half Sheet \(m-half\_sheet-info\)**](half-sheets.md#informational-half-sheet-m-half_sheet-info)\*\*\*\*

![](../.gitbook/assets/info-half-sheet.png)

## Action Half Sheet \(m-half\_sheet-action\)

Users can take actions like filtering list views or changing the status of a pro on action half sheet. Actions will be taken once a user selects an option and hits the CTA.

![](../.gitbook/assets/action-half-sheet-1.png)

1. Half Sheet Title \(a-text-h2\)

```text
font-weight: bold
font-size: 20px
font-color: text-black

padding-left: 16px
padding-right: 16px
padding-top: 48px
```

2. Exit

```text
max-width: 16px
max-height-:16px
color: text-black
border-width: 2px
padding-top: 16px
padding-right: 16px
```

3. Content  
Can use filter, radio, or checkbox pickers

```text
Title (a-text-h3)
font-weight: bold
font-size: 16px
font-color: text-black

Pickers
padding-bottom: 24px
```

4. Primary CTA \(a-button-primary\)

```text
max-width: 343px
max-height: 57px
border-radius: 5px
color: blue-medium
​
Text (a-text-button)
font-family: Circular
font-size: 20px
font-color: #FFFFFF
padding: 16px
```

## Informational Half Sheet \(m-half\_sheet-info\)

Users can view more information about features on an informational half sheet by tapping on a tool tip.

![](../.gitbook/assets/info-half-sheet-1.png)

1. Half Sheet Title \(a-text-h2\)

```text
font-weight: bold
font-size: 20px
font-color: text-black

padding-left: 16px
padding-right: 16px
padding-top: 48px
```

2. Exit

```text
max-width: 16px
max-height-:16px
color: text-black
border-width: 2px
padding-top: 16px
padding-right: 16px
```

3. Content

```text
Body Copy (a-text-paragraph):
font-weight: bold
font-size: 16px
font-color: text-black

padding-left: 16px
padding-right: 16px
padding-top: 24px
padding-bottom: 16px
```

4. Primary CTA \(a-button-primary\)

```text
max-width: 343px
max-height: 57px
border-radius: 5px
color: blue-medium
​
Text (a-text-button)
font-family: Circular
font-size: 20px
font-color: #FFFFFF
padding: 16px
```


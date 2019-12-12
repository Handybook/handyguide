---
description: >-
  The header provides the core information that users need when first viewing
  the page.
---

# Headers

## Usage of Headers

Headers are used to communicate what page \(tab\) a user is on. The header component can be combined with actions like searching, filtering a list, or changing a setting.

![](../.gitbook/assets/header-overview.png)

## Types of Headers

\*\*\*\*[**1. Primary Headers \(header-primary\)**](headers-1.md#main-headers)\*\*\*\*

![](../.gitbook/assets/primary-header.png)

**2.** [**Secondary Header \(header-secondary\)**](headers-1.md#secondary-headers)\*\*\*\*

![](../.gitbook/assets/secondary-header.png)

**3.** [**Section Header \(header-section\)**](headers-1.md#section-headers)\*\*\*\*

![](../.gitbook/assets/section-header%20%282%29.png)

**4.** [**Time Subheader \(subheader-time\)**](headers-1.md#time-subheader)\*\*\*\*

![](../.gitbook/assets/time-subheader%20%281%29.png)

**5. Dropdown Subheader \(header-dropdown\)**

![](../.gitbook/assets/dropdown-header.png)

## Anatomy of Primary Headers

Primary Headers are components used on main app pages. Main headers will scroll with the content of the page.

![](https://blobscdn.gitbook.com/v0/b/gitbook-28427.appspot.com/o/assets%2F-LPWP46krdBhvVZjXTI3%2F-Lvq_NpE1vtoqF2ZbFqQ%2F-Lvqdab7hZbRlaQOJcnm%2FPrimary%20Header.png?alt=media&token=3b668d7f-d677-4684-a392-440a924111bd)

![](../.gitbook/assets/main-header-image.png)

**1. Header Label \(a-text-h1\)**

```text
a-text-h1:
font-family: bold
font-size: 24px;
font-color: text-black or white

padding-left: 16px;
padding-right: 16px;
padding-top: 16px;
```

**2.  Action Icons**  
Action icons lead users to other flows and pages or allow users to make decisions on half sheets. They are optional. 

```text
font: font-awesome
font-size: 20px
font-weight: light
font-color: blue-medium or white

Icon 1:
padding-right: 34px

Icon 2:
padding-right: 16px
```

## Anatomy of Secondary Headers

Sub-headers are used on subpages or flows that are navigated to from a main tab page. Unlike main headers, sub-headers will stick to the top so users have a way to navigate away from the page.

![](https://blobscdn.gitbook.com/v0/b/gitbook-28427.appspot.com/o/assets%2F-LPWP46krdBhvVZjXTI3%2F-Lvq_NpE1vtoqF2ZbFqQ%2F-LvqdgGsXffvXeUdPXLa%2FSecondary%20Header.png?alt=media&token=00944979-061f-45be-90eb-b959acf384a4)

![](../.gitbook/assets/subheader-image.png)

**1. Navigation \(a-nav\)**  
Helps user navigate away from the page they are currently on. It would either be a back arrow or exit.  

```
a-nav [a-nav-left will be left aligned in the 16px column]:
max-width: 16px
color: text-black

padding-left: 16px
padding-right: 8px
```

**2. Header Label \(a-text-h4\)**

```text
a-text-h4:
font-weight: medium
font-size: 16px
font-color: text-black or white

padding-top: 16px
padding-bottom: 16px
```

**3.  Action Icons \(a-header-icon\)**  
Action icons lead users to other flows and pages or allow users to make decisions on half sheets. They are optional.

```text
font: font-awesome
font-size: 20px
font-weight: light
font-color: blue-medium or white

Icon 2:
padding-right: 16px
```

**4. Divider Line \(a-divider-dark\)**  
For easy viewing and consumption, subheaders will have divider lines.

```text
a-divider-dark:
max-width: 343px
max-height: 1px
color: slate-medium-light

padding-top: 16px
```

## Anatomy of Section Headers

![](https://blobscdn.gitbook.com/v0/b/gitbook-28427.appspot.com/o/assets%2F-LPWP46krdBhvVZjXTI3%2F-Lvq_NpE1vtoqF2ZbFqQ%2F-LvqdvdmGD2NamEeoLM5%2FSection%20Header.png?alt=media&token=38aca531-ac1c-481b-83b6-8048f1fafbb5)

![Section Header](../.gitbook/assets/section-headers.png)

**1. Header Label \(a-text-h4\)**

```text
a-text-h4:
font-weight: medium
font-size: 16px
font-color: text-black

padding-top: 8px
padding-bottom: 8px
```

**2. Container**

```text
color: slate-light
max-width: 100% 
```

## Anatomy of Time Subheader

![](https://blobscdn.gitbook.com/v0/b/gitbook-28427.appspot.com/o/assets%2F-LPWP46krdBhvVZjXTI3%2F-Lvq_NpE1vtoqF2ZbFqQ%2F-Lvqdn4XnXbWlKjTQ_XU%2FTime%20Subheader.png?alt=media&token=e6413e36-89b9-412c-8236-81069c7a6c2c)

![](../.gitbook/assets/time-subheader.png)

**1. Date & Time \(a-text-paragraph\)**  
Reflects the time chosen on the native time picker.

```text
a-text-paragraph:
font-size: 16px
font-weight: book
font-color: text-black

padding-top: 12px
padding-bottom: 12px
```

**2. Divider Line \(a-divider-dark\)**  
For easy viewing and consumption, subheaders will have divider lines.

```text
a-divider-light:
max-width: 343px
max-height: 1px
color: slate-medium-light
```

## Anatomy of Dropdown Header


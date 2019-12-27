# Input Fields

## Usage of Input Fields

Input fields allow users to enter text. Input fields are normally found within a form.

![](../.gitbook/assets/text-field-overview.png)

## Types of Input Fields

\*\*\*\*[**1. Unfilled Input**](text-field.md#anatomy-of-unfilled-text-field-input-size-unfilled)\*\*\*\*

![](../.gitbook/assets/unfilled-overview.png)

\*\*\*\*[**2. Unfilled Input Field - Error State**](text-field.md#anatomy-of-unfilled-text-field-error-state-input-error-size-unfilled)\*\*\*\*

![](https://blobscdn.gitbook.com/v0/b/gitbook-28427.appspot.com/o/assets%2F-LPWP46krdBhvVZjXTI3%2F-Lx4X_NEyOzwxNTAJ9FS%2F-Lx7yFzR-B2SPEcfdDBf%2FUnfilled%20Error-%20Overview.png?alt=media&token=910d1558-7a24-4400-8601-f28e611a059a)

\*\*\*\*[**3. Filled Input Field**](text-field.md#anatomy-of-filled-input-fields-input-size-filled)\*\*\*\*

![](https://blobscdn.gitbook.com/v0/b/gitbook-28427.appspot.com/o/assets%2F-LPWP46krdBhvVZjXTI3%2F-Lx4X_NEyOzwxNTAJ9FS%2F-Lx7y7IeUwdOfY_EeC1T%2FFilled%20-%20Overview.png?alt=media&token=22b2b0af-18b3-41c4-9f12-b476a312df96)

\*\*\*\*[**4. Filled Input Field - Error State**](text-field.md#anatomy-of-filled-text-field-error-state-input-error-size-filled)\*\*\*\*

![](https://blobscdn.gitbook.com/v0/b/gitbook-28427.appspot.com/o/assets%2F-LPWP46krdBhvVZjXTI3%2F-Lx4X_NEyOzwxNTAJ9FS%2F-Lx7yLj3riWdAOB4do3w%2FFilled%20Error-%20Overview.png?alt=media&token=2ef52155-f607-42e2-bd9a-4fb9ce55d518)

## Anatomy of Unfilled Text Field \(input-\[size\]-unfilled\)

The default state of a text field.

![](https://blobscdn.gitbook.com/v0/b/gitbook-28427.appspot.com/o/assets%2F-LPWP46krdBhvVZjXTI3%2F-Lx4X_NEyOzwxNTAJ9FS%2F-Lx7yDUh9lZ5sx36anmQ%2FUnfilled%20-%20Overview.png?alt=media&token=6b02b934-4149-4381-ab0f-13ba7231f304)

![](../.gitbook/assets/unfilled-text-field-detail.png)

**1. Label/Placeholder Text \(a-text-paragraph\)  
I**ndicates what kind of information the field requires.

```text
font-weight: book
font-size: 16px
color: slate-medium-dark

padding-left: 16px
padding-right: 16px
padding-top: 16px
padding-bottom: 16px
```

**2. Structure**  
Container for content. Input fields can be at full or half width.

```text
border-radius: 5px
border: 1px
border color: slate-medium
background-color: off-white

max-height: 52px
max-width: 100% (343px)
min-width: 50% (168px)
```

## Anatomy of Unfilled Text Field - Error State \(input-error-\[size\]-unfilled\)

![](https://blobscdn.gitbook.com/v0/b/gitbook-28427.appspot.com/o/assets%2F-LPWP46krdBhvVZjXTI3%2F-Lx4X_NEyOzwxNTAJ9FS%2F-Lx7yFzR-B2SPEcfdDBf%2FUnfilled%20Error-%20Overview.png?alt=media&token=910d1558-7a24-4400-8601-f28e611a059a)

![](../.gitbook/assets/unfilled-text-field-error-detail.png)

**1. Label/Placeholder Text \(a-text-paragraph\)  
I**ndicates what kind of information the field requires.

```text
font-weight: book
font-size: 16px
color: red-medium

padding-left: 16px
padding-right: 16px
padding-top: 16px
padding-bottom: 16px
```

**2. Structure**  
Container for content. Input fields can be at full or half width.

```text
border-radius: 5px
border: 2px
border color: red-medium
background-color: off-white

max-height: 52px
max-width: 100% (343px)
min-width: 50% (168px)
```

## Anatomy of Filled Input Fields \(input-\[size\]-filled\)

![](https://blobscdn.gitbook.com/v0/b/gitbook-28427.appspot.com/o/assets%2F-LPWP46krdBhvVZjXTI3%2F-Lx4X_NEyOzwxNTAJ9FS%2F-Lx7y7IeUwdOfY_EeC1T%2FFilled%20-%20Overview.png?alt=media&token=22b2b0af-18b3-41c4-9f12-b476a312df96)

![](../.gitbook/assets/filled-text-field-detail.png)

**1. Label \(a-text-label\)**  
Indicates what kind of information the field requires.

```text
font-weight: book
font-size: 10px 
color: slate-medium-dark

padding-left: 16px
padding-right: 16px
padding-top: 8px
padding-bottom: 3px
```

**2. Content \(a-text-paragraph\)**  
User generated text

```text
font-weight: book
font-size: 16px 
color: text-black

padding-left: 16px
padding-right: 16px
padding-bottom: 8px
```

**3. Structure**  
Container for content. Input fields can be at full or half width.

```text
border-radius: 5px
border: 1px
border color: slate-medium
background-color: off-white

max-height: 52px
max-width: 100% (343px)
min-width: 50% (168px)
```

## Anatomy of Filled Text Field - Error State \(input-error-\[size\]-filled\)

![](https://blobscdn.gitbook.com/v0/b/gitbook-28427.appspot.com/o/assets%2F-LPWP46krdBhvVZjXTI3%2F-Lx4X_NEyOzwxNTAJ9FS%2F-Lx7yLj3riWdAOB4do3w%2FFilled%20Error-%20Overview.png?alt=media&token=2ef52155-f607-42e2-bd9a-4fb9ce55d518)

![](../.gitbook/assets/filled-text-field-error-detail.png)



**1. Label \(a-text-label\)**  
Indicates what kind of information the field requires. Can be updated to include helper text.

```text
font-weight: book
font-size: 10px 
color: red-medium

padding-left: 16px
padding-right: 16px
padding-top: 8px
padding-bottom: 3px
```

**2. Content \(a-text-paragraph\)**  
User generated text.

```text
font-weight: book
font-size: 16px 
color: red-medium

padding-left: 16px
padding-right: 16px
padding-bottom: 8px
```

**3. Structure**  
Container for content. Input fields can be at full or half width.

```text
border-radius: 5px
border: 2px
border color: red-medium
background-color: off-white

max-height: 52px
max-width: 100% (343px)
min-width: 50% (168px)
```

## Animation

#### Long Form Text

When a user taps into a long form text field, any placeholder copy should disappear so the user can start typing.

#### Short Form Text

When a user taps into an unfilled short text field, the Label should animate up to the left hand corner of the container \(see example below\). 

![](../.gitbook/assets/text-field-animation.gif)


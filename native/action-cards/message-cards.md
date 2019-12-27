---
description: >-
  Message cards give the user a preview of the last message they received. It
  also leads the user to the message thread, where they can respond.
---

# Message Cards

## Usages of Message Cards

Message cards are found in the messages tab. It will reflect key information like the image of the person who sent the message, the time the message was sent, and a preview of the message. 

![](../../.gitbook/assets/message-overview%20%281%29.png)

### Types of Message Cards

\*\*\*\*[**1. Unread Message Card \(m-card-message-unread\)**](message-cards.md#anatomy-of-unread-message)\*\*\*\*

![](../../.gitbook/assets/message-unread.png)

\*\*\*\*[**2. Read Message Card \(m-card-message-read\)**](message-cards.md#anatomy-of-read-message)\*\*\*\*

![](../../.gitbook/assets/message-read%20%281%29.png)

## Anatomy of Unread Message

Unread message cards are used to represent a new message or messages that have not been opened. Like other cards, unread message cards are stacked vertically in sequential order \(the most recent at the top\).

![](https://blobscdn.gitbook.com/v0/b/gitbook-28427.appspot.com/o/assets%2F-LPWP46krdBhvVZjXTI3%2F-LwowslbkEwQ1ANHObRc%2F-Lx3u7yV39vQhG7ymlHu%2FMessage-Unread.png?alt=media&token=15df67a7-a925-4575-bf6b-1c489e7dfc9a)

![Unread Message Card](../../.gitbook/assets/unread-message.png)

**1. Unread Indicator \(a-avatar-unread\)**  
If the message is unread, the avatar will have an outline around it to indicate that the message is unread.   
  
In the consumer app, an [**Image Avatar**](../avatars.md#image-avatars-avatar-image) or the [**Customer Default Avatar**](../avatars.md#default-avatars-customer-avatar-customer-default) \(for customers with no profile picture\) can be used.   
  
In the pro app, an [**Image Avatar**](../avatars.md#image-avatars-avatar-image) or the [**Pro Default Avatar**](../avatars.md#default-avatars-pros-avatar-pro-default) \(for pros with no profile picture\) can be used.

```text
a-avatar-unread:
max-height: 64px
max-width: 64px
border-color: blue-medium
border-width: 3px
padding-right: 16px
```

**2. Sender Name \(a-text-h4\)**

```text
a-text-paragraph-bold:
font-size: 16px
font-weight: bold
font-color: text-black
```

**3. Time \(a-text-subtitle-medium\)**  
Reflects when the last message was sent.

```text
a-text-subtitle-medium:
font-size: 12px
font-weight: medium
font-color: text-black
padding-right: 32px
```

**4. Message: \(a-text-paragraph\)**  
This area will house the preview the first 2 lines of the message.

```text
a-text-paragraph:
font-size: 16px
font-weight: book
font-color: text-black

Padding:
padding-left: 16px
padding-right: 16px
```

**5. Divider Line \(a-divider-light-343\)**  
For easy viewing and consumption, cards will have divider lines.

```text
a-divider-light:
max-width: 343px
max-height: 1px
color: slate-light
```

## Anatomy of Read Message

Read messages will adopt a lot of the spacing and structure of the unread message. The only differences will be text treatment.

![](https://blobscdn.gitbook.com/v0/b/gitbook-28427.appspot.com/o/assets%2F-LPWP46krdBhvVZjXTI3%2F-LwowslbkEwQ1ANHObRc%2F-Lx3uDNIHH1PH--FB0Gl%2FMessage-Read.png?alt=media&token=d1dbc47e-ccfd-4bba-8fa8-31a3110ee377)

![Read Message Card](../../.gitbook/assets/read-message.png)

**1. Read Avatars \(a-avatar-read\)**  
Will adopt the same avatar styling but with no blue indicator

```text
a-avatar-read:
max-height: 64px
max-width: 64px
opacity: 75%
padding-right: 16px
padding-left: 16px
```

**2. Sender Name \(a-text-paragraph\)**

```text
a-text-paragraph-tert:
font-size: 16px
font-weight: book
font-color: slate-dark
```

**3. Time** \(**a-text-subtitle\)**

```text
a-text-subtitle:
font-size: 12px
font-weight: book
font-color: slate-medium-dark
padding-right: 32px
```

**4. Message \(a-text-paragraph-tert\)**

```text
a-text-paragraph-tert:
font-size: 16px
font-weight: book
font-color: slate-medium-dark

Padding:
padding-left: 16px
padding-right: 14px
```

**5. Divider Line \(a-divider-light-343\)**  
For easy viewing and consumption, cards will have divider lines.

```text
a-divider-light:
max-width: 343px
max-height: 1px
color: slate-light
```


---
description: Message Bubbles are populated with messages sent between pros and customers.
---

# Message Bubbles

## Usage of Message Bubbles

Message bubbles include the message from the user and the time it was sent. Depending on the context and length of the messages, the style of message bubble changes.

![](../.gitbook/assets/message-overview%20%282%29.png)

## Types of Message Bubbles

[**1. Sent Messages \(m-message-sent\)**](message-threads.md#sent-messages-m-message-sent)\*\*\*\*

![](../.gitbook/assets/sent-message.png)

\*\*\*\*[**2. Received Messages \(m-message-received\)**](message-threads.md#received-messages-m-message-received)

![](../.gitbook/assets/received-message.png)

## Sent Messages \(m-message-sent\)

When a user is sending the message to another message, that message will be populated in the chat detail view. Depending on the length of the message, the UI's max width will change.

![](https://blobscdn.gitbook.com/v0/b/gitbook-28427.appspot.com/o/assets%2F-LPWP46krdBhvVZjXTI3%2F-LwFe3Dfdi2UH1O-quQU%2F-LwFjUxCUIQJ0BsTC6K_%2Fsent%20message.png?alt=media&token=f1278549-2cc6-49ca-9d64-18d26ea33d46)

![](../.gitbook/assets/sent-bubbles.png)

**1. Container**

```text
background: blue-medium-light 
border-radius: 5px

m-message-sent-long:
max-width: 66.667% (excluding margins)

m-message-sent-medium:
max-width: 50% (excluding margins)

m-message-sent-short:
max-width: 33.333% (excluding margins)
```

**2. Message Text \(a-text-paragraph\)**

```text
font-weight: book
font-size: 16px
font-color: text-black

padding-top: 16px
padding-left: 12px
padding-right: 12px
padding-bottom: 8px
```

**3. Time Stamp \(a-text-label\)**  
After 24 hours, the message time stamp will reflect the date and time it was sent.

```text
font-weight: book
font-size: 10px
font-color: slate-dark

padding-top: 8px
padding-bottom: 16px
```

## Received Messages \(m-message-received\)

Received messages will adopt most of the stylings of sent messages.

![](../.gitbook/assets/received-bubbles.png)

1. Background

```text
background: dark-white 
border-radius: 5px

m-message-sent-long:
max-width: 66.667% (excluding margins)

m-message-sent-medium:
max-width: 50% (excluding margins)

m-message-sent-short:
max-width: 33.333% (excluding margins)
```

2. Message Text \(a-text-paragraph\)

```text
font-weight: book
font-size: 16px
font-color: text-black

padding-top: 16px
padding-left: 12px
padding-right: 12px
padding-bottom: 8px
```

3. Time Stamp \(a-text-label\)  
After 24 hours, the message time stamp will reflect the date and time it was received.

```text
font-weight: book
font-size: 10px
font-color: slate-dark

padding-top: 8px
padding-bottom: 16px
```


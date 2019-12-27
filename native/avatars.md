---
description: Avatars are used to represent users.
---

# Avatars

## Usage of Avatars

Avatars house an image that represent the user \(profile picture or user's initials\). 

![](../.gitbook/assets/avatar-overview.png)

## Types of Avatars

\*\*\*\*[**1. Image Avatar \(avatar-human\)**](avatars.md#image-avatars-avatar-image)

![](../.gitbook/assets/image-avatars.png)

\*\*\*\*[**2. Pro Default Avatar \(avatar-pro-default\)**](avatars.md#default-avatars-pros-avatar-pro-default)\*\*\*\*

![](../.gitbook/assets/default-avatar.png)

\*\*\*\*[**3. Customer Default Avatar \(avatar-customer-default\)**](avatars.md#default-avatars-customer-avatar-customer-default)\*\*\*\*

![](../.gitbook/assets/customer-detault.png)

\*\*\*\*[**4. Booking Avatar \(avatar-booking\)**](avatars.md#booking-avatar-a-avatar-bookings)\*\*\*\*

![](../.gitbook/assets/booking-avatar.png)

## Image Avatars \(avatar-image\)

Image avatars are used to represent pros and customers, if they have a profile image.

![](https://blobscdn.gitbook.com/v0/b/gitbook-28427.appspot.com/o/assets%2F-LPWP46krdBhvVZjXTI3%2F-LvpvsJIxtnd-bVB2Qvc%2F-Lvpz-p7aH2z6GBwUJ-v%2FImage%20Avatars.png?alt=media&token=ab85c381-18df-48fc-b956-60785689620e)

![](../.gitbook/assets/pro-avatar-detail.png)

1. Body: The image that represents the user. 

```text
max-width: 64px
max-height: 64px
```

2. Customer app only - When a pro is favorited, the status will be represented by a heart. 

```text
max-width: 14px
max-height: 14px
```

## Default Avatars - Pros \(avatar-pro-default\)

Default Avatars are used when a pro does not have a profile picture.

![](../.gitbook/assets/default-avatar-detail.png)

1. Body

```text
max-width: 64px
max-height: 64px
background-color: blue-light
```

2. Status: When a pro is favorited, the status will be represented by a heart. 

```text
max-width: 14px
max-height: 14px
```

## Default Avatars - Customer \(avatar-customer-default\)

Default Avatars are used when a customer does not have a profile picture.

![](../.gitbook/assets/default-cust-detail.png)

1. Customer Initials \(a-text-avatar\)

```text
font-size: 24px
font-weight: book
font-color: text-black
```

2. Body

```text
max-width: 64px
max-height: 64px
background-color: slate-light
```

## Booking Avatar \(avatar-bookings\)

Booking avatars are used in [**card-bookings**](action-cards/booking-cards.md) to represent the service. The icon in the avatar will correspond with the service and will take on the [**two-tone styling**](../brand-guidelines/iconography.md#usage-of-two-tone-icons).  

![](../.gitbook/assets/bookign-avatar-detail.png)

1. Body

```text
max-width: 64px
max-height: 64px
background-color: blue-light
```


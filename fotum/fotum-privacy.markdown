---
layout: fotum-page
title:  Privacy - Fotum
permalink: /software/fotum/privacy
---

# Fotum – Privacy

## Fotum Roku App:

### What do we collect?

The Fotum Roku App stores two types of data:

- If you use a Cloud provider for your photos, then the App will keep these tokens stored on your device to be used to access that service. These tokens are not personally identifiable.
- If you use a Cloud provider, then the App caches photos locally on the device to save on data being downloaded and to improve performance. These photos are only available to the Fotum app, and not other apps on the device.
- If you use a USB drive for your photos, then Fotum reads from that drive, and needs no other data.
What don’t we collect?

No other data is collected. This includes:

- Details of App usage
- Personally identifiable information
- No data is sent from your Roku other than that required to access your cloud provider.

### How to clear the data - USB?

If you are using a USB drive, then there is no stored data. Removing the USB drive clears everything.


### How to clear the data - Cloud Provider?

If you are using a Cloud provider for your photos, then there are two actions to take to clear data:

To clear saved credentials:

- In the Fotum screensaver settings, go to the Current Provider screen
- Select “Clear” to remove your saved credentials

To clear any cached photos:

- Go to the home menu
- Press Home 5 times
- Press Up 1 time
- Press Rewind 2 times
- Press Fast Forward 2 times

Clearing the cache may take up to 30 seconds, during which time your Roku device may restart.

## Fotum Auth Service:

### What do we collect?

The Fotum Auth service (hosted at [https://fotum-auth.ja2.co.uk](https://fotum-auth.ja2.co.uk), in the United Kingdom), handles the authentication process for cloud based photo providers.

During the authentication process your credentials are given directly to your cloud provider on their authentication screen – the Fotum Roku app, and the Fotum-Auth service do not see these. One you’ve authenticated and approved Fotum’s access request, a token is sent to the Fotum-Auth service and held for a limited time. It is not permanently stored. The code that you are given is a one-time code. Once you’ve used it all data is cleared from the Fotum-Auth service immediately.

### What don’t we collect?

No other data is collected.

### How to clear the data?

As no permanent record is kept, simply wait for it to expire after 5 minutes.

Alternatively, enter the code into your Roku device, which will clear the data from the service, however this would mean that you’d need to also clear the device data if you wish.

### About Dropbox authentication:

When you authorise Dropbox access, an Apps/Fotum folder is automatically created in your Dropbox, if not already present. Fotum is only given access this folder and is secured from accessing any of your other Dropbox data. Copy your photos into the Apps/Fotum folder to show them on the Fotum screensaver.

The contents of the folder are rechecked each time the screensaver starts, so if images are removed from the folder, they won’t be shown in the screensaver next time it runs.

To revoke the Fotum Roku app’s access to your Dropbox account, see the Connected Apps area of your Dropbox profile. Scroll down to the bottom to the “Apps with access to your Dropbox” section and click the delete (X) button on the row in the table for Fotum.

### About Google Photos authentication:

When you authorise Google Photos access, Fotum is granted read-only access to your photo library. Fotum looks for an album named Fotum within your account, and will use only images from this album for the screensaver.

The contents of the album are rechecked each time the screensaver starts, so if images are removed from the album, they won’t be shown in the screensaver next time it runs.

Google’s tokens expire approximately every hour. To maintain access for the screensaver the Fotum Roku app will request a refreshed token from Google when necessary.

Due to the way that Google’s authentication works, if you need to get a new code for Fotum – for example if it the original code stops working or there is a problem when first setting up, then you will need to go to your account settings and completely remove access for Fotum before re-authorizing, otherwise Fotum will be unable to access your account after the first time. To remove Fotum’s access completely, see your [Google Account Permissions page](https://myaccount.google.com/permissions).

### How your cloud data is handled by the Fotum Roku app:

Once authorized, your photos are downloaded directly from the cloud provider to your Roku device by the Fotum Roku app, and not through the Fotum-Auth service or any other JA2 owned system.

Once downloaded to your Roku device, your images may be cached locally so that they can be re-used within the screensaver, reducing the amount of data consumed by the app. The Roku device itself manages and encrypts this storage, so that the data is available to the Fotum Roku app only. To clear this, uninstall and reinstall the Fotum Roku app.
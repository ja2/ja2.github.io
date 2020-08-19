---
layout: fotum-page
title:  Troubleshooting - Fotum
permalink: /software/fotum/troubleshooting
---

# Fotum – Troubleshooting

Here are some tips for common problems when using Fotum:

### Fotum can’t find any the USB drive, or can’t find any images on the USB drive:

Fotum loads images from a fotum folder on a USB drive plugged into your Roku device. For help on setting this up, see the Quick Start guide.

### There was a problem connecting to Google Photos – Error from Google was: Re-authentication of apps is not permitted:

Due to the way that Google’s authentication works, if you need to get a new code for Fotum – for example if it the original code stops working or there is a problem when first setting up, then you will need to go to your account settings and completely remove access for Fotum before re-authorizing, otherwise Fotum will be unable to access your account after the first time. To remove Fotum completely, see your [Google Account Permissions page](https://myaccount.google.com/permissions).

### Fotum has started to show an “error downloading” message for photos from Cloud providers:

If previously Fotum worked fine, and now shows an “error downloading” message some images, it may be necessary to clear the cache on your Roku.

Fotum uses a Roku feature named cachefs to improve performance and reduce data usage with Cloud providers, however at the time of release this feature was still in Beta, meaning that there may be problems with it. Sometimes it is necessary to clear this cache and let Fotum re-download images.

To clear the cache:

- Go to the home menu
- Press Home 5 times
- Press Up 1 time
- Press Rewind 2 times
- Press Fast Forward 2 times

Clearing the cache may take upto 30 seconds, during which time your Roku device may restart.

### Some of my photos are the wrong way up, or don’t show in the middle of the screen.

Fotum uses information saved in the image file to work out how to correctly orient and position photos. However in some cases the information may be formatted unusually, causing Fotum to get the calculations wrong.

To work around this you can clear the extra information from the photo using your computer. There is a guide on how to do this on Windows and Mac here. Fotum should then be able to handle the image correctly.

If you you are happy to do so it would be great if a sample image can be provided via the contact details below. This will be used to adjust Fotum’s algorithm, and an update will be released with the new fix.

## Contact:

To get in contact about Fotum, please add a comment below, or email us at fotum [at] ja2.co.uk.

Please include as much detail as possible about the problem, along with which Roku device you have, and, if applicable, the screen size (SD, HD, Full HD, 4K etc) of your TV.

Fotum includes a debug mode, enabled from the Fotum screensaver settings. In some scenarios this can display additional diagnostic information. When you log any issues, if possible, please enable Debug mode and include any information displayed when reporting your issue.
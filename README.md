# Magellan AI Attribution Pixel GTM Template

> "I have to believe in a world outside my own mind. I have to believe that my actions still have meaning, even if I can't remember them."
>
> -- Leonard, _Memento_

This template allows you to inject Magellan AI's tracking pixel into your website using Google Tag Manager.  Once
installed, the tag tracks users' actions on advertiser websites to correlate them with podcast downloads, to attribute
conversions to podcast ad impressions.

## Installation and Setup

1. Add the Magellan AI Attribution Pixel to your Google Tag Manager container.
   [(More info)](https://support.google.com/tagmanager/answer/6103696?hl=en)
2. Add your attribution pixel API token to the tag's configuration panel.  Contact your account representative for more
   information on setting up your account and retrieving your token.  (N.B.: this token is different from any other API
   tokens from Magellan you may already use.)
3. Set the pixel to fire on the events you wish.  Usually, this will be all page views.
4. That's it!  You're now sending data to Magellan AI, which we'll match up with your podcast ads.

## Permissions

This tag requires only the `sendPixel` permission, which requests a transparent, one-pixel GIF file from Magellan AI's
servers.

## Legal Notices

All content in this repository is copyright © 2022 Twenty Nine Enterprises, Inc. DBA Magellan AI.  All rights reserved.

For information on how collected information is used and protected, please visit our
[privacy policy](https://www.magellan.ai/privacy).

## More Information

Please visit [our website](https://www.magellan.ai) to learn more about Magellan AI and how we can help your brand
succeed in the quickly-changing landscape of podcast marketing.

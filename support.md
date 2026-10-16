---
layout: default
title: Support
permalink: /support/
---

# NightRead support

NightRead {{ site.nightread.version }} is a Safari extension for iPhone and iPad with **On, Auto, and Off** modes, **Soft gray, Black, and Warm** reading appearances, and exceptions for individual website hostnames.

## Purchase and requirements

Download NightRead from the [App Store]({{ site.nightread.app_store_url }}) where available. Availability depends on your Apple Account's country or region; check your local App Store listing.

The **U.S. base price is {{ site.nightread.us_price }} as a one-time purchase**. Apple provides comparable local prices for other storefronts and may adjust them for taxes or exchange rates. Check your App Store for the current local price. There are no subscriptions, in-app purchases, ads, or NightRead accounts.

Version {{ site.nightread.version }} requires **iOS or iPadOS {{ site.nightread.minimum_ios }} or later** and Safari. Font selection and manual brightness/contrast sliders are not offered in the popup.

## Set up NightRead

1. Install NightRead and open the app. Use the help button for **Setup Instructions**.
2. On iOS/iPadOS 18 or later, open **Settings → Apps → Safari → Extensions → NightRead**. On iOS/iPadOS 17, open **Settings → Safari → Extensions → NightRead**.
3. Turn on **Allow Extension**, then allow access to the websites you want to use. **All Websites is optional.**
4. Explicitly open a light webpage such as `https://example.com/` in **Safari**.
5. Open the Page Menu beside the address bar and select **NightRead**. Depending on your Safari layout, it may be under Extensions or More.
6. Choose **On** and a reading appearance. Reload the webpage if needed. Choose **Off** to restore the website's own appearance.

Where supported, **Set up in Safari** in the app opens Safari's extension settings. Other system versions show the manual guide. If the shortcut cannot open Settings, follow the manual steps above. The app cannot verify Safari settings; check the extension's result on a webpage.

The app's **Open a Sample Webpage** link follows your default browser. If that browser is not Safari, open the URL in Safari yourself to use the extension. Private Browsing has a separate extension permission; enable it only if you want to use NightRead there.

## Modes and reading appearances

- **On** applies the selected dark appearance to websites Safari permits NightRead to access.
- **Auto** follows the device's system appearance. A light system appearance leaves the page unchanged; a dark system appearance enables NightRead.
- **Off** removes NightRead's appearance from the page.
- Choose **Soft gray**, **Black**, or **Warm** in the popup. **Reset** returns the reading appearance to Soft gray; it does not clear modes or website exceptions.

The **Day/Night** sample in the app is a local demonstration of Soft gray. It does not change your saved Safari extension preferences or website permissions.

## Website exceptions

To keep a website unchanged, turn on **Disable on this website** in the popup. This saves only the exact hostname shown. An exception for `example.com` does not automatically include `www.example.com` or other subdomains.

To enable NightRead there again, turn that switch off, or open **Website exceptions** and choose **Remove** beside the hostname. Other websites keep their existing settings. Revoking Safari website access is a separate setting; removing an exception does not grant permission in Safari.

## If a page does not change

- Check **Allow Extension** in Safari settings and access for that website.
- Check the selected mode. If it is **Auto** and your system uses a light appearance, the unchanged webpage is expected. Choose **On** to try dark appearance.
- Check **Disable on this website** and the saved **Website exceptions** list.
- If you use Private Browsing, check its separate extension permission.
- Try a light webpage: a website that already has a dark theme may be left unchanged.
- Reload the webpage, then reopen the popup. The saved mode and current page's result are reported separately. An unavailable or failed result is not confirmation that the page has changed.
- Some pages, embedded frames, and Safari system pages cannot be styled consistently. Choose **Off** or disable NightRead for that hostname if a site looks wrong.

If NightRead is absent from Extensions, open the installed app once and check Safari settings again. If settings cannot be read or saved in the popup, close and reopen it, then retry your choice. If the issue continues, include the displayed message in your feedback.

## What's new in 2.0

- A refreshed NightRead app and Safari popup.
- On, Auto, and Off controls with three reading appearances.
- Exact-host website exceptions and an exception management list.
- Clearer status for the current webpage, including native dark themes and access issues.
- A local Day/Night sample, setup instructions, and localized controls, including Simplified Chinese.

## Privacy

NightRead has no analytics, advertising, account system, or data collection service. Preferences and website exception hostnames stay in local storage. Styling a page can request its referenced stylesheets or images through the browser; see the [privacy policy]({{ '/privacy/' | relative_url }}).

## Feedback

Use the existing [issue tracker](https://github.com/nightread/nightread.github.io/issues). Avoid sharing passwords or private page content. Useful details include:

- Device model and iOS/iPadOS version.
- NightRead version and the public webpage URL, if available.
- The selected mode and reading appearance, the page status shown in the popup, and whether choosing Off restored the page.
- Steps to reproduce; an optional screenshot with personal information removed.

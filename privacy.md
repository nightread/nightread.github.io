---
layout: default
title: Privacy Policy
permalink: /privacy/
---

# Privacy policy

Last updated: October 16, 2026. This policy describes NightRead {{ site.nightread.version }} for iPhone and iPad.

## Extension data handling

NightRead has no analytics SDK, advertising service, account system, or backend that collects browsing data. It processes webpage content and styles on your device to apply your selected reading appearance. It does not send page content, full page URLs, or browsing history to a NightRead service.

Safari extension local storage keeps your selected mode, reading appearance, older appearance values retained for compatibility, and preference migration information. If you choose **Disable on this website**, it also stores the normalized hostname, such as `example.com`, so NightRead can remember that exception. An exception stores the hostname rather than a full URL, path, or query string. NightRead does not create a continuous browsing-history log.

For compatibility with older versions, the extension may read existing preferences from the containing app's local App Group storage. This is communication between components on your device, not a connection to a remote NightRead server.

## Retention and your controls

Preferences and exception hostnames remain in local extension storage so your choices can be used again. You can change modes and reading appearances in the Safari popup.

- To delete a stored website exception, open **Website exceptions** and choose **Remove** beside the hostname, or turn off **Disable on this website** for that hostname. Each exception applies only to the exact hostname shown.
- **Off** removes NightRead's reading appearance from the page. It changes the saved mode and does not erase website exceptions or other saved preferences.
- **Reset** returns the reading appearance to Soft gray. It does not clear all saved settings.
- You can revoke website access or disable the extension in Safari settings. Changing authorization does not itself delete the saved exceptions described above.

NightRead does not keep a server copy of these preferences. Local storage retention, device backups, and restoration are controlled by Safari and the operating system; Private Browsing should not be treated as a way to erase saved extension preferences.

## Webpage resources

Dark Reader is bundled with the app; NightRead does not download its JavaScript at runtime. To style a webpage, the extension can request that page's referenced stylesheets or images through the browser. These requests may reach the website or its resource hosts under normal browser networking rules. The website or resource host may process request information under its own policies. NightRead does not use those requests as an analytics or data collection service.

The NightRead app's Day/Night sample uses bundled content and the bundled reading engine. It does not change Safari website permissions or confirm that the extension is enabled. Opening a sample webpage or a help/privacy link uses ordinary browser networking for that destination.

## Permissions

- Website access lets NightRead read webpage content and change its appearance on sites you permit in Safari.
- Local storage saves modes, reading appearances, compatibility values, and explicitly selected website exceptions.
- Native messaging reads older locally stored preferences during migration; it does not communicate with a remote server.

You choose website access in Safari settings. All Websites access is optional. Private Browsing has a separate extension permission, which is only needed if you want NightRead to work there.

## Support website and feedback

This site is hosted on GitHub Pages, which handles ordinary website requests according to its own policies. Reports you submit to the [issue tracker](https://github.com/nightread/nightread.github.io/issues) are handled by GitHub and may be public. Do not include passwords or private browsing content.

## Contact and updates

Ask privacy questions through the same issue tracker without including private webpage content. Updates to this policy will be posted here with a revised date when NightRead's implementation or data handling changes.

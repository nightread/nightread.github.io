# NightRead support website

Jekyll/GitHub Pages content for the NightRead Safari extension: the product page, setup and troubleshooting, and privacy policy.

## Release alignment

The current content is prepared for **NightRead 2.0 / build 2**, whose App Store Connect metadata reports a minimum of iOS/iPadOS **17.0**. The U.S. base price is **US$0.99 as a one-time purchase**, with comparable local prices provided automatically by Apple. Availability is managed in App Store Connect. Public pages use a region-neutral App Store link and direct readers to their local storefront for availability and pricing. Verify the current availability, price, and released version before publishing; editing this repository does not change App Store Connect settings or release the app.

Release values are centralized under `nightread` in [_config.yml](_config.yml). Keep them aligned with the approved release whenever the version, price, or minimum OS changes.

## Content

- [Product page](index.md): price, On/Auto/Off modes, Soft gray/Black/Warm palettes, website exceptions, and the local Day/Night sample.
- [Support](support.md): setup paths for iOS/iPadOS 17 and 18+, website access, troubleshooting, and the 2.0 changes.
- [Privacy](privacy.md): local preferences and exact-host exceptions, removal controls, browser resource requests, and the existing feedback channel.

Descriptions should follow the shipped implementation. The app's sample is separate from Safari extension authorization. Website compatibility varies. Do not promise font controls, manual brightness sliders, universal compatibility, or health benefits.

## Preview and publication

With a GitHub Pages compatible Jekyll environment available, run:

```sh
jekyll serve --destination /tmp/nightread-support-preview
```

Review the home, support, and privacy pages before publishing. Keep generated site output and local dependency directories outside the repository. A content commit should not include preview files or machine-specific paths.

The site URL remains `https://nightread.github.io`. Feedback uses the existing [issue tracker](https://github.com/nightread/nightread.github.io/issues). Preserve the configured author and contact channels unless the owner approves a change.

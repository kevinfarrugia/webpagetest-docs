---
title: WebPageTest Change Log
eleventyNavigation:
  key: WebPageTest Change Log
  order: 999
---
# WebPageTest Change Log

## April, 2021
- **April 15:** The mobile emulation devices are now also [available directly in the browser dropdown](https://twitter.com/patmeenan/status/1382790307956264963) for any locations that support testing with Chrome. It will use Chrome stable for the emulation. Emulating mobile with beta or canary is still possible by manually selecting the emulation options in the Chromium tab of advanced settings.
- **April 14:** Cumulative Layout Shift [was updated to use](https://twitter.com/patmeenan/status/1382439517328715777) the new windowed approach. The [filmstrip also now shows layout window scores](https://twitter.com/tkadlec/status/1382440917186002945), and additional context is available in the JSON. [PR #1478](https://github.com/WPO-Foundation/webpagetest/pull/1478)
- **April 9:** [WebPageTest test results now pull in URL-specific field data from Chrome User Experience Report](https://twitter.com/patmeenan/status/1380514866390269952)
- **April 6:** [WebPageTest moved to a new account management system](https://twitter.com/patmeenan/status/1380514866390269952). The enhanced and fully supported [WebPageTest API](https://product.webpagetest.org/api?utm_source=docs&utm_medium=docs&utm_campaign=changelog&utm_content=api) was [released to general availability](https://blog.webpagetest.org/posts/the-webpagetest-api-has-gone-public/).

## March, 2021
- **March 23, 2021:** The default desktop browser size was [changed from 1024x768 to 1376x768](https://twitter.com/patmeenan/status/1374444703962132490). A dropdown was added to choose from a number of other resolution sizes.
- **March 22, 2021:** First Contentful Paint, Largest Contentful Paint and Layout Shifts were [added to the WebPageTest waterfall](https://twitter.com/patmeenan/status/1374043494789038080)
- **March 22, 2021:** A new interface [for WebPageTest.org](https://twitter.com/patmeenan/status/1374016216709357571) was released

## February, 2021
- **February 15, 2021:** When test agents are terminated (during OS shutdown for example), re-queue the test they are working on for another agent to test. This helps with support for autoscaling cloud agents so jobs are not lost when agents are terminated.

## January, 2021
- **January 28, 2021:** Added support for [testing Safari with the iOS simulator](https://twitter.com/patmeenan/status/1354875525727211522) on Intel and Apple silicon Macs.
- **January 25, 2021:** Added test options for [disabling AVIF and WebP support in Chrome](https://twitter.com/TheRealNooshu/status/1353780078791032832) for testing impact of the new formats on performance.
- **January 21, 2021:** Added an option to [enable the V8 sampling profiler](https://twitter.com/patmeenan/status/1352434691740213260) for much richer JavaScript stack traces.
- **January 6, 2021:** Added [Largest Contentful Paint](https://twitter.com/patmeenan/status/1346941018227187716) visualizations to the filmstrip view.

## December, 2020
- **December 12, 2020:** Changed video rendering to be [done on the fly](https://twitter.com/patmeenan/status/1337805490340966404) and added support for generating animated Gifs.

## November, 2020
- **November 30, 2020:** Added [layout shift visualizations](https://twitter.com/TheRealNooshu/status/1333525160259891207) to the filmstrip view.
- **November 25, 2020:** Updated the [JavaScript execution visualization](https://twitter.com/patmeenan/status/1331625445104754688) in the waterfall to better represent frequent but short events.
- **November 13, 2020:** Added support for [testing WebKit on Linux.](https://twitter.com/patmeenan/status/1327277663891894273)
- **November 4, 2020:** Mobile emulation user agent strings were changed to [always be up to date](https://twitter.com/patmeenan/status/1324145162776420353) with the version of Chrome that they are running on.
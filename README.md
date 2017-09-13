# Timer for Websites That Steal Your Time

This project helps to control time was spent on sites. It requires special extension for Chrome browser.

# Installing

Install extension for Chrome browser [Custom JavaScript for websites](https://chrome.google.com/webstore/detail/custom-javascript-for-web/poakhlngfciodnhlhhgnaaelnpjljija).

Open configuration of [cjs](https://chrome.google.com/webstore/detail/custom-javascript-for-web/poakhlngfciodnhlhhgnaaelnpjljija) browser extension on the site you want to control. Click on the link "your own external scripts", add path [https://cdn.rawgit.com/conformist-mw/34_timemachine/652f1487/index.js](https://cdn.rawgit.com/conformist-mw/34_timemachine/652f1487/index.js). Don`t forget to press "enable cjs for this host" to enable custom JS.

After that on selected domains appears a small counter (at top-left corner) that countdown 3 minutes while tab is active and then show you motivation quotes repeatedly. Default step between alerts is 30 seconds, feel free to input desired timeout and press `OK` button otherwise just `CANCEL` it.

For faster development you can use JS code hosted on localhost. Simple web server can be used for that, run:

```bash

python3 -m http.server
```

Add path `http://localhost:8000/index.js` to [cjs](https://chrome.google.com/webstore/detail/custom-javascript-for-web/poakhlngfciodnhlhhgnaaelnpjljija) browser extension. Done.


# Project Goals

The code is written for educational purposes. Training course for web-developers - [DEVMAN.org](https://devman.org)

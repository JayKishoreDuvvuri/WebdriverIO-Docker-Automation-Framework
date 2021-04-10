# WebDriverIO - Page Object Model - Automation - Docker

Design Page Objects and run Tests

## Application Under Test
```bash
http://automationpractice.com/index.php
```

## Run application

Clone the repository

```bash
git clone https://github.com/JayKishoreDuvvuri/WebdriverIO-CrossBrowser-Test-Automation-Framework
```

Folder Structure

    ├── ...
    │
    ├── pages                               # Generic functionality for tests
    │   |
    │   ├── basePage.js                     # Base page testing functionality
    │   ├── landingPage.js                  # Landing page testing functionality
    │
    │
    ├── test                                # Test suite
    │    ├── addToCart.test.js              # Automated Test Script
    │    ├── checkTotalPrice.testjs         # Automated Test Script
    │    ├── productNames.test.js           # Automated Test Script
    │    ├── toggleProductColour.test.js    # Automated Test Script
    │
    │
    ├── utils                               # Utility files for testing
    │    ├──locators.js                     # HTML and CSS identifier for elements to test
    │
    └─── errorShots                         # Screenshot captured for failed tests


### Docker Locally
Build image and run tests in Docker

```bash
docker build -t webdriverio:v1 . 
docker run -it webdriverio:v1
```

### Docker Hub
```bash
docker pull jaykishoreduvvuri/wdiochrome:v2 
docker run -it jaykishoreduvvuri/wdiochrome:v2 
```


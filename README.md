# RO Scraper

> Simple in browser scraper using Selenium and Webdriver.IO

## Project Setup

### Dependencies

 - Dockers
 - Node.js
 - Yarn

### Installation

    git clone git@github.com:remoteorigin/ro_scraper.git
    cd ro_scraper
    yarn

## Run Scraper

### Configure Start page

Change variable `startUrl` in `scraper.js` to page you want start with 

### Start Selenium
    
    npm run start-selenium
    
### Start Scraper

    npm run test  

When you are done, stop Selenium

    npm run stop-selenium

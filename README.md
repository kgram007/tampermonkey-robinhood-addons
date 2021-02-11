# Tampermonkey Robinhood Addons
Tampermonkey scripts to enhance trading in robinhood

## How to install

1. Install Tampermonkey browser extension (for [Chrome](https://chrome.google.com/webstore/detail/tampermonkey/dhdgffkkebhmkfjojejmpbldmpobfkfo?hl=en), [Firefox](https://addons.mozilla.org/en-US/firefox/addon/tampermonkey/), [Microsoft Edge](https://www.microsoft.com/store/apps/9NBLGGH5162S))
2. Go to [Robinhood Watchlist Monitor](https://greasyfork.org/en/scripts/421553-robinhood-watchlist-monitor)
3. Click on the "Install" button

**Note:** Tested only on Chrome and Firefox. Yet to test on other browsers.

## Using the addon

### Robinhood Watchlist Monitor
1. Open a new tab on your web browser
2. Make sure the tamplermonkey scripot **Robinhood Watchlist Monitor** is enabled by clicking on tampermonkey icon on top right corner of your browser
3. On your browser, go to your watchlist page on robinhood
4. Ta-da! You should see extra columns added to your watchlist table
5. Add your limut prices and see them change color as the stock/crypto price hit the limits
    * **Entry**: Will turn **yellow** if current price is at or below the limit price entered in this box 
    * **Price Targets (PT)**: Will turn **green** if current price is at or above the limit price entered in this box 
    * **Entry**: Will turn **red** if current price is at or below the limit price entered in this box

**Note:** This script removes the sidebar from the original watchlist page to create more space for extra columns.

**Note:** The values entered in the limit price boxes are not persisten when page is refereshed.
This feature is a work in progress.

## License

Licensed under [MIT License](./LICENSE).
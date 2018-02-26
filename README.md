# Exchange-Rates-Spread-Sheet

Gets historical exchange rates from the European Central Bank and stores them into a spread sheet.

Uses the [fixer.io](fixer.io) api to retrieve the information.

## Usage

py exchangeRates.py \<start date> <end date\> \<base country> \<countries to compare againgst>

example: "py exchangeRates.py 2015-02-21 2015-11-30 USD GBP EUR"

the above example would get the exchange rates between the U.S. dollar, the Great british Pound, and the Euro form Feb 21, 2015 till Nov 30, 2015

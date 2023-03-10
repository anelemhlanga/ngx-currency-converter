# NgxCurrencyConverter

App enabling a user to select currencies from a list to monitor the exchange rates for these currencies against the USD exchange rate and perform currency conversions with a markup percentage.

## Resource

- [api/currencies.json](https://openexchangerates.org/api/currencies.json)

## Feaures

- A landing screen displaying a list of monitored currencies. The user should be able to add and remove currencies to monitor.
- An add currency screen where a new currency can be selected to monitor.
- A currency conversion screen where the user can convert a specified input amount in USD to a selected currency amount. You can choose to either create a new screen where this is done or display a widget on the landing screen that allows for this conversion.

Landing Screen
• The landing screen should contain a list of currencies, add currency FAB and a navigation option to open the currency converter screen (if the widget is not displayed on the page).
• When selecting an item from the list, the user should be taken to the detail screen for that currency.
• When Clicking on the FAB, the user should be taken to the add currency screen .

Add Currency Screen
• The add currency screen should enable the user to select a currency populated from the results of the https://openexchangerates.org/api/currencies.json API call.
• On save this currency could be persisted either to a database of your choice or stored in memory.

Currency Converter Widget/Screen
• The user should be able to select a currency as well as enter an amount to convert. This conversion is between the selected currency and USD.
• Please apply a markup of 7% to the result.

Bonus Tasks
• Include unit tests for this application.
• Include integration tests for this application.
• Include documentation in your code

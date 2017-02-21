# currencymap-for-accounting.json

Contain all important information for currency. Now you can easily format amount with the accounting.js.

## Source data:## 
https://gist.github.com/Fluidbyte/2973986

I supplemented it with the appropriate format data.


## Accounting.js## 
http://openexchangerates.github.io/accounting.js/
```
// Default usage:
accounting.formatMoney(12345678); // $12,345,678.00

// European formatting (custom symbol and separators), can also use options object as second parameter:
accounting.formatMoney(4999.99, "€", 2, ".", ","); // €4.999,99

// Negative values can be formatted nicely:
accounting.formatMoney(-500000, "£ ", 0); // £ -500,000

// Simple `format` string allows control of symbol position (%v = value, %s = symbol):
accounting.formatMoney(5318008, { symbol: "GBP",  format: "%v %s" }); // 5,318,008.00 GBP
```

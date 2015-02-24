Hosted on AZURE 

http://angularjsstevenfinance.azurewebsites.net/

Exchange rate is from Yahoo Finance API 
'http://query.yahooapis.com/v1/public/yql?q=select * from ' +
          'yahoo.finance.xchange where pair in ("PAIRS")&format=json&' +
          'env=store://datatables.org/alltableswithkeys&callback=JSON_CALLBACK'

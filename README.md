# PrimeXBT Report to Cointracking.info Excel

Helper for importing PrimeXBT trades into Cointracking.info

- open https://mybinder.org/v2/gh/phdd/primexbt-cointracking/HEAD?labpath=primexbt-report.ipynb
  - wait for the process being finished
- go to PrimeXBT
  - go to trading report (Trading History > Trading report)
  - maybe filter your trades
  - click on *Statement*
  - copy the URL from the newly created browser tab
- again in the jupyter notebook
  - click into the first "cell"
  - press *Run All Cells* within the *Run* menu
  - when the input field opens: paste the URL
  - maybe define a *Trading Group* for Cointracking.info with the next input
  - wait for all cells being finished
  - click on the file browser icon (top left corner)
  - right click on *CoinTracking_Excel_Import.xls* and Download
- prepend row to Excel table (as in the original Cointracking.info file)
- go to Cointracking.info [Excel Import](https://cointracking.info/import/import_xls/)
  - upload the file

**Disclaimer**: This code may produce wrong results, thus it's your responsibility to check if everything's right. I do not give any guarantees or warranties!

Nevertheless, I hope it can help you :wink:

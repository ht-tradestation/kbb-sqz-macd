# "KBB (Keltner / Bollinger Band) Squeeze MACD": Chart Analysis, RadarScreen & Alerts

Based on the Keltner Channel / Bollinger Band squeeze, using MACD histogram for trend.
### Chart Analysis
Displays just like a standard MACD but includes the KBB squeeze red/green dots on the centerline. Histogram dynamically colored base on trend direction. Unlike the built-in MACD supplied by TradeStation, this one permits the selection of various moving average types (simple, exponential, weighted, hull).
### RadarScreen
Displays color coded values in two separate columns of the RadarScreen.
KBB column shows whether the KBB is in a squeeze or has fired. If KBB has fired, displays number of consecutive bars since fired.
MACD Hist column shows colors of the histogram trend direction.
### Alerts
Are included for both the Chart Analysis mode as well as the RadarScreen mode. Alerts include:
1. KBB squeeze fired
1. Histogram crossing zero licensed
1. Histogram changing trend direction

## Getting Started

Installation Method #1 (advanced users):

**!!!IT IS HIGHLY RECOMMENDED THAT YOU FOLLOW INSTALL METHOD #2**

Source code is provided in the form of the following a text files:

**Source code for the analysis technique**
```
HT_KBB_Squeeze_MACD.txt
```
**Source code for custom function (required)**
```
HT_MACD.txt
```
Step 1: Open the Development Environment and create a new custom function named `HT_MACD`. Paste the contents of `HT_MACD.txt` into this new custom function. Verify the function before proceeding to step 2.
Step 2:  Create a new custom indicator named `HT-KBB Squeeze MACD`. Paste the contents of `HT_KBB_Squeeze_MACD.txt` into this new indicator.  Click the verify button from the toolbar and check for errors. If no errors then you are ready to add this indicator to your Charts and/or RadarScreen.
If errors prevent the code from verifying, proceed to installation method /#2.

Installation Method #2:
The EasyLangauge file included:
```
HT_KBB_SQUEEZE_MACD.ELD
```
Simply download the EasyLanguage file and save to your hard drive. Go to an open chart and right-click, select 'Insert analysis technique'. Click the 'Import' button located below the list of included analysis techniques. Select 'Using Import/Export Wizard' from the Import menu. Browse to the location you saved the EasyLanguage file and select it. Click next through the rest of the process until complete.

### Prerequisites

Requires you to install the [TradeStation platform](https://www.tradestation.com/) ###Charges May Apply

```
RadarScreen may require a subscription. **Charges May Apply**
```

### Detailed video demo showing installation and settings

[![Demo Video](https://www.hahn-tech.com/wp-content/uploads/2017/10/kbb-sqz-macd-promo-sml.jpg)](https://www.youtube.com/watch?v=https://youtu.be/C8Eaz2cLmKY)

## Contributing

Please read CONTRIBUTING.md for details on our code of conduct, and the process for submitting pull requests to us.

## Versioning

We use [SemVer](http://semver.org/) for versioning. For the versions available, see the [tags on this repository](https://github.com/your/project/tags).

## Authors

* **Pete Hahn** - *Initial work* - [HahnTech](https://github.com/hahntech)

See also the list of [contributors](https://github.com/your/project/contributors) who participated in this project.

## License

This project is licensed under the GNU GPLv3 License - see the [LICENSE.md](LICENSE.md) file for details

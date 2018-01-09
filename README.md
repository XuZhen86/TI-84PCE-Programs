# TI-84PlusCE_TimeDisplay
Presented to you with pride by Xu Zhen.

## Description
1. This program simply displays the current system time with big red fonts and refreshes every seconds. It was implemented in [TI-BASIC](https://en.wikipedia.org/wiki/TI-BASIC) and was tested on TI-84 Plus CE calculator.
2. The program was implemented in such a way that minimizes interference with variables, so it was expected not to change any existing variables. It only creates ```⌊TIME0```, ```⌊TIME1```, ```⌊TIME2``` and ```⌊TIME3``` for temperoral data storage and they can be deleted at any time when the program is not running.

## Requirement
1. This program requires [CE TextLib](https://www.cemetech.net/programs/index.php?mode=file&id=1340) to run.
2. The [Faster](http://www.ticalc.org/pub/84plusce/asm/programs/faster.zip) program is strongly recommended to accelerate the display refresh process.

## Useage
1. Use the [TI Connect™ CE Software](https://education.ti.com/en/products/computer-software/ti-connect-ce-sw) to upload the program from computer to the calculator.
2. Press ```mode``` key and navigate to ```SET CLOCK``` section of the menu to set the system clock.
3. Type in ```prgmTIMEDISP``` on the calculater and press ```enter``` key.
4. You should see the program running and the time should refresh every second.
5. Press ```del``` or arrow keys for 3 seconds to stop the program, a light grey bar on the legt-right angle will show the countdown. You can also force-stop the program by press ```on``` key.

## Files and What Do They Do
```
TI-84PlusCE_TimeDisplay
├── LICENSE             // The license file.
├── README.md           // The file you are looking at.
├── TIMEDISP.8xp        // The upload-able file.
└── TIMEDISP.txt        // The txt version of the source code.
```

## Lisence
This program was distributed under The [GNU General Public License Version 3](https://www.gnu.org/licenses/gpl-3.0.en.html).

## Warranty
Although the program has been tested, it was not guaranteed that it will not change any variable or crash the system and results in a RAM clearance. Always make sure to archive any important data before running this program! The author of this program is not responsible for any data loss of any application of this program! You have been warned, proceed at your own risk.

## Finally
If you enjoyed and/or learned something from this project, please leave a star! I am looking forward to bring more quality projects to GitHub.fit.edu!
```
╺┳╸╻   ┏━┓╻ ╻┏━┓╻  ╻ ╻┏━┓┏━╸┏━╸   ╺┳╸╻┏┳┓┏━╸╺┳┓╻┏━┓┏━┓╻  ┏━┓╻ ╻
 ┃ ┃╺━╸┣━┫┗━┫┣━┛┃  ┃ ┃┗━┓┃  ┣╸     ┃ ┃┃┃┃┣╸  ┃┃┃┗━┓┣━┛┃  ┣━┫┗┳┛
 ╹ ╹   ┗━┛  ╹╹  ┗━╸┗━┛┗━┛┗━╸┗━╸╺━╸ ╹ ╹╹ ╹┗━╸╺┻┛╹┗━┛╹  ┗━╸╹ ╹ ╹

┏┓ ╻ ╻    ╻ ╻╻ ╻   ╺━┓╻ ╻┏━╸┏┓╻
┣┻┓┗┳┛╹   ┏╋┛┃ ┃   ┏━┛┣━┫┣╸ ┃┗┫
┗━┛ ╹ ╹   ╹ ╹┗━┛   ┗━╸╹ ╹┗━╸╹ ╹

╺┳╸╻ ╻┏━┓┏┓╻╻┏    ╻ ╻┏━┓╻ ╻╻
 ┃ ┣━┫┣━┫┃┗┫┣┻┓   ┗┳┛┃ ┃┃ ┃╹
 ╹ ╹ ╹╹ ╹╹ ╹╹ ╹    ╹ ┗━┛┗━┛╹
```

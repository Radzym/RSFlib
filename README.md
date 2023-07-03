# RSFlib
Methods and constants that i found useful at university.

## CalcFunction
Function for statistical analysis and data conversions. 

**cart2pol** - transforms carthesian coordinates to polar
**fit_uncertainty** - returns stdev from, used for curve fitter
**uncertainty** - some base analytics of measurement we used, can return, print and plot results
**GetMinIndex** - returns index/indexes of min value/values(if more), **returns list not just int!!!**
**log_b** - returns log from a of base b

## Constants
Class that consists some physical constants that i used to need

To get some:
```
import RSFlib.Constants as pc
c = pc().light_seed
```

## DataManagement
Data management tasks that i made to easier work with files.

**fileName** - method that takes path as input and returns unique path if input
    path already exist (prevent unique data overwrite)

## TkinterExtension
Some of basic widgets that are not included in base library of tkinter

**progressLoadBar** - Progress bar for loading with one input 
**UpDownButton** - Simple up/down button with displaying of numbers

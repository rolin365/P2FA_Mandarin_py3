# P2FA_Mandarin_py3
Modified Python3 P2FA for Mandarin

## Quick Start:

If you have installed these:  
- [x] Python 3
- [x] Htk 3.4
- [x] SoX (Sound eXchange)

Then you can:
1. Clone this repository
2. Add a `filename.wav` file and its corresponding transcript `filename.txt` file into the `/run` directory.
3. In Terminal, navigate to the `/run` directory:

```
$ python Calign2textgrid.py filename.wav filename.txt filename.Textgrid
```
The output `filename.Textgrid` is the corresponding time-aligned .Textgrid file.

#### A detailed step-by-step guide: https://chenzixu.rbind.io/resources/forcedalignment/

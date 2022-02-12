## NEW Victoria II war analyzer for Divergences of Darkness
I took a couple of hours finagling with the source code of the tried-and-true Victoria 2 war analyzer and got it working with Divergences! No more missing flags or displaying Aragon as Arabia!

How to use:
1. Create a dummy file directory anywhere on your PC of the form "Victoria 2/localisation"
2. Into the localisation folder place the .csv file from your DoD mod that contains the localisation for country names. For HPM-based DoD this file should be "00_HPM_countries.csv"
    - To reiterate, you should have a dummy file of the form "Victoria 2/localisation/00_HPM_countries.csv"
3. Launch vickywaranalyxzer-1.2.1-DOD-jfx.jar in the same fashion as the vanilla war analyzer.
4. Into the installation path, enter instead your dummy Victoria 2 file. Enter your save game as usual.
5. Run the analyzer!

This method can be used to allow the analyzer to properly display any mod, as long as the .jar is recompiled with the flags from the mod and a dummy file is made with that mod's country name localisation.

Original vanilla war analyzer: https://github.com/TKasekamp/VickyWarAnalyzer

### Screenshots
All wars tab:
![alt text](https://previews.dropbox.com/p/thumb/ABfQd3Q3RhEWrabQR1bKHnCNCe05uW98qWAx0SIuwuZOWFtV3v61WAkTOMCPmAON4-UwXdpO84BuRlUGkFtBJVSmv-davCWGQdUVsEs7Pk76qh8fafsrqp4-_I3jBpx-lwYwy24MYlLajFsNqFh3xE6BK66Q7R-e4tJUDcuuERCaQNW0VHcmb7LBa9GMiE-_tNX9uVwvw9RbZBrGbRyR-bVSjZ3RoWJNIMTE7n41FxaSrMHgvGDjBbRHv8VR8EMz0aLblJPkGfFAjGhk4ys4I5swFxD9DnsG-ED8rhtdvuBWUIK1ch_2V9TaKZOXuObNJuj-Z4WGA1oMV7wbgOw6CE80sqMmiWuwdzOYfEyErz4hhg/p.png "Wars tab")
War details tab:
![alt text](https://previews.dropbox.com/p/thumb/ABfa_674OviGJ8MpObk8HpZ0eAj9nJYNYiuG1v5MV6IW_CcReGF9j0niInbOzLoQrX9dxg0zXV8v8BAvDCYLUN7aeGtO7_jjX55mL40ZRKc3FkzxhW6T0Ojs_9Jlai0kzNq1cPjkB6F1LOtqZfoDS7UEy43Fjwiy_YCmndGv-ZrD5f_Y4-F4G9eWbIe_iOwI9wkggsB_avmZXD2T1mSx3aCrRfJkqb0je5H3SxX172OMyd1KlvJbImtwlAsIQ9VbOkW5KJTtumxs0DYllP8DB7AR22yvl7RKOV4ew2aoq35sVTWC82ewQbCF10lY5rebjC1rBcBUWloFSlxU5OFUhxzWBDukna_IULjNj6SAEyYNsQ/p.png "War details tab")
Battle details tab:
![alt text](https://previews.dropbox.com/p/thumb/ABcJAlmx8hpF-g7oek4hsZ6Gni8bnNXKToBXsKcoAN_FtyLIUVWuVGVwsAxy5V-PTQWHuS-ggj6kLGg7HrPzmZ2rMrBO4KFLS7qtrGGQh1uwCA5b1PNDuM47OF3IItLU8EP0TOuXsDP7zQRjQjhJBZEl64H5qYz_uarSOgktAR1wUYM9BF34mK6tBeX7dT-NTwYz6xkbmx077L2PscG_0UyEYwunJBrrEAsuAYBvMgeJGVduFGN5o01yV3Gio5H7GAKNzgcA965_Gc-6o_Qfnwzp7u3IFRmCI3MYDR9COxTBCJEIJycVhBNwweo3dvImeo2MkqtRf0d97IEqcSj4qtOHT4MBwOSS1Wablf1qm3xvFQ/p.png "Battle details tab")
Wargoals tab:
![alt text](https://previews.dropbox.com/p/thumb/ABfRe2Fg4nr6-aMk3ahH-NTXMDMfYBqIjyIO0qpo41zNkl4Sn-Ud_k9qBBwifA98cu4Ls7GpyWC66YQuSysHPV_qYCt01o-WtFBPWBUF5rtOVgGNULLdpuyDZSzceXltT1K52wkeaJSXmX7JyJdzamb6iBEPAgcSx-Lc3gOOEcsAtZ3k2AJhhawg1muZwddgJ20WesBE4aBSefIb2O2mk-L6ICRKh1z-WZzSdiGqu2DwQwu-_d9zCvVR83h4gFZsMbip8betg7M_azk7OmImd4XNBLch4VPMqynKHhLd8nCcrUdH3qK-i7cOaTb5rUggqB7SGq2eH5cv1s06CA4j8jRdzlub84gYj0PRvBF3TD7u8w/p.png "Average AI Dual Monarchy")
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
![alt text](https://i.imgur.com/xdZ2qlQ.png "Wars tab")
War details tab:
![alt text](https://i.imgur.com/LS5G8tg.png "War details tab")
Battle details tab:
![alt text](https://i.imgur.com/IB5xqV6.png "Battle details tab")
Wargoals tab:
![alt text](https://i.imgur.com/bsyYUcc.png "Average AI Dual Monarchy")
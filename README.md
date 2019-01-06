# ArcThemes
Source code for MokshaArc Themes, three flat themes for Moksha

# Arc theme for enlightenment
Based upon the original arc gtk design from [horst3180](https://github.com/horst3180/arc-theme). There are still widgets and e-modules missing. Code originally generated by use [LeBLue's](https://github.com/LeBlue/enlightenment-arc-theme/blob/master/README.md) repo.

![A screenshot of the Arc-Darker theme](https://github.com/LeBlue/enlightenment-arc-theme/blob/master/screenshots/shot.png)

### Why a copy here

I decide to move all our theme source code to BodhiDev. But LeBLues technique to build two themes from one sourc code was problematic for two reasons: 

 * It created code that could not be decomiled with edje_decc. People expect edje_decc to be able to decompile e themes.
 * Štefan's fork of LeBlues enlightenment-arc-theme turned into the MoskhaArcGreen theme and no longer could be used to build the arc and arc dark themes.
 * Separating the source code for the three themes now means each theme can develop independently. As the MoskhaArcGreen theme is the default theme for BL 5.0, features not wanted or desired in the other two ar themes can now be added. 

### Disadvantages of a copy here

 * The main disadvatage is some commits will have to be made for each theme.
 * The other disadvantages is sharing commits back to LeBlue orginal repo.
 
But overall these are minor problems.

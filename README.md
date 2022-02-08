# JOSM Paint Style

![GeneralInterchange2](https://github.com/osmlab/applepaintstyles/blob/images/images/GeneralInterchange2.png)

## Description

This map paint style improves the visibility of the highway network for easier editing of ways and nodes. All supported OSM tags render in this custom base style; no need to stack styles. 

Various elements and tag combinations render for easier editing and visualization, including:
- Highways
- Bridges/Tunnels
- Ref Tags and Route Relations
- POIs
- Street Names
- Place Names
- Pedestrian
- Access tags
- Buildings
- Addresses

Various settings and inline validation errors were added to better identify data errors and inconsistencies:
- Roundabouts
- Buildings
- Oneways
- Geometry

## Installation

There are two ways to install the paint style -- link to the paint style on this repository, or download it to your computer. Linking to it on this repository is preferred, it will ensure that any updates to the paint style will carry over to you in JOSM, but if you are mapping offline or with a slow internet connection, or wish to tweak the paint style, downloading it may be better.

1. To link directly to this repo: click 'Clone or download' then right-click 'Download ZIP' and copy the URL, which is ```https://github.com/osmlab/applepaintstyles/archive/main.zip```
Or to download it to your computer: click 'Clone or download' then click 'Download ZIP' and save the ZIP file somewhere on your computer.

2. Open JOSM preferences and navigate to Map Paint Styles (third icon down, 'Settings for the map projection and data integration' then the second tab over):
  - Click "+" next to 'Active styles'
  - Name the style something you will remember
  - Under 'URL / File' either paste the direct link: ```https://github.com/osmlab/applepaintstyles/archive/main.zip``` or navigate to where you saved the ZIP file on your computer
  - Click 'Ok'

3. Installed! You should now see the paint style qith the name you gave it in the 'Map Paint Styles' window.

## Usage

**Note:** Please see our [wiki](https://github.com/osmlab/applepaintstyles/wiki/JOSM-MapCSS-Paint-Style-Wiki) for more documentation.

By default the 'Hide icons (at low zoom)', 'Areas drawn with partial fill', 'Inline validation checks', 'Sensitive features', and 'Hide tagged waynodes at low zoom' settings are turned on. To enable and disable these and other settings: 
1. Right click on the paint style -> Left click 'Style settings'

2. Select the appropriate setting group:
  - Feature/Label Display Settings contains settings which dictate general map feature display and labeling
  - Tag/Geometry Check Settings contains settings which operate based on specific tag or geometry interactions
  - Alternative Settings contains settings which offer an alternative to the base style

3. Select the appropriate setting(s)
  - See the wiki for more information on settings

4. Remember that having other paint styles active simultaneously may cause unintended display issues. It is recommended that other styles sit below this style in the 'Map Paint Styles' window.

**Originally Based On:**

* [JOSM Default](https://josm.openstreetmap.de/wiki/Styles)
* [Apple Inline Validation](https://github.com/osmlab/appledata/wiki/Inline-Validation-Paint-Style-Information)
# JOSM Paint Style

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

### Local Copy Installation
Use this method for manual updates

1. Copy a zipped version of this repo by clicking 'Clone or download' -> 'Download ZIP'.

2. Open JOSM preferences and navigate to Map Paint Styles (third icon down, second over):
  - "+" under Active styles.
  - Name the style.
  - Add zipped paint-master repo link to 'URL / File'. 
  - Ok.

3. Installed! You should now see the paint style in the 'Map Paint Styles' window.

Note: If you do not download a zipped copy, all icons could be broken! 

### Github Remote URL Installation
Use this method for automatic updates

1. Copy HTTPS link to GitHub by clicking 'Clone or download'
  - Ensure dialog box says "Clone with HTTPS". If not, click 'Use HTTPS'
  - Copy URL

2. Open JOSM preferences and navigate to Map Paint Styles (third icon down, second over):
  - "+" under Active styles.
  - Name the style.
  - Add zipped paint-master repo link to 'URL / File'. 
  - Ok.

3. Installed! You should now see the paint style in the 'Map Paint Styles' window.

## Usage

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

* [JOSM Default] - Core elements (https://josm.openstreetmap.de/wiki/Styles)
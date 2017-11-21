% Dungeon Architect Quick Start Demos
% for Unity

Sample Content
==============
Dungeon Architect comes with sample content to quickly get you started.    It contain free modular assets (Candy) and pre-designed theme files for some of the famous modular assets in the asset store

**Sample content using free assets:**  Already included in DA package under DungeonArchitect_Samples folder

**Sample content using other paid assets in the Asset Store:**  [DOWNLOAD](https://s3-us-west-2.amazonaws.com/coderespawn-public/dungeon_architect/unity/third_party_samples/1.6.0/DungeonArchitect_Samples_Thridparty_v1.6.0.zip)

Candy Theme
===========
Dungeon Architect ships with a set of free modular assets to help you get started.   

![Level generated using the Candy Theme](../assets/images/candy_01.jpg)

Explore the contents under `DungeonArchitect_Samples/Theme_Candy/`

The theme file used to generate the level is located here:

`DungeonArchitect_Samples/Theme_Candy/Themes/CandyDungeonTheme.asset`

![Free Candy Theme](../assets/images/candy_theme.png)


Design Time Generation
----------------------
This scene has a dungeon actor setup with the Candy theme.

Select the DungeonGrid actor and click "Build Dungeon" button.  Change the **Seed** variable in the configuration to get a different layout

Scene Location: `DungeonArchitect_Samples/Theme_Candy/Scenes/DemoScene`

\newpage

Runtime Generation
------------------

This demo shows how you can build a new layout at runtime.  Play the scene and use the following controls

* **Space**: Build a new dungeon layout
* **Right Mouse**: Look Around
* **WASD**: Move the camera


Scene Location: `DungeonArchitect_Samples/Demo_Theme_Candy/Scenes/*`

\newpage

Outdoor Cliff Theme
===================

This demo showcases an outdoor scene using free assets by [Kenny](http://opengameart.org/content/3d-nature-pack) 

The art is licensed under CC0 so it can be used with your commercial games

YOUTUBE(jilMwhXIydA)

Cliffs
------
Scene Location: `DungeonArchitect_Samples/Demo_Theme_OutdoorCliffs/Scenes/Demo_OutdoorCliffs`

![Cliff Theme](../assets/images/cliff_01.jpg)


Alternate Version
-----------------
An alternate version of the theme 
Scene Location: `DungeonArchitect_Samples/Demo_Theme_OutdoorCliffs/Scenes/Demo_OutdoorCliffs_Alternate`

![Cliff Theme](../assets/images/cliff_02.jpg)


\newpage

Simple City Builder Demo
========================
This example shows how you can build your own layout algorithms and swap the existing one out.    A simple city layout is made in a grid based pattern and various theme files are used to decorate it 

Explore the contents under `DungeonArchitect_Samples/DemoBuilder_SimpleCity/`

The Sample Builder code resides under `DungeonArchitect/Scripts/Builder/SimpleCity`

City Theme #1
-------------
Scene Location: `DungeonArchitect_Samples/DemoBuilder_SimpleCity/Scenes/SimpleCityRealtimeScene`

![Simple City Theme 1](../assets/images/simple_city_01.jpg)

City Theme #2
-------------
Scene Location: `DungeonArchitect_Samples/DemoBuilder_SimpleCity/Scenes/SimpleCityScene`

![Simple City Theme 2](../assets/images/simple_city_02.jpg)

Stronghold Theme #1
-------------------
A marker emitter is attached to the builder to extend it by emitting wall markers around the city bounds.   This lets the theme files deocrate the level as a medieval stronghold

Scene Location: `DungeonArchitect_Samples/DemoBuilder_SimpleCity/Scenes/StrongholdBasic`

![Stronghold Theme 1](../assets/images/stronghold_01.jpg)

Stronghold Theme #2
-------------------
An alternative version of the above theme

Scene Location: `DungeonArchitect_Samples/DemoBuilder_SimpleCity/Scenes/StrongholdMedieval`

The art assets is licensed under CC0 and can be used with commercial games

![Stronghold Theme 2](../assets/images/stronghold_02.jpg)



\newpage

MOBA Theme (MK4)
================
A theme created using ManufacturaK4's excellent [Tower Defense and MOBA](https://www.assetstore.unity3d.com/en/#!/content/28234) asset pack

* Import the [Tower Defense and MOBA](https://www.assetstore.unity3d.com/en/#!/content/28234) asset pack into your project before opening the demo scenes
* [Download](#sample-content) the theme files from here and extract it into your project's Asset folder
* Explore the contents under `DungeonArchitect_Samples_Thridparty/Demos/Theme_K4_Moba/`

Summer Mode
-----------

Scene Location: `DungeonArchitect_Samples_Thridparty/Demos/Theme_K4_Moba/Scenes/Demo_MOBA_DA_Summer`

![ManufacturaK4's Moba Scene (Content Not included)](../assets/images/moba_01.jpg)

![ManufacturaK4's Moba Scene (Content Not included)](../assets/images/moba_02.jpg)

![ManufacturaK4's Moba Scene (Content Not included)](../assets/images/moba_03.jpg)

![Theme File Fragment](../assets/images/moba_theme.png)


Winter Mode
-----------
The assets come with winter textures as well (however it doesn't come with winter materials and an easy way to switch between the two).  With DA you can do that easily

Scene Location: `DungeonArchitect_Samples_Thridparty/Demos/Theme_K4_Moba/Scenes/Demo_MOBA_DA_Winter`

After the scene is generated,  a dungeon listener script automatically fires that replaces the summer materials with winter ones.  This script is reusable on your other projects

![ManufacturaK4's Moba Winter Scene (Content Not included)](../assets/images/moba_winter_01.jpg)

![ManufacturaK4's Moba Winter Scene (Content Not included)](../assets/images/moba_winter_02.jpg)


\newpage

Graveyard Theme (ManufacturaK4)
================
A theme created using the city builder and ManufacturaK4's excellent [Top-Down Graveyard](https://www.assetstore.unity3d.com/en/#!/content/25356) asset pack

YOUTUBE(CJLk6VsFxfY)

![Graveyard Scene (Content Not included)](../assets/images/grave1.jpg)

![Graveyard Scene (Content Not included)](../assets/images/grave2.jpg)

* Import the [Top-Down Graveyard](https://www.assetstore.unity3d.com/en/#!/content/25356) asset pack into your project
* [Download](#sample-content) the theme files from here and extract it into your project's Asset folder
* Explore the contents under `DungeonArchitect_Samples_Thridparty/Demos/Theme_K4_Graveyard/`

Desert Theme (ManufacturaK4)
================
A theme created using the city builder and ManufacturaK4's [Top-Down Desert](https://www.assetstore.unity3d.com/en/#!/content/44757) asset pack

YOUTUBE(s15dYrR213M)

![Desert Scene (Content Not included)](../assets/images/desert1.jpg)

![Desert Scene (Content Not included)](../assets/images/desert2.jpg)

* Import the [Top-Down Desert](https://www.assetstore.unity3d.com/en/#!/content/44757) asset pack into your project
* [Download](#sample-content) the theme files from here and extract it into your project's Asset folder
* Explore the contents under `DungeonArchitect_Samples_Thridparty/Demos/Theme_K4_Desert/`


Cartoon Town Theme (ManufacturaK4)
================
A theme created using the city builder and ManufacturaK4's [Cartoon Town and Farm](https://www.assetstore.unity3d.com/en/#!/content/17254) asset pack

YOUTUBE(NlqHnM1KG0g)

![Toon City Scene (Content Not included)](../assets/images/toon_city1.jpg)

* Import the [Cartoon Town and Farm](https://www.assetstore.unity3d.com/en/#!/content/17254) asset pack into your project
* [Download](#sample-content) the theme files from here and extract it into your project's Asset folder
* Explore the contents under `DungeonArchitect_Samples_Thridparty/Demos/Theme_K4_CartoonTown/`


Village Interiors (3DForge)
================
A theme created using 3DForge's awesome [Village Interior Kit](https://www.assetstore.unity3d.com/en/#!/content/17033) asset pack

YOUTUBE(-XEp_8kI-Us)

* Import the [Village Interior Kit](https://www.assetstore.unity3d.com/en/#!/content/17033) asset pack into your project before opening the demo scenes
* [Download](#sample-content) the theme files from here and extract it into your project's Asset folder
* Explore the contents under `DungeonArchitect_Samples_Thridparty/Demos/Theme_3DF_VillageInterior/`


![Village Interior Kit Theme (Content Not included)](../assets/images/village_interior_01.jpg)

![Village Interior Kit Theme (Content Not included)](../assets/images/village_interior_02.jpg)

![Village Interior Kit Theme (Content Not included)](../assets/images/village_interior_03.jpg)

\newpage


Village Exteriors (3DF) and Gaia (Adam)
====================================================
A theme created using 3DForge's awesome [Village Exterior Kit](https://www.assetstore.unity3d.com/en/#!/content/38045) asset pack and placed on a terrain generated using Adam's beautiful [Gaia](https://www.assetstore.unity3d.com/en/#!/content/42618) terrain generator

* Import the [Village Exterior Kit](https://www.assetstore.unity3d.com/en/#!/content/38045) asset pack into your project before opening the demo scenes
* Import [Gaia](https://www.assetstore.unity3d.com/en/#!/content/42618) asset pack into your project before opening the demo scenes
* [Download](#sample-content) the theme files from here and extract it into your project's Asset folder
* Explore the contents under `DungeonArchitect_Samples_Thridparty/Demos/Theme_3DF_VillageExterior_Gaia/`


Simple Village Theme
--------------------

YOUTUBE(Dcbqy_tlIHA)

A village theme created using the default grid builder. The theme file places random houses near the layout of the dungeon, making it look like a small village

Scene Location `DungeonArchitect_Samples_Thridparty/Demos/Theme_3DF_VillageExterior_Gaia/Scenes/SmallVillage`

![Village theme (Content Not included)](../assets/images/gaia_village0.jpg)

![Village theme (Content Not included)](../assets/images/gaia_village1.jpg)

![Village theme (Content Not included)](../assets/images/gaia_village2.jpg)

Farm House Theme
-----------------

A grid dungeon with a house placed inside each room of the dungoen.   This makes the indivial houses connected with pathways

Scene Location `DungeonArchitect_Samples_Thridparty/Demos/Theme_3DF_VillageExterior_Gaia/Scenes/FarmHouse`

![Farmhouse theme (Content Not included)](../assets/images/gaia_farm.jpg)

![Farmhouse theme (Content Not included)](../assets/images/gaia_farm2.jpg)


Stronghold Theme
----------------
YOUTUBE(CoT-e_cX5Rc)

This demo uses the city dungeon builder and a village with walls

Scene Location `DungeonArchitect_Samples_Thridparty/Demos/Theme_3DF_VillageExterior_Gaia/Scenes/StrongholdVillage`

![Stronghold theme (Content Not included)](../assets/images/gaia_sh1.jpg)

![Stronghold theme (Content Not included)](../assets/images/gaia_sh2.jpg)

![Stronghold theme (Content Not included)](../assets/images/gaia_sh3.jpg)



Interiors Theme (MK4)
=====================
A theme created using ManufacturaK4's excellent [Top-Down Interiors](https://www.assetstore.unity3d.com/en/#!/content/18139) asset pack

* Import the [Top-Down Interiors](https://www.assetstore.unity3d.com/en/#!/content/18139) asset pack into your project before opening the demo scenes
* [Download](#sample-content) the theme files from here and extract it into your project's Asset folder
* Explore the contents under `DungeonArchitect_Samples_Thridparty/Demos/Theme_K4_Interiors/`

Wooden Theme
------------
Scene Location: `DungeonArchitect_Samples_Thridparty/Demos/Theme_K4_Interiors/Scenes/01_PalaceWood`

![Wooden Theme (Content Not included)](../assets/images/interior_wood_01.jpg)

![Wooden Theme (Content Not included)](../assets/images/interior_wood_02.jpg)

![Theme File](../assets/images/interior_wood_theme.png)

\newpage

Stone Theme
-----------
Scene Location: `DungeonArchitect_Samples_Thridparty/Demos/Theme_K4_Interiors/Scenes/02_PalaceStone`

![Stone Theme (Content Not included)](../assets/images/interior_stone_01.jpg)

![Theme File](../assets/images/interior_stone_theme.png)

\newpage

Mixed Theme
-----------
Scene Location: `DungeonArchitect_Samples_Thridparty/Demos/Theme_K4_Interiors/Scenes/03_StoneWood_Mixed`

This sample shows how you can mix two different themes using a *Theme Override Volume*

![Multiple Themes (Content Not included)](../assets/images/interior_mixed_01.jpg)

\newpage

TaD Sewer (3DForge)
===================
A theme created using 3DForge's excellent [TaD Sewer Kit](https://www.assetstore.unity3d.com/en/#!/content/12867) asset pack

* Import the [TaD Sewer Kit](https://www.assetstore.unity3d.com/en/#!/content/12867) asset pack into your project before opening the demo scenes
* [Download](#sample-content) the theme files from here and extract it into your project's Asset folder
* Explore the contents under `DungeonArchitect_Samples_Thridparty/Demos/Theme_3DF_TaDSewer/`


![TaD Sewer Scene (Content Not included)](../assets/images/sewer_01.jpg)

![TaD Sewer Scene (Content Not included)](../assets/images/sewer_02.jpg)

![Theme File](../assets/images/sewer_theme.png)

\newpage

MultiStory Dungeon (MS)
======================
A theme created using Mana Stations's excellent [Multistory Dungeons](https://www.assetstore.unity3d.com/en/#!/content/33955) asset pack

* Import the [Multistory Dungeons](https://www.assetstore.unity3d.com/en/#!/content/33955) asset pack into your project before opening the demo scenes
* [Download](#sample-content) the theme files from here and extract it into your project's Asset folder
* Explore the contents under `DungeonArchitect_Samples_Thridparty/Demos/Theme_MS_MultistoryDungeon/`


![Mana Station's MultiStory Dungeons Scene (Content Not included)](../assets/images/ms_01.jpg)

![Mana Station's MultiStory Dungeons Scene (Content Not included)](../assets/images/ms_02.jpg)

![Mana Station's MultiStory Dungeons Scene (Content Not included)](../assets/images/ms_03.jpg)

![Theme file](../assets/images/ms_theme.png)

\newpage

TopDown Dungeon (MK4)
======================
A theme created using ManufacturaK4's excellent [Top-Down Dungeons Mobile](https://www.assetstore.unity3d.com/en/#!/content/8000) asset pack

* Import the [Top-Down Dungeons Mobile](https://www.assetstore.unity3d.com/en/#!/content/8000) asset pack into your project before opening the demo scenes
* [Download](#sample-content) the theme files from here and extract it into your project's Asset folder
* Explore the contents under `DungeonArchitect_Samples_Thridparty/Demos/Theme_K4_TopDownDungeons/`


![ManufacturaK4's Top-Down Dungeons Scene (Content Not included)](../assets/images/tdd_01.jpg)

![ManufacturaK4's Top-Down Dungeons Scene (Content Not included)](../assets/images/tdd_02.jpg)

![Theme file](../assets/images/tdd_theme.png)

Isaac Builder
=============
This sample demos the new Isaac builder that creates levels like the ones found in Binding of Isaac

The awesome art from Daniel was used for the 2D sprites: [2D Hand Painted - Dungeon Tileset](https://www.assetstore.unity3d.com/en/#!/content/42935)

* Download the samples from [here](https://s3-us-west-2.amazonaws.com/coderespawn-public/dungeon_architect/unity/third_party_samples/1.2.0/DemoBuilder_Isaac_HandPaint.zip)
* Import the asset [2D Hand Painted - Dungeon Tileset](https://www.assetstore.unity3d.com/en/#!/content/42935)


Scene File: `DemoIsaac`

![Isaac Builder (Content Not included)](../assets/images/isaac_01.jpg)

![Isaac Builder (Content Not included)](../assets/images/isaac_02.jpg)


There is also a theme for the grid builder

Scene File: `DemoGrid`

![Isaac Builder (Content Not included)](../assets/images/isaac_grid_01.jpg)

![Isaac Builder (Content Not included)](../assets/images/isaac_grid_02.jpg)


Simple Shapes Theme
===================
Another example of a theme generated using simple basic shapes

Explore the contents under `DungeonArchitect_Samples/Theme_SimpleShapes/`

Scene Location: `DungeonArchitect_Samples/Theme_SimpleShapes/Scenes/BasicShapesDemo`

![Simple Shapes Scene](../assets/images/simple_shapes_01.jpg)

![Theme File](../assets/images/simple_shapes_01_theme.png)

\newpage

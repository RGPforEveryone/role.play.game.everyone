---
{"dg-publish":true,"permalink":"/city-of-trade-1/","hide":true,"hideInGraph":true}
---




> [!NOTE|div-m] Parent Region: `INPUT[suggester(optionQuery(#Category/Region)):MyContainer]`

> [!column|no-i no-t]
>> [!info|no-title] Map
>> ```leaflet  
>> id: ZalkorsFerry ### Must be unique with no spaces  
>> image: [[Zelkor's Ferry.png]] ### Link to the map image file. Do not add a ! in front of the image  
>> bounds: [[0,0], [5000, 4025]] ### Size of the map in px Height_y, Width_x. Ignore 0,0  
>> height: 500px ### Size of the leaflet embed in px on your screen  
>> width: 95% ### Size of the leaflet embed in your note  
>> lat: 2500 ### To center the map, make this half of the map height.  
>> long: 2012.5 ### To center the map, make this half of the map width.  
>> minZoom: -3 ### Controls how far away from the map you can zoom out. Hover over the target icon to see the current level.  
>> maxZoom: 1 ### Controls how far towards the map you can zoom in. Hover over the target icon to see the current level.  
>> defaultZoom: -3 ### Sets the default zoom level when the map loads. Hover over the target icon to see the current level.  
>> zoomDelta: 0.5 ### Adjust how much the zoom changes when you zoom in or out.  
>> unit: mi ### The value displayed when measuring so you know what type of unit is being measure.  
>> scale: 0.09328358208955223 ### Real units/px (resolution) of your map  
>> recenter: false  
>> darkmode: false ### marker
>> ```
>
>> [!note|no-title] Town Name
>> ~~~meta-bind
>> INPUT[select(
>> option(1, ℹ️General),
>> option(2, 🏃‍♂️‍➡️NPCs),
>> option(3, 📝GM Notes),
>> option(4, 🐎Travel),
>> class(tabbed)
>> )]
>> ~~~
>>>[!tabbed-box-maxh]
>>> >[!div-m|no-title]
>>> > ![[#General|no-h clean]]
>>>
>>> >[!div-m|no-title]
>>> > ![[#NPCs|no-h clean]]
>>>
>>> > [!div-m|no-title]
>>> > ![[#GM Notes|no-h clean]]
>>> 
>>> > [!div-m|no-title]
>>> > ![[#Travel|no-h clean]]
>>> 

> [!NOTE|no-title]
> ~~~meta-bind
> INPUT[select(
> option(1, 🛒Commerce),
> option(2, 🍎Agriculture),
> option(3, ⚔️Military),
> option(4, 💭Philosophy),
> option(5, ⚙️Industrial),
> option(6, 🏠Nesting),
> option(7, 👑Government),
> class(tabbed)
> )]
> ~~~
> >[!tabbed-box-maxh]
> > >[!div-m|no-title]
> > > ![[#Commerce|no-h clean]]
> >
> > > [!div-m|no-title]
> > > ![[#Agriculture|no-h2 clean]]
> > 
> > > [!div-m|no-title]
> > > ![[#Military|no-h clean]]
> > 
> > > [!div-m|no-title]
> > > ![[#Philosophy|no-h clean]]
> > 
> > > [!div-m|no-title]
> > > ![[#Industrial|no-h clean]]
> > 
> > > [!div-m|no-title]
> > > ![[#Nesting|no-h clean]]
> > 
> > > [!div-m|no-title]
> > > ![[#Government|no-h clean]]

---
# General

Select Settlement: `INPUT[suggester(optionQuery(#Category/Region)):MyContainer]`

Select Category: `INPUT[inlineSelect(option(City +1500), option(Town +200), option(Village +80), option(Hamlet <80), option(Encampment), option(Keep), option(Fortress), option(Stronghold)):MyCategory]`

This is the town description. 

# NPCs

`BUTTON[button_person]` List important NPCs here. 

<pre class="dataview dataview-error">Evaluation Error: TypeError: Cannot read properties of undefined (reading 'file')
    at eval (eval at &lt;anonymous&gt; (plugin:dataview), &lt;anonymous&gt;:2:29)
    at DataviewInlineApi.eval (plugin:dataview:19027:16)
    at evalInContext (plugin:dataview:19028:7)
    at asyncEvalInContext (plugin:dataview:19038:32)
    at DataviewJSRenderer.render (plugin:dataview:19064:19)
    at DataviewJSRenderer.onload (plugin:dataview:18606:14)
    at DataviewJSRenderer.load (app://obsidian.md/app.js:1:1214378)
    at DataviewApi.executeJs (plugin:dataview:19607:18)
    at DataviewCompiler.eval (plugin:digitalgarden:10760:23)
    at Generator.next (&lt;anonymous&gt;)</pre>

# GM Notes

Make notes of what you need to track in the town here. 

# Travel



`VIEW[{Travel Calculator#HoursPerDay}][math]` hrs per day
[[1-DM Toolkit/Travel Calculator\|Travel Calculator]]  / [[Exhaustion\|Exhaustion]] Level: `VIEW[{Travel Calculator#ExhaustionLevel}][math]`

| Destination |  Travel Days  |
| ---|---|
| [[Next Town A\|Next Town A]] | 🕓: `VIEW[round((88* {Travel Calculator#TravelCalc}) / 60 / {Travel Calculator#HoursPerDay}, 1)]`      |
| [[Next Town B \|Next Town B ]] | 🕓: `VIEW[round((88* {Travel Calculator#TravelCalc}) / 60 / {Travel Calculator#HoursPerDay}, 1)]`

# CAMPING 

C - Commerce (Economics and Entertainment) - Shops, Malls, Theatres, Markets, Carnivals, Electronics
A - Agriculture (Resource Production and Collection) - Farms, Mines, Fisheries, Lumber Yards, Oil Rigs, Power Plants
M - Military (Protection and Transportation) - Forts, Bases, Armories, Walls, Seaports, Airports, Spaceports
P - Philosophy (Religion and Education) - Houses of Worship, Schools, Universities, Laboratories, Arboretums
I - Industrial (Resource Utilization and Processing) - Factories, Metalworks, Bakeries, Artisans, Jewelers
N - Nesting (Housing and Civil Engineering) - Residential Areas, Inns/Hotels
G - Government (Legislation and Judicial) - Town Halls, Courthouses, Tourist Stops, Monuments/Landmarks

## Commerce

This is the content

`BUTTON[button_place]` `BUTTON[button_person]` **C - Commerce** (Economics and Entertainment) - Shops, Malls, Theatres, Markets, Carnivals, Electronics

| Place(s) | Type |
| -------- | ---- |

{ .block-language-dataview}



## Agriculture

`BUTTON[button_place]` `BUTTON[button_person]` **A - Agriculture** (Resource Production and Collection) - Farms, Mines, Fisheries, Lumber Yards, Oil Rigs, Power Plants

| Place(s) | Type |
| -------- | ---- |

{ .block-language-dataview}

## Military

`BUTTON[button_place]` `BUTTON[button_person]` **M - Military** (Protection and Transportation) - Forts, Bases, Armories, Walls, Seaports, Airports, Spaceports

| Place(s) | Type |
| -------- | ---- |

{ .block-language-dataview}


## Philosophy

`BUTTON[button_place]` `BUTTON[button_person]` **P - Philosophy** (Religion and Education) - Houses of Worship, Schools, Universities, Laboratories, Arboretums

| Place(s) | Type |
| -------- | ---- |

{ .block-language-dataview}

## Industrial

`BUTTON[button_place]` `BUTTON[button_person]` **I - Industrial** (Resource Utilization and Processing) - Factories, Metalworks, Bakeries, Artisans, Jewelers

| Place(s) | Type |
| -------- | ---- |

{ .block-language-dataview}

## Nesting

`BUTTON[button_place]` `BUTTON[button_person]` **N - Nesting** (Housing and Civil Engineering) - Residential Areas, Bridges, Parks, Inns/Hotels

| Place(s) | Type |
| -------- | ---- |

{ .block-language-dataview}

## Government

`BUTTON[button_place]` `BUTTON[button_person]` **G - Government** (Legislation and Judicial) - Town Halls, Courthouses, Tourist Stops, Monuments/Landmarks

| Place(s) | Type |
| -------- | ---- |

{ .block-language-dataview}



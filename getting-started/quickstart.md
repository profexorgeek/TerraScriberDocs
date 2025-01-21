---
icon: bullseye-arrow
description: A quick overview of how TerraScriber works.
---

# Quickstart

TerraScriber makes it easy to create attractive maps for your virtual or tabletop gaming session! This page summarizes the overall workflow to create a map.

TerraScriber uses a grid-based system for creating maps that works nicely with most grid-based tabletop games. The default content that comes with TerraScriber assumes that a grid square is approximately five feet.

### Create A New Map

You can create a new map on the main title screen. Once created, the new map will automatically be given a filename and saved to disk. Once created, the map will show up in the list of maps and will be available for editing.

### Editing Your Map

TerraScriber divides editing into two main modes: Layers and Items.

Layers define the main "geometry" of your map and are grid based - things like floors, walls, pathways, rooms, and waterways.

Items are decorative map elements and are not grid based - things like tables, chairs, signposts, trees, and virtually anything else can be placed as an Item.

Items always render on top of Layers.

#### Camera Control

Use the mouse wheel to zoom in and out. The current zoom is shown in the bottom left status bar.

Press middle mouse to drag/pan the map.

Holding the space key will also drag/pan the map if you are using a touchpad or do not have a middle click.

#### Editing Layers

Click the Layers button in the menu bar to switch to Layers mode. You can create a new layer using the plus icon below the list of layers. Name your layer and choose the tileset the layer will use.

Layer editing either adds or removes tiles. You can switch between add and remove modes by clicking the green and red buttons next to the Layer panel. Tiles will automatically be drawn based on the tileset used by the selected layer.

Layers can be renamed, have their tileset changed, be repositioned up and down, have their visibility turned off and on, or be deleted using the buttons below the Layer list.

The list of Layers indicates the rendering order. The first Layer in the list will be the topmost rendered Layer.

#### Editing Items

It's recommended to edit Items after you have laid out the main Layers as this is the most common workflow. However, Layers and Items can be edited in any order.

Click on the Items button in the menu bar to switch to Item editing. The plus button next to the Items panel allows you to place new items from the list. The cursor button allows you to select and move items.

* Use the filter textbox to filter the list of items to quickly see just the type of item you want, such as "tree
* Use the `D` key to duplicate the selected item(s). The duplicate will immediately be placed where your cursor is.
* Use the `Z` key to rotate the item in 45 degree increments.
* Use the `X` key to flip items horizontally.
* Press the `Del` key to delete the selected items. This currently cannot be undone.
* Press the arrow keys to nudge the selected item

#### Saving Your Map

Once you create a map, it will automatically be saved constantly as you edit. Drawing Layer tiles, placing, duplicating, or repositioning items, and similar activities trigger a save.

{% hint style="info" %}
At this time, TerraScriber does not have undo functionality. Changing the name of your map in the Map Settings panel will save it to a new filename on disk and is the only way to make big changes safely. This is something we plan to address in a future version release.
{% endhint %}

#### Resizing Your Map

The resizing feature is coming soon and will appear in the Map Settings panel.

#### Exporting Your Map

The exporting feature is coming soon and will appear in the Export panel.

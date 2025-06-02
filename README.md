# Auto-Base-Grid-Drawer-Widget-Grid-Layout-Builder

A simple visual grid editor for defining custom grid layouts for use in your Lua-based Beyond All Reason (BAR) widgets or other game mods.

## 🌐 Links

👉 [Open Grid Builder Page](https://gdevalpha.github.io/Auto-Base-Grid-Drawer-Widget-Grid-Layout-Builder/)

👉 [Widget Git Repo](https://github.com/GDevAlpha/BAR-Base-Drawer-Widget)

## ✨ Features

- 🖱️ Click-based grid editor with visual feedback
- ➕ Add any number of rows and columns
- 🎨 Four layout types:
  - ⬜ Empty
  - ─ Horizontal Line
  - │ Vertical Line
  - ┌ Corner (left edge)
- 💾 Exports to a Lua-compatible format
- 🧩 Designed for easy integration with BAR Lua widgets

## 🚀 How to Use

1. Enter the number of rows and columns.
2. Click "Generate Grid" to create a grid.
3. Click any cell to choose a layout type.
4. Click "Export Grid" to copy the Lua code block.


Widget to preview and draw grid base layout for NuttyB Raptors. 

Repo:
https://github.com/GDevAlpha/BAR-Base-Drawer-Widget

Grid Builder Helper
https://gdevalpha.github.io/Auto-Base-Grid-Drawer-Widget-Grid-Layout-Builder/


Created a simple tool to help create base layouts for the Widget https://discord.com/channels/549281623154229250/1378066188550148156  

https://gdevalpha.github.io/Auto-Base-Grid-Drawer-Widget-Grid-Layout-Builder/


Personal Auto Base Grid Drawer For Nutty B

Widget to preview and draw grid base layout for NuttyB Raptors. 

### Widget Repo:
https://github.com/GDevAlpha/BAR-Base-Drawer-Widget
---

### Grid Builder Builder Tool
The Grid Layout Builder is a simple visual tool to help users design grid layouts for use in the widget.

https://gdevalpha.github.io/Auto-Base-Grid-Drawer-Widget-Grid-Layout-Builder/ 
---

## ❓ FAQ Grid Builder Builder Tool

### 🧩 What do the grid symbols mean?

Each cell in the grid represents a type of line:
- ⬜ = `0` (Empty)
- ─ = `1` (Horizontal line)
- │ = `2` (Vertical line)
- ┌ = `3` (Corner / Horizontal + Vertical line)

---

### ✍️ Can I add or remove rows and columns?

Yes. Just enter the desired number of rows and columns in the input fields, then click **"Generate Grid"**.

---

### 🔁 Can I change the grid layout after generating it?

Yes. Click any cell in the grid. A small popup will appear letting you select the desired line type.

---

### 📤 How do I use the exported grid in my widget?

Click **"Export Grid"**, and copy the generated Lua table. Paste it into your Lua widget as part of a grid layout list:

```lua
local myLayout = {
  { 0, 1, 1 },
  { 2, 3, 0 },
  { 0, 0, 0 },
}

```

Make sure to add your new layout to gridLayouts in the Widget

```lua
local gridLayouts = {myLayout, midLayout, corneLayout}
```


🔄 Can I create multiple layouts?

Yes. Simply export multiple tables and add them into a Lua list:

```lua
local gridLayouts = { layout1, layout2, layout3 }
```

# Toggle Buttons
Allows to quickly toggle areas in viewport or open them in separate windows

| ![](img/screen/toggle_preview.png) |
|---|
| |

## Toggle Button Actions
There are actions that are associated with the toggle button, they could be called from popup menu or by clicking on the button with the usage of keymap sequences.

### Default Action - Click
Depends on button [mode](#mode):

* [Toggle](#toggle-mode)
* [On](#on-mode)
* [Off](#off-mode)
* [Set](#set-mode)

### Open In New Window - Ctrl + Click
Open new window and set area by given area type

### Set - Shift + Ctrl + Click
Set active area type by given area type

| ![](img/screen/toggle_button_hint.png) |
|---|
| Button actions hint |

### Actions Menu
Button actions are available in menu Actions

| ![](img/screen/toggle_button_actions.png) |
|---|
| Actions menu |


## Toggle Button Settings

| ![](img/screen/toggle_settings.png) |
|---|
| |

### Area Type

| ![](img/screen/toggle_button_area_type.png) |
|---|
| |

### Mode
Toggle button works in one of the next available modes

| ![](img/screen/toggle_button_modes.png) |
|---|
| |

#### Toggle Mode
Toggle area with given area type

| ![](img/screen/toggle_mode.gif) |
|---|
| |

!!! note
    If area duplicate is allowed, then new area will be created and this area will be closed

#### On Mode
Open area with given area type

| ![](img/screen/on_mode.gif) |
|---|
| |

#### Off Mode
Close all areas with given area type

| ![](img/screen/off_mode.gif) |
|---|
| |

#### Set Mode
Set type of active area with given area type

| ![](img/screen/set_mode.gif) |
|---|
| |

### Direction
Indicates in which direction new area will be placed

#### Direction within Active Area

- Left
- Top
- Right
- Bottom

| ![](img/screen/area_direction.png) |
|---|
| |

#### Direction within Active Window

- Most Left
- Most Top
- Most Right
- Most Bottom

| ![](img/screen/area_direction_most_left_right.png) |
|---|
| |

| ![](img/screen/area_direction_most_top_bottom.png) |
|---|
| |

#### Size Factor
Size percentage of width or height depending on direction

| ![](img/screen/area_size_factor.png) |
|---|
| |

| ![](img/screen/size_factor_0_5.gif) |
|---|
| |

| ![](img/screen/size_factor_0_25.gif) |
|---|
| |

### Save and Restore Area and Space Properties
When new area is opened by default in Blender it has the default area and space settings. For example: UV Editor will have closed N-Panel and closed Toolbar Panel. Zen Dock addon gives an option to remember last area and space properties

| ![](img/screen/save_and_restore_props.png) |
|---|
| |

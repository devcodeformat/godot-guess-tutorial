# godot-guess-tutorial
Guess the Number Game Tutorial (In Progress)

## Initial Steps
- Download/Install Godot Software (https://godotengine.org/).
- Navigate to 'Documents' folder.
- Create a New Folder named "Godot" in 'Documents'.
- Open Godot Software.
- Click 'New Project' Button.
- Project Name: "guess-game".
- Project Path -> 'Browse' button : 'Documents' folder -> 'Godot' folder -> Create New Folder
- Renderer: 'OpenGL ES 2.0'.

## First Steps (Game Layout)
- Create New Node : Click '+' (top-left corner) or press [+ Other Node] button.
  - Search and Select 'Control' Node.
    - Rename 'Control' Node to "Game".
- Save Scene as "Game.tscn".
- While 'Game' is selected:
  - Navigate to the center of the Godot GUI.
  - Find and Select 'Layout' button. (above viewport)
    - Find and Select 'Full Rect'. (near-bottom of list)
- While 'Game' is selected:
  - Create New Node.
    - 'PanelContainer'.
- Select PanelContainer:
  - Navigate to the center of the Godot GUI.
  - Find and Select 'Layout' button.
    - Find and Select 'Full Rect'.    
- While 'PanelContainer' is selected:
  - Create New Node.
    - Find and Select 'MarginContainer'.
- Select 'MarginContainer':
  - Create New Node.
    - 'VBoxContainer'.
- Select 'VBoxContainer':
  - Rename to "Rows".
- Select 'MarginContainer':
  - Inspector tab (top-right).
    - Control -> Theme Overrides.
      - Constants.
        - Margin Right: 20.
        - Margin Top: 20.
        - Margin Left: 20.
        - Margin Bottom: 20.         

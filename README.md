# godot-guess-tutorial
====================================================
Step 1
====================================================
Godot: (Text-Based) Setting Up Layout

Create New Node -> Control
    -> Rename Control to "Game"
        -> Save scene as "Game"

Select "Game" 
    -> Center Toolbar 
        -> Layout 
            -> Full Rect (Fits/matches entire screen)

Select "Game" 
    -> Create New Node 
        -> PanelContainer (Contains elements within boundary)

Select PanelContainer
    -> Center Toolbar 
        -> Layout 
            -> Full Rect

Select PanelContainer 
    -> Create New Node 
        -> MarginContainer (Sets margin around elements)

Select MarginContainer 
    -> Create New Node 
        -> VboxContainer (Creates vertical columns)

Select VboxContainer 
    -> Rename "Rows"

Select MarginContainer 
    -> Inspector 
        -> Theme Overrides
            -> Constants (20 for all four options)

Select "Rows" 
    -> Create New Node 
        -> PanelContainer

Select PanelContainer (Child of "Game") 
    -> Rename to "Background"

Select "Background" 
    -> Inspector 
        -> Theme Overrides
            -> Styles
                -> Panel: New StyleBoxFlat 
                    -> Color: #141414


Select PanelContainer (Child of "Rows") 
    -> Rename to "GameInfo"

Select "GameInfo" 
    -> Inspector 
        -> Theme Overrides
            -> Styles 
                -> Panel: New StyleBoxFlat 
                    -> Color: #373737

Select "GameInfo" 
    -> Inspector 
        -> Size Flags 
            -> Vertical: Expand

Select "Rows" 
    -> Create New Node 
        -> PanelContainer 
            -> Rename to "InputArea"

Select "InputArea" 
    -> Inspector 
        -> Rect 
            -> Min Size = y:60

Select "InputArea" 
    -> Inspector 
        -> Theme Overrides
            -> Styles 
                -> Panel: New StyleBoxFlat 
                    ->Color: #515151

Select "Rows" 
    -> Inspector 
        -> Theme Overrides
            -> Constants
                -> Seperation: 20
                
====================================================
/Step 1
====================================================

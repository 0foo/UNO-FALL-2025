* Auto-save (optional)
    * On the Edit tab, click the tiny arrow in the lower-right corner of the Manage Edits group.
    * In the Options window, set an Auto-save interval (for example, every 10 minutes or every 10 edits).

* Create feature class.
    1. In the Catalog pane (if it’s not open, go to View → Catalog Pane).
    2. Expand Databases and right-click your default geodatabase (often named after your project, like ProjectName.gdb).
    3. Choose New → Feature Class.
    4. Name it (e.g., MyLines), and when asked for Geometry Type, select Polyline.
    5. Click through the wizard to finish (you can skip field creation for now).
    6. When done, right-click your new feature class → Add To Current  (IF NOT ALREADY ON THE CONTENTS PANE).

* Create lines/poly
    1. Go to the Edit tab → click Create again.
    2. Now you should see your line layer listed in the Create Features pane.
    3. Select it → click the Line construction tool → start drawing.
    4. Double-click to finish, then Save Edits.


* edit the vertices
    1. On the Edit tab, click Modify (in the Features group).
    2. In the Modify Features pane that appears, scroll or search for Vertices.
    3. Path: Edit → Modify → Vertices.
    4. operations:
        * Move a vertex: click and drag it.
        * Add a vertex: hover along the line (a plus sign appears), click to insert.
        * Delete a vertex: right-click it → Delete Vertex.
        * Move the entire line: drag from the center cross symbol (if visible).

* view all vertices in a feature class
    1. Use the Edit → Modify → Edit Vertices tool.
    2. Select your line and you’ll see every vertex as a point you can click and move.


* modify a feature class - FIRST WAY
    1. Right-click the feature class in the Contents pane → Attribute Table.
    2. In the table, click the gray square to the left of the row you want to edit.
    3. Then go back to the Modify pane — it will recognize that row as selected even if it’s off-screen.

* Modify a feature class - SECOND WAY
    1. In the Edit tab -> click select 
        * can also click the drop down for other selection tools
    2. Select the option on the map 
    3. Click modify

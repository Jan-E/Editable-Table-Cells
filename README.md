Editable Table Cells
====================

iOS Project for iPad, demonstrating how to edit UITableViewCells inline.

The way we do this is by adding a custom UITableViewCell to the table view which contains a text field (or text view for multiline scenarios). When the view controller enters editing mode we enable the textfield in the cell that has been tapped to allow editing.

To respond properly to selections the table view is set to allow selections during editing (both in code and in the Storyboard for clarification).

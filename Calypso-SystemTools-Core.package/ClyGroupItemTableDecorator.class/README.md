I delegate decoration of any group item to the group itself:

	groupItem actualObject decorateTableCell: anItemCellMorph of: groupItem
	
The actualObject is a kind ClyGroup. There are method, class and package groups.

If you introduce new kind of group then to activate this decorator you will need to annotate me with new decoration strategy for new context of this new group
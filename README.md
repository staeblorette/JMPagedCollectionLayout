# JMPagedCollectionLayout
A well behaved collection view layout that handles cells smaller than the viewport, pagination and well defined scrolling behaviour.

Features include:
Fitting:
* Adjacent cells peak from the edge
* Cells use the full screen of the viewport
Scrolling:
* Default collection view scrolling
* Paginated scrolling
* Scrolling will always end, so that a cells origin is at the edge of the viewport + horizontal spacing
Layouting:
* Define number of collumns, rows, spacing and we calculate the collectionView size

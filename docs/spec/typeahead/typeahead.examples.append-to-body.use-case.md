16.13: Typeahead Append to body example
=======================================
**Primary Actor**: User

**Scope**: Ngx-bootstrap DEMO / BS version 3&4

**Goal**: Show user Append to body functionality

Main success scenario:
----------------------
1. User opens Typeahead demo page
2. User clicks on Append to body sub-menu
3. User sees typeahead input and typeahead card with "Model:" text
4. When user starts to type a name of a State from "states" array then order of typed symbols and spaces between them is ignored then a drop-down with a list of States matches is shown
5. If there are no matches then the drop-down is hidden. The "Model" is filled with inputted data
6. When there are any matches then a drop-down with a list of States matches is shown.
7. Items in the drop-down are clickable.
8. When user clicks on any item in typeahead drop-down, then typeahead container auto-fills with a selected State

Extensions:
-----------
3a. If there is any data, it could be deleted. While deleting data the drop-down with matches is shown

Variations:
-----------
2*. User scrolls to Append to body sub-menu
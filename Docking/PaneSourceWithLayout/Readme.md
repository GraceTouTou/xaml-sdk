## Save/Load layout with PaneSource
This examples demonstrates how to handle scenarios where the layout of the RadDocking is loaded and there is a PaneSource collection set. In this scenario if the saved layout matches the PaneSource collection no conflicts are found and all is well, but if the bound collection contains more instances of RadPanes, then the saved in the layout XML the additional RadPane instance in the PanesSource collection will be disregarded. This is an expected behavior that needs to be handled.

[//]: <keywords:docking, loaded, collection>
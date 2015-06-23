# leaflet-refresh-issues
## this is to demostrate a bug in leafletjs on phonegap/ionic type of system.

The map works fine until one switching to another state, and open a modal and then close it and go back to the map state.  The map is some how distored. If I change the orientation (landscape/portrait). Everythign will go back to normal again.  

It is a very illusive and took me a really long time to be able to replicate it. Want to put it out in the community to see if any one has any idea on how to fix this.  



How to replicate this bug. 

In menu 
go to Home
open Modal 
close Modal
go to Map in the menu

and you will see that the map is distored on where it refreshes the map tiles. 

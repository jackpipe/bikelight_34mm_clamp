# bikelight_34mm_clamp
A bicycle rear light clamp for 34mm seatposts, as commonly found on folding bikes.

My first Freecad model from scratch.
There are numerous issues with the model, and I certainly found numerous ahem, challenges, using Freecad.

For example the sketches for the thru-hole, countersink, etc appear to have detached from the faces.
All of them have hard-coded positions, rather than being mutually attached to a given point, which doesn't seem possible in Freecad - you can only synch a sketch to a point on the face it is attached to.
Given this, it is not easy to shrink the length of the fastening tab without having to manually reposition all the sketches; the tab is slightly too long IMHO.

The sketch for the grip extrusion and array is a complete replacement from my first completed attempt, since the original got into an "error" state from which I was unable to recover even by deleting the entire content of the sketch.  Indeed attempting to edit any of the sketches seems to put them in an error state of some kind.  The model is higher than neccesary, but it is not possible to shrink it without repositioning all the sketches, and additionally re-adding all the fillets.  It's almost as if fillets hard-code to an edge.  In any case the round of the tab is achieved with a 9mm fillet, and attempting two 9mm fillets on 18mm or less of solid fails.  Etc, etc, etc.

Freecad is certainly a powerful tool, but it is not without it's ideosyncracies and learning confusions for an inept beginner like me.

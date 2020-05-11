# Elena: Elevation-based Navigation
Nabigation systems optimize for the shortest or fastest route. However, they do not consider elevation gain. For example, users may want to maximize the elevation gain if they are looking for an intense workout. Likewise, users may want to minimize the elevation gain if they only care about how easy they can go to the destination.

## Usages
* Start and end location can be assigned by full address, or using draggable marker to move the position on the map.
* To activate elevation mode, choose MAX or MIN and define the tolerance percentile, default percentile is 100. 
	* Elevation mode: If user chooses MAX, the navigation will choose the path with max elevation gain among the path within tolerance. Likewise, choosing MIN will let navigation choose the path with min elevation gain.
	* Tolerance: If tolerance percentile is 150, meaning user can bear with the path distance that up to 150% of the shortest path distsance.

## Demo
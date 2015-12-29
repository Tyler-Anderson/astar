# astar
a* (a star) pathfinding algorithm, uses a binary heap 

this implementation uses a binheap under the hood and is currently set up for square grids but would work on grids with other dimensions if you create a simple new map generation function. 
In addition this pathfinder works perfectly well with webworkers because the initial state is loaded at once and afterwards the changes to the map are all ideally suited to passing many small messages between the webworker(s) and the main thread. 

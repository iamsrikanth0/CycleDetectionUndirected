For Undirected Graphs
When do we say that a graph has a Cycle, when Visited is true and the currect has not yet visited and it is also not a parent vertex. That's all it is
So we need to track Parent, Visted array, Curr and then apply DFS. 
Depth first search just goes on traversing while checking Visited and Parent, this way we will find if there is exists in the graph. 
Simply put, first visit a Vertex, get neighbours, apply conditions now. 

# Automated-Warehouse
 We consider an automated warehouse scenario in which robots deliver products to picking stations to fulfill orders. A warehouse is represented as a rectangular grid, and the robots can move between horizontally or vertically adjacent cells. To fulfill given orders, robots have to carry shelves with the required products to matching picking stations. The robots are flat, can move underneath shelves and pick them up. However, a robot that carries a shelf does not fit under another shelf anymore, so that shelves may need to be moved out of the way first. The overall goal is to fulfill all orders in as little time as possible, where time is counted in steps and each robot may (but does not have to) perform one action per time step. While robots move around, pick up and put down shelves, deliver products or remain idle, there must not be collisions, i.e., no robot may move into or switch its cell with another one from one step to the next. Finally, grid cells can be designated as highways, and no shelves may be put down at such cells.
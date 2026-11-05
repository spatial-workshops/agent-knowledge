# agent-knowledge
simulating spatial agent knowledge

## robot-sim

`robot-sim/index.html` — a single-page three.js simulation of a robot that starts with no
knowledge of a maze-like building, maps walls with a 4 m × 65° vision cone, and searches
for a goal whose location it doesn't know (frontier-based exploration over its own occupancy
map). Once the goal enters its cone it plans a route (A*) to it and stops on arrival. Open the file in a
browser (it loads three.js from jsDelivr).

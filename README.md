# Dispatch-Simulation-Priority-Queue
I used two priority queues based on min-heaps to create a discrete event simulation that models a 911 dispatch for a small police department. Throughout the simulation, various incidents are reported to the police department and police units are automatically dispatched to deal with these events based on their priority.

One priority queue (based on time) is used to keep track of which events will occur next in the simulation, and the other (based on incident priority) is used to instruct the department where to send its next available unit.

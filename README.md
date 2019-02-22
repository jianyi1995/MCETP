# MCETP
Instances for the Multi-Constraint Emergency Transportation Problem

1. VEHICLES_SECTION:
The property of vehicles are given in this section. Each line is of the form
<integer> <integer> <integer> <integer>
The first integer specifies the id of the vehicle, the second the speed of this vehicle,
the third the capacity of this vehicle and the forth the distance limit of this vehicle.
vehicle_id is in ascending order of vehicle load

2. Depots:
The property of depots are given in this section. Each line is of the form
<integer> <integer> <integer> ...
The first integer specifies the id of the depot, the second the total number of vehicles
in this depot and then lists the id of these vehicles in this depot.
id is in ascending order of depot id.

other parts can be seen from the report of the LKH-3, the link is http://akira.ruc.dk/~keld/research/LKH-3/LKH-3_REPORT.pdf

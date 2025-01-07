# ManufacturingSystemWithMachineBreakdowns
Simulation Analysis Manufacturing System with Machine Breakdowns
This project evaluated a manufacturing system with three machines prone to breakdowns, modeled as exponentially distributed events with an average operational time of 8 hours. Two repairmen addressed breakdowns with an average repair time of 2 hours. The objective was to assess the cost-effectiveness of adding up to three extra machines to reduce downtime and ensure production continuity over 800 simulated hours.

Approach and Methods
Simulation Framework The system was modeled using queuing theory, where repairmen prioritized repairs based on a fixed logic, and excess breakdowns were queued until repairmen became available.
Cost Metrics
$50hour for each broken machine.
$10hour for each repairman.
Tools Microsoft Excel was used to simulate breakdowns and repair times based on random numbers generated using exponential distributions.
Findings
Initial System (3 Machines)

Total Cost $20,770
Queue Length 0.4725 (average)
Operational Time 790 hours
System with 4 Machines

Total Cost $27,240
Queue Length 0.6375 (average)
Operational Time 798 hours
System with 5 Machines

Total Cost $38,160
Queue Length 0.905 (average)
Operational Time 798 hours
System with 6 Machines

Total Cost $43,760
Queue Length 1.0 (average)
Operational Time 800 hours
Conclusion and Recommendations
Adding machines improves operational time but leads to significantly higher costs and increased queue lengths per machine.

Optimal Configuration Without revenue data, the recommendation is based on cost-effectiveness. If the increase in cost from 3 to 4 machines is less than the revenue lost due to reduced operational time with 3 machines, the system should opt for 4 machines.
Key Trade-Off Maintaining a balance between operational efficiency and cost per machine is essential for decision-making.

## Simplification for Visualization purposes of the flow-based domain between two borders.

### Next Steps to assess the impact of new planned power lines on the flow based domain:
- Simulate the complete flow based domain
- Simulate multiple days and extract a typical flow based domain for each border
#### Deterministic Approach -> too resource/tool intensive
- Use PyPSA to simulate the European Electricity System including TYNDP planned new infrastructure. #this probably will not work since PyPSA simplifies the network into fictitious nodes, not computing the complete load flow.
- Extract the PTDF matrix and simulate a typical flow based domain of the planned power system
#### Probabilistic Approach
- Define major domain-shaping drivers, such as demand, solar and wind generation etc.
- Create a probability matrix that define the possible scenarios and use it to approximate the flow-based domain

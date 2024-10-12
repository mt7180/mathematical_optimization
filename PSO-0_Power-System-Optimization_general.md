# Power System Optimization

Power system optimization addresses the challenges of the planning and operating electrical power systems, including generation capacity planning, minimizing operational costs and reducing emissions.  

#### Overview of some key optimization models for power system optimization, they differ in complexity and therefore in detail and computational requirements:

- **Basic Capacity Expansion Problem**: fundamental in planning for future system capacity needs, focusing on minimizing investment and operational costs over time.
- **Generation Expansion Planning (GEP)** : Similar to Capacity Expansion but usually considers a broader range of scenarios and longer time horizons, addressing long-term investment decisions.
- **Economic Dispatch (ED)**: core operational model that ensures power generation is allocated optimally among generators to minimize cost.
- **Economic-Emission Dispatch**: variation of economic dispatch that integrates emissions or other environmental concerns into the objective function.
- **Unit Commitment**: Important for scheduling which generators should be online to meet demand in a cost-effective manner, considering startup/shutdown costs and constraints.
- **Security-Constrained Unit Commitment (SCUC)**: extends Unit Commitment to consider contingencies and system security, ensuring that the scheduled generation can meet load requirements even after certain contingencies.
- **Optimal Power Flow (OPF)**: determines the most efficient operating conditions for an electric power system by minimizing costs or losses while incorporating the physical constraints like voltage, thermal limits, etc. See also: AC-OPF / DC-OPF
- **AC Optimal Power Flow (AC-OPF)**: in its natural form, it requires the introduction of complex numbers to formulate voltage constraints. AC-OPF aims for optimizing real and reactive power flows while considering the full nonlinearities of alternating current (AC) power flow equations, such as voltage and phase angle constraints.
- **DC Optimal Power Flow (DC-OPF)**: Special case of those for AC networks, with the difference that all quantities are real. DCOPF problem approximates the ACOPF problem by making additional assumptions to produce linear constraints. While the additional assumptions result in a potential loss of solution accuracy, they make the DCOPF problem much easier to solve. Commonly used for large-scale applications due to its reduced complexity.
- **Security-Constrained Optimal Power Flow (SCOPF)**: extension of OPF that incorporates contingency analysis to ensure the system can remain secure (meet demand) even if certain lines or generators fail. 
- **Distributed Optimal Power Flow (D-OPF)**: Accounts for distributed energy resources (DERs), such as rooftop solar or small-scale storage, and optimizes power flow with these added complexities.
- **Multi-Period Optimal Power Flow (MOPF)**: Extends OPF by optimizing over multiple time periods (e.g., daily, weekly), allowing for better integration of time-varying aspects like demand and renewable generation.
- **Stochastic/Robust Unit Commitment**: Addresses uncertainty in load, renewable generation, or system failures. These models are crucial with the increasing penetration of variable renewable energy sources (like wind and solar).
- **Optimal Transmission Expansion Planning (TEP)**: Focuses on determining the optimal placement and capacity of new transmission lines to minimize overall system costs while ensuring system reliability.
- **Optimal Reactive Power Dispatch (ORPD)**: An extension of OPF that focuses on optimizing reactive power flow to minimize losses and maintain voltage levels within prescribed limits.
- **Hydrothermal Coordination**: Models the joint operation of hydro and thermal power plants, which is important in systems with significant hydro generation.
- **Market-based OPF**: Considers market mechanisms like locational marginal pricing (LMP) for optimal pricing and dispatch decisions.
- **Co-optimization of Energy and Reserves**: Simultaneously optimizes energy and reserve markets, crucial in modern grids where balancing services are becoming increasingly necessary.
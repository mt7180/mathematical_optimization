# Power System Optimization

Power system optimization addresses the challenges of the planning and operating electrical power systems, including generation capacity planning, minimizing operational costs and reducing emissions.  

#### Overview of some key optimization models for power system optimization, they differ in complexity and therefore in detail and computational requirements:
_(blue: LP, green: LP or NLP, depending on specific formulation, rest: NLP)_
- $\color{LightSkyBlue}{\textsf{Basic Capacity Expansion Problem}}$: fundamental in planning for future system capacity needs, focusing on minimizing investment and operational costs over time.
- $\color{Aquamarine}{\textsf{Generation Expansion Planning (GEP)}}$: Similar to Capacity Expansion but usually considers a broader range of scenarios and longer time horizons, addressing long-term investment decisions.
- $\color{LightSkyBlue}{\textsf{Economic Dispatch}}$: core operational model that ensures power generation is allocated optimally among generators to minimize cost.
- $\color{Aquamarine}{\textsf{Economic-Emission Dispatch}}$: variation of economic dispatch that integrates emissions or other environmental concerns into the objective function.
- $\color{Aquamarine}{\textsf{Unit Commitment}}$: Important for scheduling which generators should be online to meet demand in a cost-effective manner, considering startup/shutdown costs and constraints.
- $\color{Aquamarine}{\textsf{Security-Constrained Unit Commitment (SCUC)}}$: extends Unit Commitment to consider contingencies and system security, ensuring that the scheduled generation can meet load requirements even after certain contingencies.
- $\color{LightSkyBlue}{\textsf{Optimal Power Flow (OPF) -> Transport Model}}$: Core for ensuring the economic operation of power systems under various constraints like voltage, thermal limits, etc.
- **AC Optimal Power Flow (AC-OPF)**: optimizing real and reactive power flows while considering the full nonlinearities of alternating current (AC) power flow equations, such as voltage and phase angle constraints.
- $\color{LightSkyBlue}{\textsf{DC-OPF}}$: Linear Approximation of Optimal Power Flow: A linearized, computationally simpler version of AC-OPF, commonly used for large-scale applications due to its reduced complexity.
- **Security-Constrained Optimal Power Flow (SCOPF)**: extension of OPF that incorporates contingency analysis to ensure the system can remain secure (meet demand) even if certain lines or generators fail.
- $\color{Aquamarine}{\textsf{Security-Constrained Unit Commitment (SCUC)}}$: extends Unit Commitment to consider contingencies and system security, ensuring that the scheduled generation can meet load requirements even after certain contingencies.
- **Stochastic/Robust Unit Commitment**: Addresses uncertainty in load, renewable generation, or system failures. These models are crucial with the increasing penetration of variable renewable energy sources (like wind and solar).
- $\color{Aquamarine}{\textsf{Optimal Transmission Expansion Planning (TEP)}}$:Focuses on determining the optimal placement and capacity of new transmission lines to minimize overall system costs while ensuring system reliability.
- $\color{Aquamarine}{\textsf{Multi-Period Optimal Power Flow (MOPF)}}$:Extends OPF by optimizing over multiple time periods (e.g., daily, weekly), allowing for better integration of time-varying aspects like demand and renewable generation.
- **Optimal Reactive Power Dispatch (ORPD)**: An extension of OPF that focuses on optimizing reactive power flow to minimize losses and maintain voltage levels within prescribed limits.
- **Distributed Optimal Power Flow (D-OPF)**:Accounts for distributed energy resources (DERs), such as rooftop solar or small-scale storage, and optimizes power flow with these added complexities.
<br>

#### Advanced

- **Hydrothermal Coordination**: Models the joint operation of hydro and thermal power plants, which is important in systems with significant hydro generation.
- $\color{Aquamarine}{\textsf{Market-based OPF}}$: Considers market mechanisms like locational marginal pricing (LMP) for optimal pricing and dispatch decisions.
- $\color{Aquamarine}{\textsf{Co-optimization of Energy and Reserves}}$: Simultaneously optimizes energy and reserve markets, crucial in modern grids where balancing services are becoming increasingly necessary.

<br>

> **_NOTE_**: In general each **Constrained Optimization Model** consists of
> - an objective function to be minimized or maximized, 
> - decision variables (variables to be adjusted), 
> - and constraints (limitations on the values of the decision variables).  
>  



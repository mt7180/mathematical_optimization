# Power System Optimization

Power system optimization addresses the challenges of the planning and operating electrical power systems, including generation capacity planning, minimizing operational costs and reducing emissions.  

#### Overview of some key optimization models for power system optimization, they differ in complexity and therefore in detail and computational requirements:
_(blue: LP, green: LP or NLP, depending on specific formulation, rest: NLP)_
- <code style="color : LightSkyBlue">**Basic Capacity Expansion Problem**</code>: fundamental in planning for future system capacity needs, focusing on minimizing investment and operational costs over time.
- <code style="color : Aquamarine">**Generation Expansion Planning (GEP)**</code>: Similar to Capacity Expansion but usually considers a broader range of scenarios and longer time horizons, addressing long-term investment decisions.
- <code style="color : LightSkyBlue">**Economic Dispatch**</code>: core operational model that ensures power generation is allocated optimally among generators to minimize cost.
- <code style="color : Aquamarine">**Economic-Emission Dispatch**</code>: variation of economic dispatch that integrates emissions or other environmental concerns into the objective function.
- <code style="color : Aquamarine">**Unit Commitment**</code>: Important for scheduling which generators should be online to meet demand in a cost-effective manner, considering startup/shutdown costs and constraints.
- <code style="color : Aquamarine">**Security-Constrained Unit Commitment (SCUC)**</code>: extends Unit Commitment to consider contingencies and system security, ensuring that the scheduled generation can meet load requirements even after certain contingencies.
- <code style="color : LightSkyBlue">**Optimal Power Flow (OPF) -> Transport Model**</code>: Core for ensuring the economic operation of power systems under various constraints like voltage, thermal limits, etc.
- **AC Optimal Power Flow (AC-OPF)**: optimizing real and reactive power flows while considering the full nonlinearities of alternating current (AC) power flow equations, such as voltage and phase angle constraints.
- <code style="color : LightSkyBlue">**DC-OPF**</code>: Linear Approximation of Optimal Power Flow: A linearized, computationally simpler version of AC-OPF, commonly used for large-scale applications due to its reduced complexity.
- **Security-Constrained Optimal Power Flow (SCOPF)**: extension of OPF that incorporates contingency analysis to ensure the system can remain secure (meet demand) even if certain lines or generators fail.
- <code style="color : Aquamarine">**Security-Constrained Unit Commitment (SCUC)**</code>: extends Unit Commitment to consider contingencies and system security, ensuring that the scheduled generation can meet load requirements even after certain contingencies.
- **Stochastic/Robust Unit Commitment**: Addresses uncertainty in load, renewable generation, or system failures. These models are crucial with the increasing penetration of variable renewable energy sources (like wind and solar).
- <code style="color : Aquamarine">**Optimal Transmission Expansion Planning (TEP)**</code>:Focuses on determining the optimal placement and capacity of new transmission lines to minimize overall system costs while ensuring system reliability.
- <code style="color : Aquamarine">**Multi-Period Optimal Power Flow (MOPF)**</code>:Extends OPF by optimizing over multiple time periods (e.g., daily, weekly), allowing for better integration of time-varying aspects like demand and renewable generation.
- **Optimal Reactive Power Dispatch (ORPD)**: An extension of OPF that focuses on optimizing reactive power flow to minimize losses and maintain voltage levels within prescribed limits.
- **Distributed Optimal Power Flow (D-OPF)**:Accounts for distributed energy resources (DERs), such as rooftop solar or small-scale storage, and optimizes power flow with these added complexities.
<br>

#### Advanced

- **Hydrothermal Coordination**: Models the joint operation of hydro and thermal power plants, which is important in systems with significant hydro generation.
- <code style="color : Aquamarine">**Market-based OPF**</code>: Considers market mechanisms like locational marginal pricing (LMP) for optimal pricing and dispatch decisions.
- <code style="color : Aquamarine">**Co-optimization of Energy and Reserves**</code>: Simultaneously optimizes energy and reserve markets, crucial in modern grids where balancing services are becoming increasingly necessary.

<br>

> **_NOTE_**: In general each **Constrained Optimization Model** consists of
> - an objective function to be minimized or maximized, 
> - decision variables (variables to be adjusted), 
> - and constraints (limitations on the values of the decision variables).  
>  



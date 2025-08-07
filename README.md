## Logistics-Operations

###
A company providing after-sales services for electronic devices is responsible for managing logistics operations related to products returned due to technical defects. To enhance its operations, the company seeks to collaborate with a third-party logistics service provider to design and implement a comprehensive after-sales service network.
This service network consists of three levels: Collection Centers, Repair Centers, and Production Sites.

Customers return defective products to nearby collection centers. If a product is repairable, it is sent to a repair center for inspection and repair. If it is non-repairable, a replacement is sourced from a production site and delivered to the customer via the same collection center. Spare parts required for repairs are also supplied from production sites to repair centers. The logistics service provider offers:1. 20 local warehouses (proposed as collection centers), and 2. 8 distribution centers (candidates for repair centers).

The after-sales service provider decides to use all 20 local warehouses as collection centers to ensure widespread geographic coverage. However, due to the investment and personnel training required to establish repair centers, only a limited number of the 8 distribution centers can be selected for this purpose. Each selected repair center can be equipped with a limited number of repair tools, and each tool has a defined capacity for handling defective products.

A linear programming model is developed to determine the optimal flow of returned products, replacement products, and spare parts, decide the location and capacity of repair centers, allocate repair equipment across the selected centers. The objective is to minimize the total fixed and variable costs of the system, including repair center setup costs and transportation costs across the network. The model was implemented and solved using Python and Lingo, and sensitivity analysis was performed to evaluate the robustness of the solution under changing system parameters.

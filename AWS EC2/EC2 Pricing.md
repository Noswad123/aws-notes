# AWS Free Tier
# Saving Plans
- lower prices
- 1-3year commitment

# On-Demand
- No upfront costs or minimum contracts apply.
- ideal for short-term, irregular workloads that cannot be interrupted.
- The instances run continuously until you stop them
- you pay for only the compute time you use.
- pay for compute capacity by the hour
# Reserved Instances
- pay ahead of time to receive a discount
- Best for predictable usage
- billing discount that is applied to the use of On-Demand Instances in your account
- You can purchase Standard Reserved and Convertible Reserved Instances for a one-year or three-year term, and Scheduled Reserved Instances for a one-year term.
- You can share with other accounts
- Unlike Savings Plans, Reserved Instances do not require you to commit to a consistent amount of compute usage over the duration of the contract.
	- Offerings
		- convertible
			- up to 54% reduced pricing compared to on-demand
			- can change RI
		- scheduled
			- reserve instances for specific time periods
		- Standard
			- up to 75% reduced pricing compared to on-demand
			- cannot change RI Attributes
# Spot Instances
- ideal for workloads with flexible start and end times or that can withstand interruptions.
- leverage unused EC2 computing capacity
- offers you cost savings at up to 90% of On-Demand Instance prices.
- can be terminated by AWS at anytime

# Dedicated Hosts
- physical servers with EC2 instance capacity that is fully dedicated to your use.
- strict server-bound licensing that won't support multi-tenant
# Terminology
- multi-tenant
	- multiple customers running workloads on the same hardware
	- virtual isolation is what separates customers (Apartment)
- Single tenant
	- Dedicated hardware is what separates customers (House)


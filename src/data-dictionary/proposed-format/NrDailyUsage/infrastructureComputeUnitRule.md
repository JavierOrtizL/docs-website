---
name: infrastructureComputeUnitRule
type: attribute
---

Describes the algorithm used to calculate the host size for CU usage.

Values include: agent\_collected\_calculated\_data: Use the host size data collected by the agent from the OS environment. cloud\_provider\_data: Use the host size data from the cloud provider. missing\_data: Some host size data was missing. This could be due to an agent and operating system combination for which CPU and memory sizes are not supported. This will result in the default host size (16) being applied.
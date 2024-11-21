2024-07-22 11:46

Status:

Tags: [[serverless]]

# Azure Functions

Azure Functions is an event-driven, serverless compute option that doesn’t require maintaining virtual machines or containers. If you build an app using VMs or containers, those resources have to be “running” in order for your app to function. With Azure Functions, an event wakes the function, alleviating the need to keep resources provisioned when there are no events.

## Benefits
- Ideal when you're only concerned about the code running your service and not about the underlying platform or infrastructure
- Used when performing work in response to an event (often via a REST request), timer or message from another azure service
- Scale automatically based on demand
- Runs code when it's triggered and automatically deallocates resources when it's finished
- Can be stateless (default) or stateful (durable functions)

# References
Source: https://learn.microsoft.com/en-us/training/modules/describe-azure-compute-networking-services/6-functions
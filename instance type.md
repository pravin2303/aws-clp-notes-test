| Feature          | On-Demand Instances           | Reserved Instances                 | Spot Instances                       | Dedicated Hosts               |
| ---------------- | ----------------------------- | ---------------------------------- | ------------------------------------ | ----------------------------- |
| Cost             | High                          | Lower (discount)                   | Lowest                               | Highest                       |
| Commitment       | None                          | 1 or 3 years                       | None                                 | Long-term                     |
| Payment Model    | Pay per use                   | Pay upfront or partial             | Market-based pricing                 | Dedicated hardware pricing    |
| Interruption     | No                            | No                                 | Yes (can be terminated by AWS)       | No                            |
| Flexibility      | Very high                     | Limited                            | High                                 | Low                           |
| Hardware         | Shared                        | Shared                             | Shared                               | Dedicated physical server     |
| Best Use Case    | Short-term workloads, testing | Long-running predictable workloads | Batch jobs, fault-tolerant workloads | Compliance or licensing needs |
| Example Scenario | Temporary web server          | Production database                | Data processing job                  | Licensed enterprise software  |


|Type|Key Idea|
|---|---|
|On-Demand|Flexible pay-as-you-go|
|Reserved|Long-term discount|
|Spot|Cheapest but interruptible|
|Dedicated|Physical server for one customer|


| RI Type             | Description                                                               | Flexibility | Cost Saving                     | Best Use Case                        |
| ------------------- | ------------------------------------------------------------------------- | ----------- | ------------------------------- | ------------------------------------ |
| **Standard RIs**    | Commit to a specific instance type and region for 1 or 3 years            | Low         | Highest discount                | Stable long-running workloads        |
| **Convertible RIs** | Can change instance family, OS, or tenancy during the term                | High        | Lower than Standard RI          | Workloads that may change            |
| **Scheduled RIs**   | Reserve capacity for a **specific time schedule** (e.g., daily or weekly) | Medium      | Moderate                        | Workloads running at fixed times     |
| **Dedicated RIs**   | Reserved capacity on **dedicated hardware** (single tenant)               | Low         | Discount on dedicated instances | Compliance or licensing requirements |


| Type           | Key Idea                             |
| -------------- | ------------------------------------ |
| Standard RI    | Highest savings, fixed configuration |
| Convertible RI | Can change instance type             |
| Scheduled RI   | Runs at scheduled times              |
| Dedicated RI   | Reserved dedicated hardware          |
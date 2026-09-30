# System Workflow

```text
User
  |
  v
Submit Standard Laptop Request
  |
  v
Flow Designer Trigger
  |
  v
Check Request Conditions
  |
  +---- Condition Not Met ----> Normal / Alternate Handling
  |
  v
Approval Required?
  |
  +---- No --------------------> Fulfilment
  |
  +---- Yes
          |
          v
      Approval
          |
     +----+----+
     |         |
  Approved   Rejected
     |         |
     v         v
 Fulfilment  Update Request
     |
     v
Update Status
     |
     v
Complete Request
```

> Adapt this diagram if your actual ServiceNow flow has different conditions, actions, or approval stages.

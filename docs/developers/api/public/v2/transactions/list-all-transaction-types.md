---
title: "List all transaction types"
---

# List all transaction types

[[toc]]

## Endpoint

```
GET /api/transactions/types
```

## Response

```json
{
    "data": {
        "TRANSFER": 0,
        "SECOND_SIGNATURE": 1,
        "DELEGATE": 2,
        "VOTE": 3,
        "MULTI_SIGNATURE": 4,
        "IPFS": 5,
        "TIMELOCK_TRANSFER": 6,
        "MULTI_PAYMENT": 7,
        "DELEGATE_RESIGNATION": 8
    }
}
```

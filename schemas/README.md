# Schemas

XSD schemas for all Veloconnect modules.

## Structure

| Folder | Module | Versions |
|---|---|---|
| `profile/` | Buyer authentication and server capabilities | 1.1, 1.4, 1.5, 1.6 |
| `catalog/` | Product catalog access | 1.5 |
| `order/` | Order processing | 1.1 |
| `stock/` | Stock availability (B2B, B2C) | 1.4 |
| `sale/` | Sales data exchange (B2B, B2X) | 1.6 |
| `receipt/` | Order confirmation | 1.3 |
| `transaction/` | Core transaction types | 1.0, 1.4, 1.6 |

`veloconnect-1.6.xsd` is the top-level schema referencing all modules.

## Notes

- Modules are independently versioned
- Implementing all modules is not required – adopt what fits your use case
- `transaction` is a shared dependency used across multiple modules

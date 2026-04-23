# Veloconnect – Standard

Open standard for B2B data exchange between bicycle retailers and suppliers.

Veloconnect defines XML-based APIs for order processing, catalog access, 
stock information, and sales data exchange.

Maintained by [DiBike – Digitize Bike Business Group](https://www.veloconnect.de)

---

## Modules

| Module | Schema | Description |
|---|---|---|
| Profile | `schemas/profile/` | Server capabilities and buyer authentication |
| Catalog | `schemas/catalog/` | Product catalog access |
| Order | `schemas/order/` | Order processing |
| Stock | `schemas/stock/` | Stock availability (B2B, B2C) |
| Sale | `schemas/sale/` | Sales data exchange (B2B, B2X) |
| Receipt | `schemas/receipt/` | Order confirmation |
| Transaction | `schemas/transaction/` | Core transaction types |

The file `veloconnect-1.6.xsd` is the top-level schema referencing all modules.

---

## Integration

For request examples and Bruno collection see:  
[github.com/veloconnect/postman](https://github.com/veloconnect/postman)

---

## License

Veloconnect is published under the OASIS UBL License.  
Copyright DiBike Digitize Bike Business Group GmbH & Co. KG

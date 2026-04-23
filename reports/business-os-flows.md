# Business OS End-to-End Flows

Generated at: 2026-04-23T08:18:59.512Z

- Passing scenarios: 11/11
- Total steps: 105
- Aggregate duration: 319 ms

## Scenarios

### Quote to Cash

- ID: `quote-to-cash`
- Status: passed
- Plugins: `crm-core`, `sales-core`, `accounting-core`
- Steps: 12
- Duration: 82 ms
- Plugin summaries:
  - `crm-core`: primary=2, secondary=1, openExceptions=0
  - `sales-core`: primary=2, secondary=1, openExceptions=0
  - `accounting-core`: primary=2, secondary=1, openExceptions=0

### Procure to Pay

- ID: `procure-to-pay`
- Status: passed
- Plugins: `procurement-core`, `inventory-core`, `accounting-core`
- Steps: 9
- Duration: 30 ms
- Plugin summaries:
  - `procurement-core`: primary=2, secondary=1, openExceptions=0
  - `inventory-core`: primary=2, secondary=0, openExceptions=0
  - `accounting-core`: primary=2, secondary=1, openExceptions=0

### Project to Bill

- ID: `project-to-bill`
- Status: passed
- Plugins: `projects-core`, `accounting-core`
- Steps: 8
- Duration: 21 ms
- Plugin summaries:
  - `projects-core`: primary=2, secondary=1, openExceptions=0
  - `accounting-core`: primary=2, secondary=1, openExceptions=0

### Plan to Produce

- ID: `plan-to-produce`
- Status: passed
- Plugins: `manufacturing-core`, `inventory-core`
- Steps: 8
- Duration: 21 ms
- Plugin summaries:
  - `manufacturing-core`: primary=2, secondary=1, openExceptions=0
  - `inventory-core`: primary=2, secondary=0, openExceptions=0

### Service Dispatch to Bill

- ID: `service-dispatch-to-bill`
- Status: passed
- Plugins: `support-service-core`, `field-service-core`, `inventory-core`, `accounting-core`
- Steps: 14
- Duration: 35 ms
- Plugin summaries:
  - `support-service-core`: primary=2, secondary=1, openExceptions=0
  - `field-service-core`: primary=2, secondary=1, openExceptions=0
  - `inventory-core`: primary=2, secondary=0, openExceptions=0
  - `accounting-core`: primary=2, secondary=1, openExceptions=0

### Retail POS Close

- ID: `retail-pos-close`
- Status: passed
- Plugins: `pos-core`, `accounting-core`
- Steps: 8
- Duration: 19 ms
- Plugin summaries:
  - `pos-core`: primary=2, secondary=1, openExceptions=0
  - `accounting-core`: primary=2, secondary=1, openExceptions=0

### Hire to Payroll

- ID: `hire-to-payroll`
- Status: passed
- Plugins: `hr-payroll-core`, `accounting-core`
- Steps: 8
- Duration: 19 ms
- Plugin summaries:
  - `hr-payroll-core`: primary=2, secondary=1, openExceptions=0
  - `accounting-core`: primary=2, secondary=1, openExceptions=0

### Contract to Renewal

- ID: `contract-to-renewal`
- Status: passed
- Plugins: `contracts-core`, `subscriptions-core`, `accounting-core`
- Steps: 14
- Duration: 32 ms
- Plugin summaries:
  - `contracts-core`: primary=2, secondary=1, openExceptions=0
  - `subscriptions-core`: primary=2, secondary=1, openExceptions=0
  - `accounting-core`: primary=3, secondary=1, openExceptions=0

### Portal Self Service

- ID: `portal-self-service`
- Status: passed
- Plugins: `business-portals-core`, `sales-core`, `support-service-core`
- Steps: 7
- Duration: 20 ms
- Plugin summaries:
  - `business-portals-core`: primary=2, secondary=1, openExceptions=0
  - `sales-core`: primary=2, secondary=0, openExceptions=0
  - `support-service-core`: primary=2, secondary=0, openExceptions=0

### Treasury Settlement

- ID: `treasury-settlement`
- Status: passed
- Plugins: `treasury-core`, `accounting-core`
- Steps: 8
- Duration: 19 ms
- Plugin summaries:
  - `treasury-core`: primary=2, secondary=1, openExceptions=0
  - `accounting-core`: primary=2, secondary=1, openExceptions=0

### E-Invoicing Cycle

- ID: `e-invoicing-cycle`
- Status: passed
- Plugins: `e-invoicing-core`, `accounting-core`
- Steps: 9
- Duration: 21 ms
- Plugin summaries:
  - `e-invoicing-core`: primary=2, secondary=1, openExceptions=0
  - `accounting-core`: primary=3, secondary=1, openExceptions=0


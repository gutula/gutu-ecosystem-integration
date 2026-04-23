# Business OS Resilience Flows

Generated at: 2026-04-23T10:50:09.347Z

- Passing plugins: 25/25
- Aggregate duration: 972 ms

## Plugins

### party-relationships-core

- Status: passed
- Duration: 77 ms
- Duplicate create protection: passed
- Revision mismatch protection: passed
- Exception records closed after recovery: 4
- Advance recovery: pending=1, retriedTarget=traceability.links.record, resolved=1
- Reconcile recovery: pending=1, retriedTarget=traceability.reconciliation.queue, resolved=1

### product-catalog-core

- Status: passed
- Duration: 36 ms
- Duplicate create protection: passed
- Revision mismatch protection: passed
- Exception records closed after recovery: 4
- Advance recovery: pending=1, retriedTarget=traceability.links.record, resolved=1
- Reconcile recovery: pending=1, retriedTarget=traceability.reconciliation.queue, resolved=1

### pricing-tax-core

- Status: passed
- Duration: 33 ms
- Duplicate create protection: passed
- Revision mismatch protection: passed
- Exception records closed after recovery: 4
- Advance recovery: pending=1, retriedTarget=traceability.links.record, resolved=1
- Reconcile recovery: pending=1, retriedTarget=traceability.reconciliation.queue, resolved=1

### traceability-core

- Status: passed
- Duration: 35 ms
- Duplicate create protection: passed
- Revision mismatch protection: passed
- Exception records closed after recovery: 4
- Advance recovery: pending=1, retriedTarget=traceability.links.record, resolved=1
- Reconcile recovery: pending=1, retriedTarget=traceability.reconciliation.queue, resolved=1

### accounting-core

- Status: passed
- Duration: 34 ms
- Duplicate create protection: passed
- Revision mismatch protection: passed
- Exception records closed after recovery: 4
- Advance recovery: pending=1, retriedTarget=traceability.links.record, resolved=1
- Reconcile recovery: pending=1, retriedTarget=traceability.reconciliation.queue, resolved=1

### crm-core

- Status: passed
- Duration: 36 ms
- Duplicate create protection: passed
- Revision mismatch protection: passed
- Exception records closed after recovery: 4
- Advance recovery: pending=1, retriedTarget=traceability.links.record, resolved=1
- Reconcile recovery: pending=2, retriedTarget=sales.quotes.create, resolved=2

### sales-core

- Status: passed
- Duration: 36 ms
- Duplicate create protection: passed
- Revision mismatch protection: passed
- Exception records closed after recovery: 4
- Advance recovery: pending=2, retriedTarget=inventory.reservations.allocate, resolved=2
- Reconcile recovery: pending=2, retriedTarget=accounting.billing.post, resolved=2

### procurement-core

- Status: passed
- Duration: 36 ms
- Duplicate create protection: passed
- Revision mismatch protection: passed
- Exception records closed after recovery: 4
- Advance recovery: pending=2, retriedTarget=inventory.receipts.record, resolved=2
- Reconcile recovery: pending=2, retriedTarget=accounting.billing.post, resolved=2

### inventory-core

- Status: passed
- Duration: 33 ms
- Duplicate create protection: passed
- Revision mismatch protection: passed
- Exception records closed after recovery: 4
- Advance recovery: pending=1, retriedTarget=traceability.links.record, resolved=1
- Reconcile recovery: pending=1, retriedTarget=traceability.reconciliation.queue, resolved=1

### projects-core

- Status: passed
- Duration: 34 ms
- Duplicate create protection: passed
- Revision mismatch protection: passed
- Exception records closed after recovery: 4
- Advance recovery: pending=1, retriedTarget=traceability.links.record, resolved=1
- Reconcile recovery: pending=2, retriedTarget=accounting.billing.post, resolved=2

### support-service-core

- Status: passed
- Duration: 34 ms
- Duplicate create protection: passed
- Revision mismatch protection: passed
- Exception records closed after recovery: 4
- Advance recovery: pending=1, retriedTarget=traceability.links.record, resolved=1
- Reconcile recovery: pending=2, retriedTarget=inventory.transfers.request, resolved=2

### pos-core

- Status: passed
- Duration: 33 ms
- Duplicate create protection: passed
- Revision mismatch protection: passed
- Exception records closed after recovery: 4
- Advance recovery: pending=1, retriedTarget=traceability.links.record, resolved=1
- Reconcile recovery: pending=2, retriedTarget=accounting.billing.post, resolved=2

### manufacturing-core

- Status: passed
- Duration: 39 ms
- Duplicate create protection: passed
- Revision mismatch protection: passed
- Exception records closed after recovery: 4
- Advance recovery: pending=2, retriedTarget=inventory.transfers.request, resolved=2
- Reconcile recovery: pending=1, retriedTarget=traceability.reconciliation.queue, resolved=1

### quality-core

- Status: passed
- Duration: 67 ms
- Duplicate create protection: passed
- Revision mismatch protection: passed
- Exception records closed after recovery: 4
- Advance recovery: pending=1, retriedTarget=traceability.links.record, resolved=1
- Reconcile recovery: pending=1, retriedTarget=traceability.reconciliation.queue, resolved=1

### assets-core

- Status: passed
- Duration: 42 ms
- Duplicate create protection: passed
- Revision mismatch protection: passed
- Exception records closed after recovery: 4
- Advance recovery: pending=1, retriedTarget=traceability.links.record, resolved=1
- Reconcile recovery: pending=1, retriedTarget=traceability.reconciliation.queue, resolved=1

### hr-payroll-core

- Status: passed
- Duration: 45 ms
- Duplicate create protection: passed
- Revision mismatch protection: passed
- Exception records closed after recovery: 4
- Advance recovery: pending=1, retriedTarget=traceability.links.record, resolved=1
- Reconcile recovery: pending=2, retriedTarget=accounting.billing.post, resolved=2

### contracts-core

- Status: passed
- Duration: 37 ms
- Duplicate create protection: passed
- Revision mismatch protection: passed
- Exception records closed after recovery: 4
- Advance recovery: pending=1, retriedTarget=traceability.links.record, resolved=1
- Reconcile recovery: pending=2, retriedTarget=accounting.billing.post, resolved=2

### subscriptions-core

- Status: passed
- Duration: 35 ms
- Duplicate create protection: passed
- Revision mismatch protection: passed
- Exception records closed after recovery: 4
- Advance recovery: pending=1, retriedTarget=traceability.links.record, resolved=1
- Reconcile recovery: pending=2, retriedTarget=accounting.billing.post, resolved=2

### business-portals-core

- Status: passed
- Duration: 35 ms
- Duplicate create protection: passed
- Revision mismatch protection: passed
- Exception records closed after recovery: 4
- Advance recovery: pending=2, retriedTarget=sales.quotes.create, resolved=2
- Reconcile recovery: pending=1, retriedTarget=traceability.reconciliation.queue, resolved=1

### field-service-core

- Status: passed
- Duration: 36 ms
- Duplicate create protection: passed
- Revision mismatch protection: passed
- Exception records closed after recovery: 4
- Advance recovery: pending=2, retriedTarget=support.service-orders.dispatch, resolved=2
- Reconcile recovery: pending=2, retriedTarget=accounting.billing.post, resolved=2

### maintenance-cmms-core

- Status: passed
- Duration: 35 ms
- Duplicate create protection: passed
- Revision mismatch protection: passed
- Exception records closed after recovery: 4
- Advance recovery: pending=2, retriedTarget=support.service-orders.dispatch, resolved=2
- Reconcile recovery: pending=1, retriedTarget=traceability.reconciliation.queue, resolved=1

### treasury-core

- Status: passed
- Duration: 34 ms
- Duplicate create protection: passed
- Revision mismatch protection: passed
- Exception records closed after recovery: 4
- Advance recovery: pending=1, retriedTarget=traceability.links.record, resolved=1
- Reconcile recovery: pending=2, retriedTarget=accounting.payments.allocate, resolved=2

### e-invoicing-core

- Status: passed
- Duration: 34 ms
- Duplicate create protection: passed
- Revision mismatch protection: passed
- Exception records closed after recovery: 4
- Advance recovery: pending=1, retriedTarget=traceability.links.record, resolved=1
- Reconcile recovery: pending=2, retriedTarget=accounting.billing.post, resolved=2

### analytics-bi-core

- Status: passed
- Duration: 37 ms
- Duplicate create protection: passed
- Revision mismatch protection: passed
- Exception records closed after recovery: 4
- Advance recovery: pending=1, retriedTarget=traceability.links.record, resolved=1
- Reconcile recovery: pending=1, retriedTarget=traceability.reconciliation.queue, resolved=1

### ai-assist-core

- Status: passed
- Duration: 39 ms
- Duplicate create protection: passed
- Revision mismatch protection: passed
- Exception records closed after recovery: 4
- Advance recovery: pending=1, retriedTarget=traceability.links.record, resolved=1
- Reconcile recovery: pending=3, retriedTarget=crm.handoffs.prepare, resolved=3


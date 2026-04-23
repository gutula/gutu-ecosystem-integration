# Business OS Repo CI Fan-out

Generated at: 2026-04-23T10:23:12.593Z

- Passing targets: 26/26
- Aggregate duration: 111518 ms

## Targets

### gutu-plugin-party-relationships-core

- ID: `party-relationships-core`
- Status: passed
- Directory: `/Users/chinmoybhuyan/Desktop/Personal/Framework/plugins/gutu-plugin-party-relationships-core`
- Duration: 5542 ms
- Exit code: 0

```text

tests/migrations/postgres.test.ts:
(pass) party-relationships-core postgres helpers > creates the business tables and indexes [0.88ms]
(pass) party-relationships-core postgres helpers > rolls the schema back safely [0.01ms]

tests/migrations/sqlite.test.ts:
(pass) party-relationships-core sqlite helpers > creates the business tables and indexes
(pass) party-relationships-core sqlite helpers > rolls the sqlite tables back safely [0.10ms]

tests/unit/package.test.ts:
(pass) plugin manifest > keeps a stable package id and business contract surface [0.39ms]
(pass) domain catalog > keeps ERPNext parity references and operational surfaces visible [0.48ms]

tests/integration/lifecycle.test.ts:
(pass) party-relationships-core lifecycle integration > creates, advances, and reconciles a governed business record [37.29ms]

tests/contracts/ui-surface.test.ts:
(pass) party-relationships-core ui surface > mounts the business control room [0.02ms]

 8 pass
 0 fail
 57 expect() calls
Ran 8 tests across 5 files. [85.00ms]
$ node scripts/docs-check.mjs
```

### gutu-plugin-product-catalog-core

- ID: `product-catalog-core`
- Status: passed
- Directory: `/Users/chinmoybhuyan/Desktop/Personal/Framework/plugins/gutu-plugin-product-catalog-core`
- Duration: 4574 ms
- Exit code: 0

```text

tests/migrations/postgres.test.ts:
(pass) product-catalog-core postgres helpers > creates the business tables and indexes [0.24ms]
(pass) product-catalog-core postgres helpers > rolls the schema back safely [0.07ms]

tests/migrations/sqlite.test.ts:
(pass) product-catalog-core sqlite helpers > creates the business tables and indexes [0.08ms]
(pass) product-catalog-core sqlite helpers > rolls the sqlite tables back safely [0.04ms]

tests/unit/package.test.ts:
(pass) plugin manifest > keeps a stable package id and business contract surface [0.03ms]
(pass) domain catalog > keeps ERPNext parity references and operational surfaces visible [0.04ms]

tests/integration/lifecycle.test.ts:
(pass) product-catalog-core lifecycle integration > creates, advances, and reconciles a governed business record [33.61ms]

tests/contracts/ui-surface.test.ts:
(pass) product-catalog-core ui surface > mounts the business control room

 8 pass
 0 fail
 57 expect() calls
Ran 8 tests across 5 files. [72.00ms]
$ node scripts/docs-check.mjs
```

### gutu-plugin-pricing-tax-core

- ID: `pricing-tax-core`
- Status: passed
- Directory: `/Users/chinmoybhuyan/Desktop/Personal/Framework/plugins/gutu-plugin-pricing-tax-core`
- Duration: 4616 ms
- Exit code: 0

```text

tests/migrations/postgres.test.ts:
(pass) pricing-tax-core postgres helpers > creates the business tables and indexes [0.14ms]
(pass) pricing-tax-core postgres helpers > rolls the schema back safely [0.11ms]

tests/migrations/sqlite.test.ts:
(pass) pricing-tax-core sqlite helpers > creates the business tables and indexes [0.06ms]
(pass) pricing-tax-core sqlite helpers > rolls the sqlite tables back safely [0.04ms]

tests/unit/package.test.ts:
(pass) plugin manifest > keeps a stable package id and business contract surface
(pass) domain catalog > keeps ERPNext parity references and operational surfaces visible [0.09ms]

tests/integration/lifecycle.test.ts:
(pass) pricing-tax-core lifecycle integration > creates, advances, and reconciles a governed business record [33.01ms]

tests/contracts/ui-surface.test.ts:
(pass) pricing-tax-core ui surface > mounts the business control room

 8 pass
 0 fail
 57 expect() calls
Ran 8 tests across 5 files. [70.00ms]
$ node scripts/docs-check.mjs
```

### gutu-plugin-traceability-core

- ID: `traceability-core`
- Status: passed
- Directory: `/Users/chinmoybhuyan/Desktop/Personal/Framework/plugins/gutu-plugin-traceability-core`
- Duration: 4471 ms
- Exit code: 0

```text

tests/migrations/postgres.test.ts:
(pass) traceability-core postgres helpers > creates the business tables and indexes [0.19ms]
(pass) traceability-core postgres helpers > rolls the schema back safely [0.11ms]

tests/migrations/sqlite.test.ts:
(pass) traceability-core sqlite helpers > creates the business tables and indexes [0.08ms]
(pass) traceability-core sqlite helpers > rolls the sqlite tables back safely [0.04ms]

tests/unit/package.test.ts:
(pass) plugin manifest > keeps a stable package id and business contract surface
(pass) domain catalog > keeps ERPNext parity references and operational surfaces visible [0.37ms]

tests/integration/lifecycle.test.ts:
(pass) traceability-core lifecycle integration > creates, advances, and reconciles a governed business record [29.60ms]

tests/contracts/ui-surface.test.ts:
(pass) traceability-core ui surface > mounts the business control room

 8 pass
 0 fail
 57 expect() calls
Ran 8 tests across 5 files. [65.00ms]
$ node scripts/docs-check.mjs
```

### gutu-plugin-accounting-core

- ID: `accounting-core`
- Status: passed
- Directory: `/Users/chinmoybhuyan/Desktop/Personal/Framework/plugins/gutu-plugin-accounting-core`
- Duration: 4459 ms
- Exit code: 0

```text

tests/migrations/postgres.test.ts:
(pass) accounting-core postgres helpers > creates the business tables and indexes
(pass) accounting-core postgres helpers > rolls the schema back safely [0.24ms]

tests/migrations/sqlite.test.ts:
(pass) accounting-core sqlite helpers > creates the business tables and indexes [0.05ms]
(pass) accounting-core sqlite helpers > rolls the sqlite tables back safely [0.04ms]

tests/unit/package.test.ts:
(pass) plugin manifest > keeps a stable package id and business contract surface
(pass) domain catalog > keeps ERPNext parity references and operational surfaces visible [0.40ms]

tests/integration/lifecycle.test.ts:
(pass) accounting-core lifecycle integration > creates, advances, and reconciles a governed business record [31.22ms]

tests/contracts/ui-surface.test.ts:
(pass) accounting-core ui surface > mounts the business control room [0.02ms]

 8 pass
 0 fail
 57 expect() calls
Ran 8 tests across 5 files. [68.00ms]
$ node scripts/docs-check.mjs
```

### gutu-plugin-crm-core

- ID: `crm-core`
- Status: passed
- Directory: `/Users/chinmoybhuyan/Desktop/Personal/Framework/plugins/gutu-plugin-crm-core`
- Duration: 4336 ms
- Exit code: 0

```text

tests/migrations/postgres.test.ts:
(pass) crm-core postgres helpers > creates the business tables and indexes [0.25ms]
(pass) crm-core postgres helpers > rolls the schema back safely [0.05ms]

tests/migrations/sqlite.test.ts:
(pass) crm-core sqlite helpers > creates the business tables and indexes [0.12ms]
(pass) crm-core sqlite helpers > rolls the sqlite tables back safely [0.03ms]

tests/unit/package.test.ts:
(pass) plugin manifest > keeps a stable package id and business contract surface
(pass) domain catalog > keeps ERPNext parity references and operational surfaces visible [0.33ms]

tests/integration/lifecycle.test.ts:
(pass) crm-core lifecycle integration > creates, advances, and reconciles a governed business record [32.70ms]

tests/contracts/ui-surface.test.ts:
(pass) crm-core ui surface > mounts the business control room [0.66ms]

 8 pass
 0 fail
 57 expect() calls
Ran 8 tests across 5 files. [69.00ms]
$ node scripts/docs-check.mjs
```

### gutu-plugin-sales-core

- ID: `sales-core`
- Status: passed
- Directory: `/Users/chinmoybhuyan/Desktop/Personal/Framework/plugins/gutu-plugin-sales-core`
- Duration: 4410 ms
- Exit code: 0

```text

tests/migrations/postgres.test.ts:
(pass) sales-core postgres helpers > creates the business tables and indexes [0.16ms]
(pass) sales-core postgres helpers > rolls the schema back safely [0.06ms]

tests/migrations/sqlite.test.ts:
(pass) sales-core sqlite helpers > creates the business tables and indexes
(pass) sales-core sqlite helpers > rolls the sqlite tables back safely [0.13ms]

tests/unit/package.test.ts:
(pass) plugin manifest > keeps a stable package id and business contract surface
(pass) domain catalog > keeps ERPNext parity references and operational surfaces visible [0.09ms]

tests/integration/lifecycle.test.ts:
(pass) sales-core lifecycle integration > creates, advances, and reconciles a governed business record [35.29ms]

tests/contracts/ui-surface.test.ts:
(pass) sales-core ui surface > mounts the business control room

 8 pass
 0 fail
 57 expect() calls
Ran 8 tests across 5 files. [73.00ms]
$ node scripts/docs-check.mjs
```

### gutu-plugin-procurement-core

- ID: `procurement-core`
- Status: passed
- Directory: `/Users/chinmoybhuyan/Desktop/Personal/Framework/plugins/gutu-plugin-procurement-core`
- Duration: 4380 ms
- Exit code: 0

```text

tests/migrations/postgres.test.ts:
(pass) procurement-core postgres helpers > creates the business tables and indexes
(pass) procurement-core postgres helpers > rolls the schema back safely [0.30ms]

tests/migrations/sqlite.test.ts:
(pass) procurement-core sqlite helpers > creates the business tables and indexes [0.08ms]
(pass) procurement-core sqlite helpers > rolls the sqlite tables back safely [0.07ms]

tests/unit/package.test.ts:
(pass) plugin manifest > keeps a stable package id and business contract surface
(pass) domain catalog > keeps ERPNext parity references and operational surfaces visible [0.30ms]

tests/integration/lifecycle.test.ts:
(pass) procurement-core lifecycle integration > creates, advances, and reconciles a governed business record [36.06ms]

tests/contracts/ui-surface.test.ts:
(pass) procurement-core ui surface > mounts the business control room [0.06ms]

 8 pass
 0 fail
 57 expect() calls
Ran 8 tests across 5 files. [72.00ms]
$ node scripts/docs-check.mjs
```

### gutu-plugin-inventory-core

- ID: `inventory-core`
- Status: passed
- Directory: `/Users/chinmoybhuyan/Desktop/Personal/Framework/plugins/gutu-plugin-inventory-core`
- Duration: 4446 ms
- Exit code: 0

```text

tests/migrations/postgres.test.ts:
(pass) inventory-core postgres helpers > creates the business tables and indexes
(pass) inventory-core postgres helpers > rolls the schema back safely [0.24ms]

tests/migrations/sqlite.test.ts:
(pass) inventory-core sqlite helpers > creates the business tables and indexes
(pass) inventory-core sqlite helpers > rolls the sqlite tables back safely [0.11ms]

tests/unit/package.test.ts:
(pass) plugin manifest > keeps a stable package id and business contract surface [0.08ms]
(pass) domain catalog > keeps ERPNext parity references and operational surfaces visible [0.05ms]

tests/integration/lifecycle.test.ts:
(pass) inventory-core lifecycle integration > creates, advances, and reconciles a governed business record [30.68ms]

tests/contracts/ui-surface.test.ts:
(pass) inventory-core ui surface > mounts the business control room [0.06ms]

 8 pass
 0 fail
 57 expect() calls
Ran 8 tests across 5 files. [68.00ms]
$ node scripts/docs-check.mjs
```

### gutu-plugin-projects-core

- ID: `projects-core`
- Status: passed
- Directory: `/Users/chinmoybhuyan/Desktop/Personal/Framework/plugins/gutu-plugin-projects-core`
- Duration: 4368 ms
- Exit code: 0

```text

tests/migrations/postgres.test.ts:
(pass) projects-core postgres helpers > creates the business tables and indexes
(pass) projects-core postgres helpers > rolls the schema back safely [0.27ms]

tests/migrations/sqlite.test.ts:
(pass) projects-core sqlite helpers > creates the business tables and indexes [0.09ms]
(pass) projects-core sqlite helpers > rolls the sqlite tables back safely [0.06ms]

tests/unit/package.test.ts:
(pass) plugin manifest > keeps a stable package id and business contract surface
(pass) domain catalog > keeps ERPNext parity references and operational surfaces visible [0.04ms]

tests/integration/lifecycle.test.ts:
(pass) projects-core lifecycle integration > creates, advances, and reconciles a governed business record [36.34ms]

tests/contracts/ui-surface.test.ts:
(pass) projects-core ui surface > mounts the business control room

 8 pass
 0 fail
 57 expect() calls
Ran 8 tests across 5 files. [72.00ms]
$ node scripts/docs-check.mjs
```

### gutu-plugin-support-service-core

- ID: `support-service-core`
- Status: passed
- Directory: `/Users/chinmoybhuyan/Desktop/Personal/Framework/plugins/gutu-plugin-support-service-core`
- Duration: 4439 ms
- Exit code: 0

```text

tests/migrations/postgres.test.ts:
(pass) support-service-core postgres helpers > creates the business tables and indexes
(pass) support-service-core postgres helpers > rolls the schema back safely [0.38ms]

tests/migrations/sqlite.test.ts:
(pass) support-service-core sqlite helpers > creates the business tables and indexes
(pass) support-service-core sqlite helpers > rolls the sqlite tables back safely [0.10ms]

tests/unit/package.test.ts:
(pass) plugin manifest > keeps a stable package id and business contract surface [0.08ms]
(pass) domain catalog > keeps ERPNext parity references and operational surfaces visible [0.04ms]

tests/integration/lifecycle.test.ts:
(pass) support-service-core lifecycle integration > creates, advances, and reconciles a governed business record [33.11ms]

tests/contracts/ui-surface.test.ts:
(pass) support-service-core ui surface > mounts the business control room

 8 pass
 0 fail
 57 expect() calls
Ran 8 tests across 5 files. [69.00ms]
$ node scripts/docs-check.mjs
```

### gutu-plugin-pos-core

- ID: `pos-core`
- Status: passed
- Directory: `/Users/chinmoybhuyan/Desktop/Personal/Framework/plugins/gutu-plugin-pos-core`
- Duration: 4391 ms
- Exit code: 0

```text

tests/migrations/postgres.test.ts:
(pass) pos-core postgres helpers > creates the business tables and indexes
(pass) pos-core postgres helpers > rolls the schema back safely [0.21ms]

tests/migrations/sqlite.test.ts:
(pass) pos-core sqlite helpers > creates the business tables and indexes [0.14ms]
(pass) pos-core sqlite helpers > rolls the sqlite tables back safely [0.03ms]

tests/unit/package.test.ts:
(pass) plugin manifest > keeps a stable package id and business contract surface
(pass) domain catalog > keeps ERPNext parity references and operational surfaces visible [0.13ms]

tests/integration/lifecycle.test.ts:
(pass) pos-core lifecycle integration > creates, advances, and reconciles a governed business record [32.56ms]

tests/contracts/ui-surface.test.ts:
(pass) pos-core ui surface > mounts the business control room

 8 pass
 0 fail
 57 expect() calls
Ran 8 tests across 5 files. [67.00ms]
$ node scripts/docs-check.mjs
```

### gutu-plugin-manufacturing-core

- ID: `manufacturing-core`
- Status: passed
- Directory: `/Users/chinmoybhuyan/Desktop/Personal/Framework/plugins/gutu-plugin-manufacturing-core`
- Duration: 4895 ms
- Exit code: 0

```text

tests/migrations/postgres.test.ts:
(pass) manufacturing-core postgres helpers > creates the business tables and indexes
(pass) manufacturing-core postgres helpers > rolls the schema back safely [0.26ms]

tests/migrations/sqlite.test.ts:
(pass) manufacturing-core sqlite helpers > creates the business tables and indexes
(pass) manufacturing-core sqlite helpers > rolls the sqlite tables back safely [0.17ms]

tests/unit/package.test.ts:
(pass) plugin manifest > keeps a stable package id and business contract surface [0.01ms]
(pass) domain catalog > keeps ERPNext parity references and operational surfaces visible [0.07ms]

tests/integration/lifecycle.test.ts:
(pass) manufacturing-core lifecycle integration > creates, advances, and reconciles a governed business record [31.28ms]

tests/contracts/ui-surface.test.ts:
(pass) manufacturing-core ui surface > mounts the business control room [0.02ms]

 8 pass
 0 fail
 57 expect() calls
Ran 8 tests across 5 files. [69.00ms]
$ node scripts/docs-check.mjs
```

### gutu-plugin-quality-core

- ID: `quality-core`
- Status: passed
- Directory: `/Users/chinmoybhuyan/Desktop/Personal/Framework/plugins/gutu-plugin-quality-core`
- Duration: 4421 ms
- Exit code: 0

```text

tests/migrations/postgres.test.ts:
(pass) quality-core postgres helpers > creates the business tables and indexes [0.16ms]
(pass) quality-core postgres helpers > rolls the schema back safely [0.07ms]

tests/migrations/sqlite.test.ts:
(pass) quality-core sqlite helpers > creates the business tables and indexes [0.02ms]
(pass) quality-core sqlite helpers > rolls the sqlite tables back safely [0.03ms]

tests/unit/package.test.ts:
(pass) plugin manifest > keeps a stable package id and business contract surface
(pass) domain catalog > keeps ERPNext parity references and operational surfaces visible [0.10ms]

tests/integration/lifecycle.test.ts:
(pass) quality-core lifecycle integration > creates, advances, and reconciles a governed business record [31.54ms]

tests/contracts/ui-surface.test.ts:
(pass) quality-core ui surface > mounts the business control room

 8 pass
 0 fail
 57 expect() calls
Ran 8 tests across 5 files. [66.00ms]
$ node scripts/docs-check.mjs
```

### gutu-plugin-assets-core

- ID: `assets-core`
- Status: passed
- Directory: `/Users/chinmoybhuyan/Desktop/Personal/Framework/plugins/gutu-plugin-assets-core`
- Duration: 4392 ms
- Exit code: 0

```text

tests/migrations/postgres.test.ts:
(pass) assets-core postgres helpers > creates the business tables and indexes
(pass) assets-core postgres helpers > rolls the schema back safely [0.53ms]

tests/migrations/sqlite.test.ts:
(pass) assets-core sqlite helpers > creates the business tables and indexes
(pass) assets-core sqlite helpers > rolls the sqlite tables back safely [0.11ms]

tests/unit/package.test.ts:
(pass) plugin manifest > keeps a stable package id and business contract surface
(pass) domain catalog > keeps ERPNext parity references and operational surfaces visible [0.06ms]

tests/integration/lifecycle.test.ts:
(pass) assets-core lifecycle integration > creates, advances, and reconciles a governed business record [31.53ms]

tests/contracts/ui-surface.test.ts:
(pass) assets-core ui surface > mounts the business control room

 8 pass
 0 fail
 57 expect() calls
Ran 8 tests across 5 files. [66.00ms]
$ node scripts/docs-check.mjs
```

### gutu-plugin-hr-payroll-core

- ID: `hr-payroll-core`
- Status: passed
- Directory: `/Users/chinmoybhuyan/Desktop/Personal/Framework/plugins/gutu-plugin-hr-payroll-core`
- Duration: 4345 ms
- Exit code: 0

```text

tests/migrations/postgres.test.ts:
(pass) hr-payroll-core postgres helpers > creates the business tables and indexes [0.41ms]
(pass) hr-payroll-core postgres helpers > rolls the schema back safely [0.12ms]

tests/migrations/sqlite.test.ts:
(pass) hr-payroll-core sqlite helpers > creates the business tables and indexes [0.17ms]
(pass) hr-payroll-core sqlite helpers > rolls the sqlite tables back safely [0.04ms]

tests/unit/package.test.ts:
(pass) plugin manifest > keeps a stable package id and business contract surface
(pass) domain catalog > keeps ERPNext parity references and operational surfaces visible [0.11ms]

tests/integration/lifecycle.test.ts:
(pass) hr-payroll-core lifecycle integration > creates, advances, and reconciles a governed business record [34.19ms]

tests/contracts/ui-surface.test.ts:
(pass) hr-payroll-core ui surface > mounts the business control room

 8 pass
 0 fail
 57 expect() calls
Ran 8 tests across 5 files. [70.00ms]
$ node scripts/docs-check.mjs
```

### gutu-plugin-contracts-core

- ID: `contracts-core`
- Status: passed
- Directory: `/Users/chinmoybhuyan/Desktop/Personal/Framework/plugins/gutu-plugin-contracts-core`
- Duration: 4324 ms
- Exit code: 0

```text

tests/migrations/postgres.test.ts:
(pass) contracts-core postgres helpers > creates the business tables and indexes [0.20ms]
(pass) contracts-core postgres helpers > rolls the schema back safely [0.13ms]

tests/migrations/sqlite.test.ts:
(pass) contracts-core sqlite helpers > creates the business tables and indexes [0.10ms]
(pass) contracts-core sqlite helpers > rolls the sqlite tables back safely [0.05ms]

tests/unit/package.test.ts:
(pass) plugin manifest > keeps a stable package id and business contract surface [0.96ms]
(pass) domain catalog > keeps ERPNext parity references and operational surfaces visible [0.14ms]

tests/integration/lifecycle.test.ts:
(pass) contracts-core lifecycle integration > creates, advances, and reconciles a governed business record [32.99ms]

tests/contracts/ui-surface.test.ts:
(pass) contracts-core ui surface > mounts the business control room

 8 pass
 0 fail
 57 expect() calls
Ran 8 tests across 5 files. [69.00ms]
$ node scripts/docs-check.mjs
```

### gutu-plugin-subscriptions-core

- ID: `subscriptions-core`
- Status: passed
- Directory: `/Users/chinmoybhuyan/Desktop/Personal/Framework/plugins/gutu-plugin-subscriptions-core`
- Duration: 4347 ms
- Exit code: 0

```text

tests/migrations/postgres.test.ts:
(pass) subscriptions-core postgres helpers > creates the business tables and indexes [0.14ms]
(pass) subscriptions-core postgres helpers > rolls the schema back safely [0.17ms]

tests/migrations/sqlite.test.ts:
(pass) subscriptions-core sqlite helpers > creates the business tables and indexes [0.12ms]
(pass) subscriptions-core sqlite helpers > rolls the sqlite tables back safely [0.03ms]

tests/unit/package.test.ts:
(pass) plugin manifest > keeps a stable package id and business contract surface [0.11ms]
(pass) domain catalog > keeps ERPNext parity references and operational surfaces visible [0.09ms]

tests/integration/lifecycle.test.ts:
(pass) subscriptions-core lifecycle integration > creates, advances, and reconciles a governed business record [33.44ms]

tests/contracts/ui-surface.test.ts:
(pass) subscriptions-core ui surface > mounts the business control room

 8 pass
 0 fail
 57 expect() calls
Ran 8 tests across 5 files. [69.00ms]
$ node scripts/docs-check.mjs
```

### gutu-plugin-business-portals-core

- ID: `business-portals-core`
- Status: passed
- Directory: `/Users/chinmoybhuyan/Desktop/Personal/Framework/plugins/gutu-plugin-business-portals-core`
- Duration: 4383 ms
- Exit code: 0

```text

tests/migrations/postgres.test.ts:
(pass) business-portals-core postgres helpers > creates the business tables and indexes [0.14ms]
(pass) business-portals-core postgres helpers > rolls the schema back safely [0.05ms]

tests/migrations/sqlite.test.ts:
(pass) business-portals-core sqlite helpers > creates the business tables and indexes
(pass) business-portals-core sqlite helpers > rolls the sqlite tables back safely [0.16ms]

tests/unit/package.test.ts:
(pass) plugin manifest > keeps a stable package id and business contract surface
(pass) domain catalog > keeps ERPNext parity references and operational surfaces visible [0.41ms]

tests/integration/lifecycle.test.ts:
(pass) business-portals-core lifecycle integration > creates, advances, and reconciles a governed business record [30.56ms]

tests/contracts/ui-surface.test.ts:
(pass) business-portals-core ui surface > mounts the business control room

 8 pass
 0 fail
 57 expect() calls
Ran 8 tests across 5 files. [66.00ms]
$ node scripts/docs-check.mjs
```

### gutu-plugin-field-service-core

- ID: `field-service-core`
- Status: passed
- Directory: `/Users/chinmoybhuyan/Desktop/Personal/Framework/plugins/gutu-plugin-field-service-core`
- Duration: 4328 ms
- Exit code: 0

```text

tests/migrations/postgres.test.ts:
(pass) field-service-core postgres helpers > creates the business tables and indexes [0.17ms]
(pass) field-service-core postgres helpers > rolls the schema back safely [0.05ms]

tests/migrations/sqlite.test.ts:
(pass) field-service-core sqlite helpers > creates the business tables and indexes [0.06ms]
(pass) field-service-core sqlite helpers > rolls the sqlite tables back safely [0.07ms]

tests/unit/package.test.ts:
(pass) plugin manifest > keeps a stable package id and business contract surface [0.87ms]
(pass) domain catalog > keeps ERPNext parity references and operational surfaces visible [0.13ms]

tests/integration/lifecycle.test.ts:
(pass) field-service-core lifecycle integration > creates, advances, and reconciles a governed business record [33.50ms]

tests/contracts/ui-surface.test.ts:
(pass) field-service-core ui surface > mounts the business control room

 8 pass
 0 fail
 57 expect() calls
Ran 8 tests across 5 files. [69.00ms]
$ node scripts/docs-check.mjs
```

### gutu-plugin-maintenance-cmms-core

- ID: `maintenance-cmms-core`
- Status: passed
- Directory: `/Users/chinmoybhuyan/Desktop/Personal/Framework/plugins/gutu-plugin-maintenance-cmms-core`
- Duration: 4331 ms
- Exit code: 0

```text

tests/migrations/postgres.test.ts:
(pass) maintenance-cmms-core postgres helpers > creates the business tables and indexes [0.13ms]
(pass) maintenance-cmms-core postgres helpers > rolls the schema back safely [0.05ms]

tests/migrations/sqlite.test.ts:
(pass) maintenance-cmms-core sqlite helpers > creates the business tables and indexes [0.08ms]
(pass) maintenance-cmms-core sqlite helpers > rolls the sqlite tables back safely [0.05ms]

tests/unit/package.test.ts:
(pass) plugin manifest > keeps a stable package id and business contract surface [0.08ms]
(pass) domain catalog > keeps ERPNext parity references and operational surfaces visible [0.05ms]

tests/integration/lifecycle.test.ts:
(pass) maintenance-cmms-core lifecycle integration > creates, advances, and reconciles a governed business record [32.48ms]

tests/contracts/ui-surface.test.ts:
(pass) maintenance-cmms-core ui surface > mounts the business control room

 8 pass
 0 fail
 57 expect() calls
Ran 8 tests across 5 files. [69.00ms]
$ node scripts/docs-check.mjs
```

### gutu-plugin-treasury-core

- ID: `treasury-core`
- Status: passed
- Directory: `/Users/chinmoybhuyan/Desktop/Personal/Framework/plugins/gutu-plugin-treasury-core`
- Duration: 4068 ms
- Exit code: 0

```text

tests/migrations/postgres.test.ts:
(pass) treasury-core postgres helpers > creates the business tables and indexes [0.05ms]
(pass) treasury-core postgres helpers > rolls the schema back safely [0.17ms]

tests/migrations/sqlite.test.ts:
(pass) treasury-core sqlite helpers > creates the business tables and indexes
(pass) treasury-core sqlite helpers > rolls the sqlite tables back safely [0.22ms]

tests/unit/package.test.ts:
(pass) plugin manifest > keeps a stable package id and business contract surface
(pass) domain catalog > keeps ERPNext parity references and operational surfaces visible [0.04ms]

tests/integration/lifecycle.test.ts:
(pass) treasury-core lifecycle integration > creates, advances, and reconciles a governed business record [28.72ms]

tests/contracts/ui-surface.test.ts:
(pass) treasury-core ui surface > mounts the business control room

 8 pass
 0 fail
 57 expect() calls
Ran 8 tests across 5 files. [61.00ms]
$ node scripts/docs-check.mjs
```

### gutu-plugin-e-invoicing-core

- ID: `e-invoicing-core`
- Status: passed
- Directory: `/Users/chinmoybhuyan/Desktop/Personal/Framework/plugins/gutu-plugin-e-invoicing-core`
- Duration: 4020 ms
- Exit code: 0

```text

tests/migrations/postgres.test.ts:
(pass) e-invoicing-core postgres helpers > creates the business tables and indexes [0.15ms]
(pass) e-invoicing-core postgres helpers > rolls the schema back safely [0.04ms]

tests/migrations/sqlite.test.ts:
(pass) e-invoicing-core sqlite helpers > creates the business tables and indexes [0.12ms]
(pass) e-invoicing-core sqlite helpers > rolls the sqlite tables back safely [0.02ms]

tests/unit/package.test.ts:
(pass) plugin manifest > keeps a stable package id and business contract surface [0.08ms]
(pass) domain catalog > keeps ERPNext parity references and operational surfaces visible [0.07ms]

tests/integration/lifecycle.test.ts:
(pass) e-invoicing-core lifecycle integration > creates, advances, and reconciles a governed business record [33.64ms]

tests/contracts/ui-surface.test.ts:
(pass) e-invoicing-core ui surface > mounts the business control room

 8 pass
 0 fail
 57 expect() calls
Ran 8 tests across 5 files. [80.00ms]
$ node scripts/docs-check.mjs
```

### gutu-plugin-analytics-bi-core

- ID: `analytics-bi-core`
- Status: passed
- Directory: `/Users/chinmoybhuyan/Desktop/Personal/Framework/plugins/gutu-plugin-analytics-bi-core`
- Duration: 4570 ms
- Exit code: 0

```text

tests/migrations/postgres.test.ts:
(pass) analytics-bi-core postgres helpers > creates the business tables and indexes
(pass) analytics-bi-core postgres helpers > rolls the schema back safely [0.41ms]

tests/migrations/sqlite.test.ts:
(pass) analytics-bi-core sqlite helpers > creates the business tables and indexes
(pass) analytics-bi-core sqlite helpers > rolls the sqlite tables back safely [0.17ms]

tests/unit/package.test.ts:
(pass) plugin manifest > keeps a stable package id and business contract surface [0.04ms]
(pass) domain catalog > keeps ERPNext parity references and operational surfaces visible [0.05ms]

tests/integration/lifecycle.test.ts:
(pass) analytics-bi-core lifecycle integration > creates, advances, and reconciles a governed business record [38.25ms]

tests/contracts/ui-surface.test.ts:
(pass) analytics-bi-core ui surface > mounts the business control room

 8 pass
 0 fail
 57 expect() calls
Ran 8 tests across 5 files. [79.00ms]
$ node scripts/docs-check.mjs
```

### gutu-plugin-ai-assist-core

- ID: `ai-assist-core`
- Status: passed
- Directory: `/Users/chinmoybhuyan/Desktop/Personal/Framework/plugins/gutu-plugin-ai-assist-core`
- Duration: 4609 ms
- Exit code: 0

```text

tests/migrations/postgres.test.ts:
(pass) ai-assist-core postgres helpers > creates the business tables and indexes
(pass) ai-assist-core postgres helpers > rolls the schema back safely [0.43ms]

tests/migrations/sqlite.test.ts:
(pass) ai-assist-core sqlite helpers > creates the business tables and indexes
(pass) ai-assist-core sqlite helpers > rolls the sqlite tables back safely [0.15ms]

tests/unit/package.test.ts:
(pass) plugin manifest > keeps a stable package id and business contract surface
(pass) domain catalog > keeps ERPNext parity references and operational surfaces visible

tests/integration/lifecycle.test.ts:
(pass) ai-assist-core lifecycle integration > creates, advances, and reconciles a governed business record [72.68ms]

tests/contracts/ui-surface.test.ts:
(pass) ai-assist-core ui surface > mounts the business control room

 8 pass
 0 fail
 57 expect() calls
Ran 8 tests across 5 files. [109.00ms]
$ node scripts/docs-check.mjs
```

### gutu-business-packs

- ID: `business-pack-catalog`
- Status: passed
- Directory: `/Users/chinmoybhuyan/Desktop/Personal/Framework/catalogs/gutu-business-packs`
- Duration: 50 ms
- Exit code: 0

```text
Business pack catalog validation passed.

$ bun run validate
$ node scripts/validate-pack-catalog.mjs
```


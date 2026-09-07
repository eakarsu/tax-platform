# Feature status — Tax preparation, compliance & recovery

| Capability | Status |
| --- | --- |
| Native sidebar and canonical feature registry | Built; 391 pages |
| Shared records, validation, relationships, persistence | Implemented in shared runtime |
| Clickable table rows with centered details popup | Implemented; Edit, Delete, Cancel, keyboard access and mobile layout |
| Domain field forms and source traceability | Imported from static source definitions; historical routes are labeled in mapping |
| CSV exports, attachments, audit and report totals | Implemented |
| At least 15 fictional rows per editable feature | Seeded by startup; measured in reports/seed-verification.json |
| AI question-and-answer workspace | Replaces AI feature tables; questions, context fields, formatted answers, follow-ups and saved history; live provider configuration required |
| Source calculation adapters | Available for explicitly registered calculation variants only |
| Source business-rule and state-machine parity | Incomplete beyond registered adapters and native records; verify each source journey |
| Original account/business data migration | Not performed; source data preserved |
| Provider integrations and external delivery | Not connected; request preparation only |
| Hosted authentication, independent-review roles and tenant isolation | Not migrated; local single-user boundary |

A successful build or populated table is not evidence of full source workflow parity. The source-to-feature map records every extracted definition and route, with explicit exclusions and migration warnings. Test/build reports distinguish checked behavior from remaining work.

| Canonical feature | Native mode | Source entries | Calculators | Status |
| --- | --- | ---: | ---: | --- |
| Clients & customers | records | 0 | 0 | Native records/view |
| Work items & projects | records | 1 | 0 | Native records/view |
| Contacts & parties | records | 0 | 0 | Native records/view |
| Tasks | records | 0 | 0 | Native records/view |
| Calendar | records | 0 | 0 | Native records/view |
| Deadlines & reminders | records | 0 | 0 | Native records/view |
| Notes | records | 0 | 0 | AI question-and-answer workspace; records available as context |
| Documents | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Templates | records | 0 | 0 | AI question-and-answer workspace; records available as context |
| Invoices & billing | records | 0 | 0 | Native records/view |
| Time tracking | records | 0 | 0 | Native records/view |
| Messages & communications | records | 0 | 0 | Native records/view |
| Reports & analytics | report | 25 | 0 | Native records/view |
| Activity & audit trail | audit | 25 | 0 | Native records/view |
| Provider connections | integration | 4 | 0 | Provider request records only |
| Producer permit registry | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Product formula registry | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Production lot tracking | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Taxpaid removal ingestion | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Bonded transfer control | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Export shipment matching | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Proof-of-export evidence | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Destruction loss evidence | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Rate and credit calculation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Claim eligibility | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Statute deadline monitoring | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Drawback claim preparation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Agency query workflow | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Refund reconciliation | records | 2 | 0 | AI question-and-answer workspace; records available as context |
| Product market analytics | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Store developer agreement library | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Application SKU registry | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Transaction ingestion | records | 2 | 0 | AI question-and-answer workspace; records available as context |
| Subscription ingestion | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Store commission calculation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Small-business rate validation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Subscription rate transition | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| In-app purchase reconciliation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Refund chargeback audit | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Territory tax treatment | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Withholding calculation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Currency conversion | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Store statement matching | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Missing payout detection | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| App territory analytics | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Asset register ingestion | records | 2 | 0 | AI question-and-answer workspace; records available as context |
| Location situs validation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Ghost asset detection | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Disposed asset removal | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Asset class mapping | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Depreciation schedule application | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Functional obsolescence | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Economic obsolescence | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Exemption qualification | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Rendition preparation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Assessment reconciliation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Appeal opportunity scoring | records | 2 | 0 | AI question-and-answer workspace; records available as context |
| Evidence packet generation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Refund tracking | records | 5 | 0 | AI question-and-answer workspace; records available as context |
| Jurisdiction asset analytics | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Entity VAT profile | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Supplier invoice ingestion | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Invoice validity checks | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Country eligibility rules | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Expense category classification | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Business purpose evidence | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Partial deductibility calculation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Domestic registration exclusion | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Original document control | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Minimum claim threshold | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Filing deadline monitoring | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Portal claim preparation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Tax authority query workflow | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Country category analytics | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Jurisdiction incentive library | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Production entity registry | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Budget cost ingestion | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Payroll residency validation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Vendor location validation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Qualified spend classification | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Related-party control | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Financing source treatment | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Minimum spend threshold | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Credit rebate calculation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Audit sample workbench | records | 2 | 0 | AI question-and-answer workspace; records available as context |
| Application package | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Certificate tracking | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Credit transfer monetization | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Production jurisdiction analytics | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Invoice project mapping | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Asset classification | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Placed-in-service validation | records | 2 | 0 | AI question-and-answer workspace; records available as context |
| Tax life method assignment | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Bonus depreciation calculation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Section 179 analysis | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Cost segregation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Repair versus capital determination | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Partial disposition analysis | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Retirement disposal tracking | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Book-to-tax reconciliation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Tax schedule generation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Amended return support | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Tax benefit analytics | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Entity jurisdiction registry | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Vehicle equipment master | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Fuel-card ingestion | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Bulk fuel receipt ingestion | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Asset assignment | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Telematics matching | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Engine-hour matching | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Tax-paid gallon calculation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Eligible use classification | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Federal refund calculation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| State refund calculation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Evidence package | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Form preparation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Fleet jurisdiction analytics | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Employer location registry | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Employee wage ingestion | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Eligibility population matching | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Certification deadline control | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Qualified wage calculation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Credit interaction rules | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Federal credit calculation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| State credit calculation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Payroll deposit reconciliation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Form amendment preparation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Supporting document package | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Tax notice workflow | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| General-ledger reconciliation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Program location analytics | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Entity and jurisdiction registry | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Payroll register ingestion | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Return and deposit reconciliation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Agency notice intake | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Notice deadline control | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| SUTA rate validation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Experience-rating calculation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Benefit charge audit | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Wage-base and rate validation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Multi-state allocation review | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Penalty and interest recalculation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Agency response package | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Amended return and refund claim | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Agency case and credit tracking | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Tax exposure and outcome analytics | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Plan provision library | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Participant service history | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Compensation averaging | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Benefit formula calculation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Election option validation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Beneficiary entitlement | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Life-status monitoring | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| COLA calculation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Social Security offset | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Workers compensation offset | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Payroll payment reconciliation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Overpayment detection | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Recoupment plan workflow | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Member appeal evidence | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Plan liability analytics | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Parcel & Property Registry | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Assessment Notice Ingestion | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Jurisdiction & Filing Calendar | records | 2 | 0 | AI question-and-answer workspace; records available as context |
| Assessment Anomaly Detection | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Comparable-Sales Selection | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Comparable Adjustment Workbench | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Income-Approach Valuation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Cost-Approach Valuation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Business & Intangible Value Separation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Economic Obsolescence Analysis | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Appeal Application Preparation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Evidence Exchange Management | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Negotiation & Hearing Workbench | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Decision & Refund Tracking | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Portfolio Savings Analytics | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Expenses & Payroll | records | 2 | 0 | Native records/view |
| Engineering Evidence | records | 1 | 0 | Native records/view |
| Credits & Filings | records | 2 | 0 | Native records/view |
| Tax Year | records | 1 | 0 | Native records/view |
| Research Project | records | 1 | 0 | Native records/view |
| Qualified Expense | records | 1 | 0 | Native records/view |
| Git Evidence | records | 1 | 0 | Native records/view |
| Ticket Evidence | records | 1 | 0 | Native records/view |
| Experiment | records | 1 | 0 | Native records/view |
| Contractor Cost | records | 1 | 0 | Native records/view |
| Wage Allocation | records | 1 | 0 | Native records/view |
| Section 174A Cost | records | 1 | 0 | Native records/view |
| Credit Calculation | records | 1 | 0 | Native records/view |
| Tax Document | records | 1 | 0 | Native records/view |
| Audit Defense Item | records | 1 | 0 | Native records/view |
| Four-Part Test Qualifier | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Expense Qualification Mapper | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Credit & 174A Estimator | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Plan document rules | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Participant vesting ingestion | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Termination event control | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Forfeiture recognition | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Restoration obligation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Forfeiture account ledger | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Permitted use validation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Contribution offset calculation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Plan expense payment review | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Participant reallocation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Year-end deadline monitoring | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Operational failure detection | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Correction calculation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Audit evidence package | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Plan forfeiture analytics | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Customer Legal-Entity Registry | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Certificate Collection Portal | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Certificate Classification & Extraction | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Jurisdiction Rules Engine | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Exemption-Reason Validation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Product & Usage Eligibility | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Certificate-to-Transaction Coverage | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Unsupported Exemption Detection | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Transaction Exposure Calculation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Automated Customer Outreach | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Expiration & Renewal Management | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| ERP Order Controls | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Audit-Defense Package | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Override Governance | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Exposure & Compliance Analytics | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Tax code normalization | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Product service classification | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Use location determination | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Jurisdiction rate validation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Exemption mapping | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Manufacturing exemption | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Resale exemption | records | 2 | 0 | AI question-and-answer workspace; records available as context |
| Duplicate accrual detection | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Vendor tax error detection | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Refund statute monitoring | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Sample projection control | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Claim evidence package | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Refund cash tracking | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Entity jurisdiction analytics | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Building project registry | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Ownership eligibility | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Government allocation control | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Construction cost ingestion | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Lighting system evidence | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| HVAC system evidence | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Envelope system evidence | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Energy model validation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Reference standard mapping | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Efficiency threshold calculation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Deduction calculation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Certification evidence | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Return workpaper generation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Building tax analytics | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Entity filing-group registry | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| State rule library | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Revenue sourcing | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Payroll factor calculation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Property factor calculation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Market-based sourcing | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Throwback throwout rules | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Combined reporting control | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| NOL vintage ledger | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Limitation expiration calculation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Credit inventory | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Provision return reconciliation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Amended return opportunity | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| State entity analytics | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Carrier invoice ingestion | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Service product classification | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Service address validation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Jurisdiction mapping | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Federal USF calculation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| State USF calculation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| 911 surcharge validation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Gross receipts tax review | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Utility user tax review | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Internet access exemption | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Overcharge calculation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Carrier refund request | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Tax authority claim workflow | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Service jurisdiction analytics | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Property Source Ingestion | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Property-Type Classification | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Owner & Address Normalization | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Jurisdiction Priority Determination | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Effective-Dated Dormancy Rules | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Activity & Owner-Contact Analysis | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Exemption & Deduction Review | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Due-Diligence Campaign Management | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Owner Response & Claim Resolution | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| NAUPA Report Generation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Remittance Reconciliation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Audit-Defense Workpapers | records | 2 | 0 | AI question-and-answer workspace; records available as context |
| Historical Exposure Estimation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| M&A Successor-Liability Management | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Voluntary Disclosure Management | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Investor beneficial owner registry | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Custodian account mapping | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Security income event ingestion | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Treaty rate library | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Statutory treaty calculation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Relief-at-source validation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Excess withholding detection | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Tax residency evidence | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Power-of-attorney control | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Market filing deadlines | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Custodian submission workflow | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Tax authority queries | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Currency reconciliation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Country custodian analytics | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Transactions | records | 2 | 0 | Native records/view |
| Portfolio Tracker | records | 2 | 0 | AI question-and-answer workspace; records available as context |
| Tax Reports | records | 2 | 0 | Native records/view |
| Tax Loss Harvesting | records | 1 | 0 | Native records/view |
| Mining & Staking | records | 1 | 0 | Native records/view |
| DeFi Activities | records | 2 | 0 | AI question-and-answer workspace; records available as context |
| NFT Transactions | records | 2 | 0 | Native records/view |
| Cross-Border Tax | records | 1 | 0 | Native records/view |
| Compliance Checks | records | 2 | 0 | Native records/view |
| CF: TaxOptimizationEngine | records | 1 | 0 | Native records/view |
| CF: PredictiveTaxLiabilityFo | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| CF: DefiTaxAutomation | records | 1 | 0 | Native records/view |
| CF: RegulatoryScenarioModeli | records | 1 | 0 | Native records/view |
| CF: MultiJurisdictionTaxOpti | records | 1 | 0 | Native records/view |
| Gap: MissingAnalyzeCryptoTaxS | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Gap: LimitedExchangeApiIntegr | integration | 1 | 0 | Provider request records only |
| Gap: NoRealTimePriceFeedInteg | integration | 1 | 0 | Provider request records only |
| Gap: NoCpaAccountantReviewWor | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Gap: NoWalletPrivateKeySecuri | records | 1 | 0 | Native records/view |
| Gap: NoWebhooks | integration | 1 | 0 | Provider request records only |
| Gap: NoSearchAcrossTransactio | records | 1 | 0 | Native records/view |
| Tax Bracket Forecaster | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Donation Optimizer | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| International Tax Mapper | records | 1 | 0 | Native records/view |
| Earned Income Split Analyzer | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Staking Reward Automator | records | 1 | 0 | Native records/view |
| Carbon Offset Tax Credit Finder | records | 1 | 0 | Native records/view |
| Roth Conversion Simulator | records | 1 | 0 | Native records/view |
| Auto-Categorize Transactions | records | 1 | 0 | Native records/view |
| DeFi Tax Implications | records | 1 | 0 | Native records/view |
| AI Tax Planning | records | 2 | 0 | AI question-and-answer workspace; records available as context |
| Cost Basis Optimizer | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Wash Sale Analyzer | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Portfolio Tax Risk | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Regulatory Updates | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Full Tax Summary | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Wash sale exposure | records | 1 | 0 | Native records/view |
| Tax Interview | records | 1 | 0 | Native records/view |
| AI Assistant | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Income | records | 1 | 0 | Native records/view |
| Self-Employment | records | 1 | 0 | Native records/view |
| Deductions | records | 1 | 0 | Native records/view |
| Dependents | records | 1 | 0 | Native records/view |
| Scan Documents | records | 1 | 0 | Native records/view |
| Find Deductions | records | 1 | 0 | Native records/view |
| Audit Risk Scorer | records | 1 | 0 | Native records/view |
| Receipt Scanner | records | 1 | 0 | Native records/view |
| Estimated Taxes | records | 1 | 0 | Native records/view |
| Tax Calculator | records | 1 | 0 | Native records/view |
| State Returns | records | 1 | 0 | Native records/view |
| State Tax Optimizer | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| K-1 Intake Review | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Estimated Payments (AI) | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| YoY Anomaly Detector | records | 1 | 0 | Native records/view |
| Filing Scenarios | records | 1 | 0 | Native records/view |
| AI Advice | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Tax Forms | records | 1 | 0 | Native records/view |
| E-File | records | 1 | 0 | Native records/view |
| PDF Export | records | 1 | 0 | Native records/view |
| Backlog tools | records | 1 | 0 | Native records/view |
| tax optimization scenarios mfj vs mfs hoh with | records | 1 | 0 | Native records/view |
| estimated tax planning with quarterly payment recommendations | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| multi state tax planning for state specific deductions and credits | records | 1 | 0 | Native records/view |
| document auto categorization via receipt ocr ml | records | 1 | 0 | Native records/view |
| engagement letter e sign with scope fees | records | 1 | 0 | Native records/view |
| irs notice cp 1099 letter auto response drafter | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| state local tax optimization ai | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| estimated payment planning ai | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| automated audit risk early warning monitor | records | 1 | 0 | Native records/view |
| e filing integration efin irs mef | integration | 1 | 0 | Provider request records only |
| limited cpa coordination beyond engagement letters | records | 1 | 0 | Native records/view |
| tax plan comparison standard vs itemized visualizations | records | 1 | 0 | Native records/view |
| year over year comparison and anomaly detection | records | 1 | 0 | Native records/view |
| webhooks notifications system | integration | 1 | 0 | Provider request records only |
| audit log subsystem | records | 1 | 0 | Native records/view |
| limited integrations module exists but not deeply wired | integration | 1 | 0 | Provider request records only |
| Analyze | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Generate | records | 1 | 0 | Native records/view |
| Receipt scans | records | 1 | 0 | Native records/view |
| Scan | records | 2 | 0 | Native records/view |
| Calculate | records | 1 | 0 | Native records/view |
| Rules & Jobs | records | 2 | 0 | Native records/view |

Row popup verification passed: dashboard and feature rows, keyboard/focus, editing and persistence, delete confirmation/cancellation, centered mobile layout and full-record navigation. See `reports/row-popup-verification.json`.

## Verified local build

Build, API, browser and actual `start.sh` checks passed. All 391 feature pages were visited in the browser; 389 editable tables contain at least 15 fictional rows each. CRUD persistence and mobile layout were checked. Evidence is in `reports/verification.json`, `reports/browser-verification.json` and `reports/startup-verification.json`.

These checks cover the native local workspace. Full source-specific business rules, authentication and live provider operations remain incomplete as described above. Test servers were stopped after verification.

## AI workspace verification

All 306 AI feature routes were checked in the browser and show questions and formatted answers instead of the original record table. Existing records are retained as optional context. Questions, follow-ups, saved history across restart, Markdown tables, safe rendering, downloads, provider-failure recovery and mobile layout passed with a mocked provider. See `reports/ai-workspace-verification.json`.

Live answers require `OPENROUTER_API_KEY` and `OPENROUTER_MODEL` in this app's `.env` and an app restart. No live provider call was made during verification. Conversational answers do not execute unmigrated specialist engines, read record attachments automatically or perform external actions.


## AI word limits

Questions support up to 5,000 words with a live counter and server validation. AI responses and record drafts have a 16,000-token output budget and a default 180-second timeout to support answers up to 5,000 words; actual length depends on the request and model. Answers show their word count, and long questions can be expanded. Browser checks passed for 5,000-word questions and answers, saved history, full downloads, mobile layout and rejection of 5,001-word questions. See `reports/word-limit-verification.json` (mock-provider boundary checks).

## Merged AI assistants

306 original AI entries are now grouped into **8 assistants** in the sidebar. Choose up to 8 related capabilities and add up to 10 questions for one provider request and one saved response. Shared context is sent once; repeated questions are removed after trimming and whitespace/case normalization. The total question limit is 5,000 words and the combined answer target is up to 5,000 words.

Original feature URLs still open the appropriate assistant with that capability selected. Existing records and answers stay in place; the assistant history includes answers saved under its member features. Non-AI record tables retain their popup actions. This merges the assistant workflow and navigation; it does not implement previously missing external integrations or specialist engines. See `reports/assistant-merge-map.json` and `reports/assistant-merge-verification.json`.

## Floating Ask AI assistant

Implemented across this workspace. The bottom-right **Ask AI** button opens a persistent chat panel on every page. Use **Ask AI about item** in a row popup or record view, or **Use current item** inside the panel, to supply the selected record.

- Questions about the page, any explicitly chosen app record, and general topics.
- Formatted answers, comparison tables, follow-ups, copy and Markdown download.
- Conversation and question drafts stay intact during in-app navigation. Saved answers persist in SQLite; the last conversation restores in the same browser tab after reload. The latest 50 saved answers are listed; restoring one displays up to 20 turns. Up to four preceding turns are sent as AI context.
- Up to 5,000 input words and a response budget of up to 5,000 words. Output length remains dependent on the provider and the question.
- Page title and description are supplied automatically; record fields and notes are sent only for a selected item. Attachments and unselected records are not included. **New chat** starts without earlier conversation context.
- Existing AI provider configuration, timeout, rate limit and safe response renderer are reused. The assistant answers and drafts; it does not execute record changes or external actions.

Validation: shared backend tests, all 64 app builds/API checks, and all 64 browser checks passed with an injected test provider. Browser checks cover item context, navigation, saved history/reload, follow-ups, new-chat isolation, error recovery, word limits, keyboard controls, mobile bounds, safe Markdown rendering and attachment refresh. See [verification](reports/floating-ai-verification.json).

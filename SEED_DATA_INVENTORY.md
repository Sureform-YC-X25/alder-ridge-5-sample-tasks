# Alder Ridge Seed Data Inventory

This inventory is generated from the packaged five-task manifest, source registry, and read-only accounting snapshot. Run `python scripts/build_seed_inventory.py --check` to verify it.

## Summary

| Measure | Value |
|---|---:|
| Selected tasks | 5 |
| Company-world source files | 53 |
| Company-world source size | 1.69 MiB |
| Accounting database size | 74.35 MiB |
| Accounting business tables | 27 |
| Accounting rows | 575,008 |
| Accounting SHA256 | `00ddfe914af7abb109a05f703623f43c241ac5f90d73e0f4f5e46d9459b76e7d` |
| Source world | `alder-ridge-mechanical-v2` |
| Snapshot | `2026-06-30-pre-close` |

### File types

| Type | Files |
|---|---:|
| `csv` | 11 |
| `docx` | 3 |
| `eml` | 7 |
| `pdf` | 9 |
| `pptx` | 3 |
| `xlsx` | 20 |

### Source authority/version status

| Status | Files |
|---|---:|
| `approved-plan` | 1 |
| `approved-policy` | 1 |
| `approved-record` | 1 |
| `current-support` | 33 |
| `current-working` | 14 |
| `historical-final` | 2 |
| `stale-working` | 1 |

## Selected task source contracts

| Task | Minimum source artifacts | Accounting MCP |
|---|---:|---|
| `task_001` | 12 | required |
| `task_004` | 14 | required |
| `task_015` | 20 | required |
| `task_035` | 10 | not required |
| `task_068` | 22 | required |

## Accounting database

| Table | Rows |
|---|---:|
| `accounts` | 108 |
| `audit_events` | 0 |
| `bank_transactions` | 59,406 |
| `company` | 1 |
| `cost_codes` | 24 |
| `customer_invoice_lines` | 31,479 |
| `customer_invoices` | 31,479 |
| `customers` | 160 |
| `departments` | 6 |
| `employees` | 176 |
| `fixed_assets` | 81 |
| `job_cost_entries` | 20,627 |
| `journal_headers` | 98,518 |
| `journal_lines` | 212,805 |
| `payroll_run_lines` | 15,114 |
| `payroll_runs` | 215 |
| `prepaid_items` | 57 |
| `project_change_orders` | 8 |
| `projects` | 68 |
| `purchase_order_lines` | 2,057 |
| `purchase_orders` | 2,057 |
| `service_agreements` | 90 |
| `service_work_orders` | 30,576 |
| `timecard_entries` | 45,452 |
| `vendor_bill_lines` | 12,042 |
| `vendor_bills` | 12,042 |
| `vendors` | 360 |
| **Total** | **575,008** |

## Company-world source files

| Path | Type | Size | Status | SHA256 |
|---|---|---:|---|---|
| `Requests/7.1.26_822am - Fwd_ wip close need today.eml` | `eml` | 1.04 KiB | `current-support` | `e5a239130fffa8397c8dfefa35fd33042e7752d476c87442f9248973258e73cf` |
| `Requests/7.2.26_1027am - Q2 bank compliance package.eml` | `eml` | 1.17 KiB | `current-support` | `39fadb63e526e013663a8b9f50765ecdd96044c03b1a8c4f35f6548693cff30c` |
| `Requests/7.4.26_0711am - FY27 plan first pass + branch submissions.eml` | `eml` | 1.42 KiB | `current-support` | `3245fdbf484a84710e90b0d311a35484d8b55649e9643a392a3ed968804e94b2` |
| `Requests/7.4.26_1344pm - Q2 board lender + IR refresh.eml` | `eml` | 1.15 KiB | `current-support` | `1d5917863fbb30ddd4b70e33bcc8f829a7194968529ca172a67c455582b4c498` |
| `Requests/7.5.26_0618am - FY27 plan review follow-up.eml` | `eml` | 1.31 KiB | `current-support` | `27ee557525c77a24efc5780480317c8fee21c4b13f82f2cc7c83b28d802bbe0b` |
| `Requests/7.5.26_0812am - board review changes + source tie.eml` | `eml` | 963 B | `current-support` | `9ebdf491b7d6747051b34ffd4114b995f3a0c2fba5c1b4a4932d0f2850d4d8da` |
| `Shared/Finance/AP/Invoice Batches/2026/07/01/batch 20260701-02.pdf` | `pdf` | 81.70 KiB | `current-support` | `18bf0f58a5a02b35d38ff210784274ec23d3d44ff085d6c6dced346ea38a2f4b` |
| `Shared/Finance/Accounting Policies + old memos/Revenue recognition - WIP policy_rev11-24 SIGNED scan.pdf` | `pdf` | 71.52 KiB | `current-support` | `714c589af37ce0f56821402e0842fefd342bceffda34022589dd8b8f31d272c7` |
| `Shared/Finance/Close/2026/05 May/4_WIP/WIP 5.31.26_FINAL_v7_revised NB.xlsx` | `xlsx` | 372.68 KiB | `historical-final` | `e4687e5de974150d1ee9331746d454eae751e30b8bc8d9cf43ae09e740bb3426` |
| `Shared/Finance/Close/2026/06 June/1 close mgmt/June close tracker - working - upd 7.1 810am.xlsx` | `xlsx` | 14.34 KiB | `current-working` | `22e77cb10e58cabf009475cef8ee18dc3ad6d653b04a64eeec5b39a838352dcd` |
| `Shared/Finance/Close/2026/06 June/2 reconciliations/TB rec_6.30 prelim - NB v4.xlsx` | `xlsx` | 16.81 KiB | `current-working` | `bf74cf03714d36bb0a3e1b17ce5ff0b9212494ca5b143e01b146443b4d07958d` |
| `Shared/Finance/Close/2026/06 June/2 reconciliations/Vista billing batch history through 7.5.csv` | `csv` | 6.53 KiB | `current-support` | `91e80f1d46a28223903170023119e0e1cadd78644aa45f44fae1e5523af57668` |
| `Shared/Finance/Close/2026/06 June/3 accruals/AP cutoff + accrual list_7.1 OL.xlsx` | `xlsx` | 87.43 KiB | `current-support` | `15cebc513bb80e0bf7de09078bd761f2a78d6e8a7271b7e4ef9a6401c2a0bbb5` |
| `Shared/Finance/Close/2026/06 June/4 WIP/ARM-2409 June WIP controller sign-off - WORKING.docx` | `docx` | 42.59 KiB | `current-working` | `ca7a510681f801b9a9697b1fb503f6a05c0d52b5d88aa9c5052a6241ad0110af` |
| `Shared/Finance/Close/2026/06 June/4 WIP/WIP risk cases_7.1 847am - NB REVIEW COPY.xlsx` | `xlsx` | 6.66 KiB | `current-working` | `6e82251b717b922d6067e467a99419ed134d4385fd11b5878608c53813ef9120` |
| `Shared/Finance/FP&A/Backlog/FY27 backlog burn and capacity - WORKING.xlsx` | `xlsx` | 24.65 KiB | `current-working` | `d2aa283d16f9d875371388994f317b49420fb39bfbcb15b342cd3b31dfb8d37f` |
| `Shared/Finance/FP&A/Backlog/backlog burn + award pipeline_6.30 v6.xlsx` | `xlsx` | 13.15 KiB | `current-support` | `7420b603202cf0cb5c1e870500817e40c6c0ac15184160a3dc01545dc2a5af38` |
| `Shared/Finance/FP&A/FY26 plan + reforecast/FY26 Op Plan_BoardApproved_12.18.25_FINAL2.xlsx` | `xlsx` | 19.54 KiB | `approved-plan` | `a343602eec8aacf00861914257bd0cb5854e0e671adca830e295cf8592e5d713` |
| `Shared/Finance/FP&A/FY26 plan + reforecast/FY26 guidance cases_7.5.csv` | `csv` | 1.31 KiB | `current-support` | `92fa7c0cabd403420c606304d9aa32b9590b9befa67040b9f491e5821c48bf73` |
| `Shared/Finance/FP&A/FY26 plan + reforecast/FY26 rolling forecast_v12 - pre WIP.xlsx` | `xlsx` | 13.01 KiB | `stale-working` | `af52aadb93a221ef583d9aa00caf938fe956184aa324e2c7248c3bc591f85039` |
| `Shared/Finance/FP&A/FY26 plan + reforecast/June case sensitivity inputs_7.5.csv` | `csv` | 1.69 KiB | `current-support` | `7974c4519ee33d2b1ccd59b65230302cbd1e8ae587b7a8614447a27e8000a40f` |
| `Shared/Finance/FP&A/FY26 plan + reforecast/department reforecast inputs - June pull.xlsx` | `xlsx` | 12.96 KiB | `current-support` | `637dddc8e52bbc182d4da7be3d40f816c2ce6cc527923260742a78dc7bd23847` |
| `Shared/Finance/FP&A/FY27 plan/FY27 planning assumptions - v4 branch draft.xlsx` | `xlsx` | 35.10 KiB | `current-working` | `c0091953a125394a8c647b292ab5a8c550401b5bc98950a99c41578ac1ce8839` |
| `Shared/Finance/FP&A/FY27 plan/FY27 planning assumptions - v6 controller tie.xlsx` | `xlsx` | 89.46 KiB | `current-support` | `f365b0a68552c88cb6fe2b45383ce90025894cd8c959ed03fa9b13263c08ca7e` |
| `Shared/Finance/FP&A/FY27 plan/FY27 planning definitions + scenario guardrails - APPROVED.pdf` | `pdf` | 19.86 KiB | `current-support` | `69a1fb011d8d4e2c0a59d949f2f110bd8b7be88d218dea12b2a4924de843b144` |
| `Shared/Finance/FP&A/FY27 plan/FY27 steering committee notes - 7.3 DC.docx` | `docx` | 46.38 KiB | `current-support` | `d28b9f8d355c9dbcb332ff727b746ea06813b9912fa8138d7b69e40e6b3e6933` |
| `Shared/Finance/Investor Relations/Q2 working/FY26 published range record_6.18.csv` | `csv` | 632 B | `approved-record` | `bd8188890a513e7a0becf4851f15e332b051f50bd24c9b06072f56e71779585c` |
| `Shared/Finance/Investor Relations/Q2 working/KPI definitions + lender presentation policy.pdf` | `pdf` | 5.43 KiB | `current-working` | `e5293a2b6d7b71fa80d605fa455e9040232714e2c65083e20adc68a54458a2ea` |
| `Shared/Finance/Investor Relations/Q2 working/guidance interval settings_6.18.csv` | `csv` | 507 B | `approved-policy` | `2a649cacd6936252d95dee26a303144970e1d02b3067107ff5eafe6e611e6dd4` |
| `Shared/Finance/Reporting/2026/06 June/FY26 outlook risk register_7.5.csv` | `csv` | 1.50 KiB | `current-support` | `429d9332b6fe881bd9f60d0e29255e8625778563968d3536da60faed8884c628` |
| `Shared/Finance/Reporting/2026/06 June/Finance action review notes_7.5.csv` | `csv` | 6.09 KiB | `current-support` | `385ee6303c4d42670c439a2af7f398cdb1557356e9b748246be288b836087955` |
| `Shared/Finance/Reporting/2026/06 June/June executive performance review - WORKING.pptx` | `pptx` | 49.58 KiB | `current-working` | `377e6c3f7cfb8b28625ac4c674ab01139d45de6082e6c99bb7025add47319d33` |
| `Shared/Finance/Reporting/2026/06 June/Q2 board + lender narrative review notes - 7.4 DC.docx` | `docx` | 39.17 KiB | `current-support` | `e3e85a9634ad4b50af59bad0d5b911d0d50432b43f4cfc4defca455e288ab40c` |
| `Shared/Finance/Reporting/2026/06 June/Q2 management reporting cube extract_7.2.csv` | `csv` | 7.96 KiB | `current-support` | `53a79ff1afa7cbeb5b3f047ac14f4a0397339f4eaeaa90a524bca2b1e01fbdbc` |
| `Shared/Finance/Reporting/2026/06 June/Q2 management reporting data book - v5 CFO scratch.xlsx` | `xlsx` | 20.45 KiB | `current-support` | `74910243fb70ae7b9e33f60b9263c484f93ed24f0bc856ce0228e5848b05c5e2` |
| `Shared/Finance/Reporting/2026/06 June/Q2 management reporting data book - v7 controller tie.xlsx` | `xlsx` | 23.37 KiB | `current-support` | `d41bc01197966303831d3490bfdc2ae78d19a5d1d32063d7aaac06522766daa6` |
| `Shared/Finance/Reporting/Board/Q1 2026/Q1 board package - FINAL signed off.pptx` | `pptx` | 29.44 KiB | `historical-final` | `d5833bba0c2daead046a3de58f3fba38394f104836247e3778c5707ab85bc222` |
| `Shared/Finance/Treasury/Bank - covenants/2026 Q2 working/Q2 covenant headroom - lender review working.xlsx` | `xlsx` | 7.05 KiB | `current-working` | `54dd0ed1913e3009687f3c22abef130caa78ee6f20673f15e5bb594f55abbcb8` |
| `Shared/Finance/Treasury/Bank - covenants/2026 Q2 working/Q2 lender update - review working v3.pptx` | `pptx` | 27.01 KiB | `current-working` | `77e6107f163af332d357bb0d676be4dd03d47b723e8faa932659f1bb45992c0d` |
| `Shared/Finance/Treasury/Bank - covenants/Agreement + amendments/USBank_Amdt2_9.30.25_EXECUTED scan.pdf` | `pdf` | 75.08 KiB | `current-support` | `f421b58250ffda87755630d94e80aacdd8f66e0745d163655f469b9fe30092dc` |
| `Shared/Finance/Treasury/Debt/debt sched - 6.30 before bank pkg.xlsx` | `xlsx` | 9.74 KiB | `current-support` | `f3ee4a488e34799d7980b5606c07aef84df79156046506853ef8aab984179be0` |
| `Shared/Operations/Commercial/CO Log/6.30 support - not all final/2409_commercial working_6.24.pdf` | `pdf` | 66.53 KiB | `current-working` | `62f50db0199c82610dd15d8969e04d7e1a83bb0c69edcb9f6ff8eab9674e0016` |
| `Shared/Operations/Commercial/CO Log/6.30 support - not all final/2417_PCO17_owner emails + FD summary_6.30.pdf` | `pdf` | 66.40 KiB | `current-support` | `4e1fa1ce8d6d8e959179410a21806beb910c8fd5043b969517984a2f86b4fb56` |
| `Shared/Operations/Commercial/CO Log/6.30 support - not all final/2506_PCO6_DB27 backup + cost est (working).pdf` | `pdf` | 66.31 KiB | `current-working` | `e2cb22ed385b217b25a0c268172b11d4cae1cbae79385ffc76f0b0f9d43b63a0` |
| `Shared/Operations/Commercial/CO Log/CO log MASTER (do not sort)_6.30.26 - PR copy.xlsx` | `xlsx` | 13.49 KiB | `current-working` | `202486070d2b00632526e7bcfee5a55033982d487845a68a5092334341756b41` |
| `Shared/Operations/Commercial/Contract Records/2026/07/02/scan batch 20260702-01.pdf` | `pdf` | 71.48 KiB | `current-support` | `80f9f1a98c5c5b80ae6506d29ccf0df1d800945d79ee9b87caf2a28b2c60bc13` |
| `Shared/Operations/Commercial/Correspondence Archive/2026/06/30/sent 1706.eml` | `eml` | 690 B | `current-support` | `0848b5bb100d485d63eb9f9dc68eb6319e22ffc30ef09df4a813d4b6d3f74e81` |
| `Shared/Operations/Planning exports/CRM backlog service renewals + forecast history_6.30.csv` | `csv` | 40.79 KiB | `current-support` | `31fd81d80484059dd8b6825860ca6d45d3bedc1fe793333b0d298bc3480d05bc` |
| `Shared/Operations/Planning exports/July owner support log_7.5.csv` | `csv` | 4.39 KiB | `current-support` | `7e50e98730b4b42457d47e304b01c234ff219b51612e0961b588fac724ee3bf7` |
| `Shared/Operations/Planning exports/Q2 operating evidence extract_7.5.csv` | `csv` | 7.79 KiB | `current-support` | `1399ed49be4a631fbd379d8ffad071281eac5549197337e7e567f43fcab93dae` |
| `Shared/Operations/Project Controls/cash curves/major jobs cash curves_6.30 scenario B.xlsx` | `xlsx` | 20.45 KiB | `current-support` | `d3cd0948eafc562b1ead187c86e9d8f1bbe27e2d44a31897efb77443d57ff525` |
| `Shared/Operations/Project Forecasts/June26 - PM updates/PM ETC updates_6.29 530pm_COMBINED_v3.xlsx` | `xlsx` | 18.54 KiB | `current-support` | `8ca9b478dd7613a0a9289b4b44bf04fe6de0542161c9bf9713dc3d6cf2866c9a` |
| `Shared/Operations/Service/monthly KPI/service KPI pack source_6.30 - LT edits.xlsx` | `xlsx` | 65.25 KiB | `current-working` | `3c4c11129e0c78cb1c10cee1e0985aa855fe920e6bcaeefc16f70a86433665cf` |

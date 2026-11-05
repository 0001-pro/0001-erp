# 0001 ERP

**Lightweight ERP system for wholesale trade and warehouse management.**

0001 ERP is an integrated business management system designed to support wholesale and retail operations, inventory management, warehouse workflows, and business document processing.

The system was independently designed and developed by the author and has been used in real business environments for many years.

Website: https://0001.pro/erp/

## Overview

0001 ERP was developed to address practical business requirements in trading companies, with a particular focus on wholesale operations and coordination between office personnel and warehouse staff.

The system combines desktop and web interfaces with centralized business logic and database processing.

Its design emphasizes operational control, traceability of business transactions, and accurate management of inventory and goods movement.

## Core capabilities

- Product and counterparty management
- Wholesale and retail operations
- Multi-currency support
- Warehouse inventory management
- Incoming, outgoing, and transfer documents
- Reservations and returns
- Cash operations
- Product movement history
- Document change history and restoration
- Multi-user access and resource locking
- Business analytics and reporting
- Supplier price list processing
- Document generation and printing

## Warehouse management

One of the distinctive features of 0001 ERP is the separation of physical warehouse stock from operationally available stock.

This approach allows sales managers to allocate goods to customer orders while warehouse personnel separately confirm actual goods movement.

The system maintains separate records for commercial availability and physical inventory operations, helping coordinate office and warehouse workflows.

## Architecture

The original implementation is based on a client-server architecture and includes:

- **C++ / Qt** — desktop application for office personnel.
- **PHP** — server-side business logic and web application functionality.
- **MySQL / MariaDB** — centralized data storage and database-level processing.
- **Web interface** — warehouse operations and inventory document management.
- **Java utilities** — auxiliary spreadsheet processing and generation.

The system uses database views, triggers, and stored procedures as part of its data processing architecture.

## Project status

0001 ERP is an established software system currently undergoing technical review, source code restoration, and architectural documentation.

The immediate objective is to preserve the existing functionality, document the architecture, evaluate modernization opportunities, and determine the future development direction.

The source code is not yet published in this repository.

## Project information

- Product: **0001 ERP**
- Developer: **0001.pro**
- Category: Business software / ERP
- Focus: Wholesale trade and warehouse management
- Website: https://0001.pro/erp/

---

© 0001.pro

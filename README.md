# hana_app

## Contents

This repository contains the results from the following SAP tutorials:

1. Mission: Getting Started with XS Advanced Development
https://developers.sap.com/mission.xsa-get-started.html
2. Tutorial Group: Expose Entities Using OData and XSJS with SAP HANA XS Advanced
https://developers.sap.com/group.hana-xsjs-xsodata.html
3. Create an SAPUI5 application with SAP HANA XS Advanced
https://developers.sap.com/group.hana-xsa-sapui5.html
Requirements: SAPUI5 >= v1.40

## Prerequisites

On a fresh SAP HANA Express it is required to do the following tasks which are contents of the tutorials mentioned above:

1. **Tutorial** Configure a Space to Develop on a Tenant Database (XS Advanced): https://developers.sap.com/tutorials/xsa-tenant-db-space.html
2. **Create UAA service** https://developers.sap.com/tutorials/xsa-html5-module.html
3. **Tutorial** SAP HANA XS Advanced, Access a classic schema from an HDI container: https://developers.sap.com/tutorials/xsa-create-user-provided-anonymous-service.html

## Implementation

1. Build db module
2. Build core_xsjs module
3. Run web module

## Features

- **products.hdbcalculationview** Graphical calculation view with dimension data type 
- **purchase_orders.hdbcalculationview** Graphical calculation view with cube data type, star join and currency conversion
- **businessPartners.xsodata** Simple ODataservice
- **purchaseOrders.xsodata** OData with entity relationship and XSJS service 
- **user.xsodata** OData service with create option
- **index.html** SAPUI5 list and usage of SAPUI5 library from local XSA
- **odataBasic/index.html** Consume basic OData service with SAPUI5 list app with dynamically creating columns
- **odataView/index.html** Consume multi entity OData service with SAPUI5 form and list app
- **odataCRUD/index.html** SAPUI5 form and list app with create, read and update options

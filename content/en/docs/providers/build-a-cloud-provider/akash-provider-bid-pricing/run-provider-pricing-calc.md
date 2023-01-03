---
title: "Run Provider Pricing Calc"
key: "run-provider-pricing-calc"
description: ""
lead: ""
date: Thu Dec 29 2022 03:03:46 GMT-0800 (Pacific Standard Time)
lastmod: Thu Dec 29 2022 03:03:46 GMT-0800 (Pacific Standard Time)
draft: false
images: []
weight: 1
toc: true

menu:
    docs:
        parent: "akash-provider-bid-pricing"

---
Run Provider Pricing Calc
=========================

In this step we will detail:

*   Command syntax for the provider pricing estimation script
*   Example templates based on different provider host/server footprints
*   Example script execution

**NOTE** - we recommend initially leaving the pricing standards used in the script as is. Once comfortable with the script the pricing specifications may be updated if you feel necessary. The default pricing standards for CPU/memory/ephemeral storage/persistent storage may be viewed in the script located [here](https://github.com/ovrclk/helm-charts/blob/main/charts/akash-provider/scripts/price_script_generic.sh).

Command Syntax
--------------

*   Details on the input to the scripts are reviewed in the subsequent section

    ./charts/akash-provider/scripts/price_script_generic.sh <<<  <deployment-order-request-specs>
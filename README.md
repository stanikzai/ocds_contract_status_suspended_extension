# Contract Status Suspended

[ocds_contract_status_suspended_extension](https://github.com/stanikzai/ocds_contract_status_suspended_extension) 

Most of the time a contract is suspended due to force majeure or any security issue. This status of the contract helps in tracking the status of a contract and why it is suspended and when it will be active again,
we have mapped the suspended status to the active status of close codelist of contract status and added an extension as suspended which holed true/false value.

## Overview
The field introduced by this extension is:

    contract/suspended it has true and false value in case a contract is suspend contract/status contain active value and suspended contain true value
## Examples
The following extract illustrates this property in use within the contract block.

            "contracts": [{
                 "status": "active",
                 "suspended": true,
            }]

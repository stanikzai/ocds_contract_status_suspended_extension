# Contract Amendment Type

[ocds_contract_status_suspended_extension](https://github.com/stanikzai/ocds_contract_status_suspended_extension) 

The contract amendment type can be used to record the type of amendment brought into contract.

## Overview
The field introduced by this extension is:

    contract/amendments/type - Type of contract amendments. It should be one of these values: timeAmendment,costAmendment, timeAndCostAmendment, amendmentInContractConditions.

## Examples
The following extract illustrates this property in use within the contract block.

            "contracts": [
            {
                 "amendments": [
                         {
                           "id": "311",
                           "type": "timeAndCostAmendment",
                           "date": "2016-12-20T00:00:00+04:30",
                           "description": "تعدیل در قیمت و معیاد قرارداد صورت گرفته است که قیمت قرارداد را از 549669774 افغانی به 687087218 افغانی و معیاد قرارداد را از تاریخ 2016-12-20  به تاریخ 2017-02-28 افزایش داده است.",
                           "amendsReleaseID": "5c10b6e07e0a9475f50d7015-MoD-G-0001|1",
                           "releaseID": "5c10b7ed7e0a947c1637cc0d-MoD-G-0001|1",
                           "rationale": "با آنکه پروسه تدارکاتی جهت رفع نیازمندی های سال اینده موفقانه پیشبرده میشود، لازم خواهد بود که بطور احتیاطی و جلوگیری از احتمال ناغگی قطعات و جزوتام ها ، بمنظور اکمالات به موقع و آمادگی عملیات شفق پیش بین بوده و تدابیر مؤثر فراهم گردد."
                         }
                       ],
            }
            ]

# Procurement method rationale classifications

Adds an array to the tender object to classify the procurement method rationale.

## Legal context

In the European Union, this extension's fields correspond to [eForms BT-135, BT-136](https://github.com/eForms/eForms). See [OCDS for the European Union](http://standard.open-contracting.org/profiles/eu/master/en/) for the correspondences to Tenders Electronic Daily (TED).

## Example

```json
{
  "tender": {
    "procurementMethodRationaleClassifications": [
      {
        "id": "D_NO_TENDERS_REQUESTS",
        "description": "No tenders or no suitable tenders/requests to participate in response to a procedure with prior call for competition",
        "scheme": "TED_PT_AWARD_CONTRACT_WITHOUT_CALL"
      },
      {
        "id": "D_FROM_LIQUIDATOR_CREDITOR",
        "description": "Purchase of supplies or services on particularly advantageous terms from the liquidator in an insolvency procedure, an arrangement with creditors or a similar procedure under national laws and regulations",
        "scheme": "TED_PT_AWARD_CONTRACT_WITHOUT_CALL"
      }
    ]
  }
}
```

## Issues

Report issues for this extension in the [ocds-extensions repository](https://github.com/open-contracting/ocds-extensions/issues), putting the extension's name in the issue's title.

## Changelog

This extension was originally discussed as part of the [OCDS for EU profile](https://github.com/open-contracting-extensions/european-union/issues) and in [pull requests](https://github.com/open-contracting-extensions/ocds_procurementMethodRationaleClassifications_extension/pulls?q=is%3Apr+is%3Aclosed).

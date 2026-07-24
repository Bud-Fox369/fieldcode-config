# fieldcode-config

Remote plan configuration for the **FieldCode** iOS app.

`financing.json` holds the Contractor Loan PRO (Momnt) plan definitions the app loads at launch.
Editing it here updates plan terms/APRs in the app without an app update.

**Merchant fees are intentionally omitted** from this public file — they are internal cost data.
The app restores them from its bundled copy by plan ID.

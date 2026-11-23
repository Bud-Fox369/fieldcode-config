# fieldcode-config

Remote plan configuration for the **FieldCode** iOS app.

`financing.json` holds the **Sunlight Financial** plan definitions the app loads at launch — the
one source for plan terms. Editing it here updates terms, APRs, payment factors, minimum loan
sizes and card labels in the app without an app update. The app bundles a copy as its offline
fallback.

**Merchant fees and Sunlight product codes are intentionally omitted** from this public file —
they are internal data. The app restores them from its bundled copy by plan id.

# Development and validation

`car_rental.rp` is the editable Axure source of truth. This is an interaction-design prototype, not an implemented booking application. Keep the native document name unchanged when opening it in a compatible Axure RP installation.

Recommended working layout:

- Edit `car_rental.rp` in Axure RP.
- Generate local HTML previews into `exports/` and local backups into `backups/`; these directories are ignored.
- Keep intentional screenshots or walkthrough material in a separate tracked documentation folder if you add them later.
- Review and commit native-document changes as a whole; `.gitattributes` marks `.rp` as binary to avoid corrupt text merges.

## Hosted-preview check — October 15, 2026

The repository's existing [Axure Share preview](https://rwg88z.axshare.com/) loaded successfully. City selection updated the office choices; the missing-date message could be dismissed; choosing dates through the calendars allowed navigation from HOME to the CAR selection page. That page displayed vehicle rows, filters, sorting, and rental controls. Filter, sorting, and rental actions were not validated.

The calendar inserted `05/16/2015` and `05/18/2015` in the tested journey despite displaying a November 2019 heading. Treat these as fixed prototype values, not working current-date booking logic. The review stopped before rental submission, account, or payment actions.

No source document or generated prototype was edited. The hosted version was not matched to the native `.rp` file. Native editor compatibility, internal object inspection, and a complete interaction review require a compatible Axure installation. No booking persistence, authentication, payment, API, SQL, or real inventory integration was established.

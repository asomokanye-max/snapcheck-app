# Snap Check (pilot)

Checks the health facility monthly summary form before it leaves the facility.

- **Who uses it:** facility staff (records officers, nurses in charge) and LGA M&E officers.
- **Pilot sites:** selected health facilities in Ife Central and Ife East LGAs, Osun State, Nigeria.
- **What it does:** the user photographs the paper form (or types the figures); the AI reads each box; the user confirms the reading against the paper; the tool checks for blank boxes, wrong row and column totals and impossible figures; the user corrects from the registers and saves. Reading accuracy and errors caught are recorded.
- **Privacy:** aggregate counts only, no patient names; photos are not stored. Test data only until Ministry approval.
- **Built with:** a single HTML page hosted on Netlify, with a Supabase database and an Edge Function that calls the Anthropic Claude API. No secret keys are kept in this repository.

Institute of Public Health, Obafemi Awolowo University, Ile-Ife.
Principal investigator: Akingbola Sunday Omokanye.

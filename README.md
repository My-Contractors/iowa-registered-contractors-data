# Iowa registered construction contractors

Every construction contractor registered with the State of Iowa under Iowa Code ch. 91C: 17,803 businesses,
99 counties, 32 trades, as exported by the State on September 21, 2026.

Compiled by Iowa's Best Contractors (https://contractiowa.com). Method and definitions:
https://contractiowa.com/methodology

## Cite this dataset

Iowa's Best Contractors (contractiowa.com), Iowa registered construction contractors, compiled from the State of Iowa contractor registration record (Iowa Code ch. 91C), exported September 21, 2026.
https://contractiowa.com/methodology

## Source

Active Iowa Construction Contractor Registrations, Iowa Department of Inspections, Appeals, and Licensing (DIAL),
https://dial.iowa.gov/licenses/building/contractors, published through the Iowa Data Hub. The State's portal is the
authoritative record; verify any registration at https://laborportal.iwd.iowa.gov/iwd_portal/ using its
registration number.

Registration shows compliance with Iowa's contractor registration law. It is not a license and not a quality rating.
Electrical, plumbing, HVAC and mechanical work also needs a license from a State board.

## Files

| File | What it is |
|---|---|
| `iowa-registered-contractors.csv` | one row per registered business |

Columns: `name`, `owner_name`, `trade`, `city`, `county`, `zip`, `home_state`, `registration_number`, `registration_status`, `registration_issued`, `registration_expires`, `phone`, `profile_url`.

Business names are lightly normalized for display (possessive 'S to 's, LLC and HVAC casing, O'Brien and McCarthy
casing, short initials such as JC in capitals, a name repeated after DBA). Every other field is the State's value.
`county` is blank where the State's address is outside Iowa or has no county. No email addresses or street addresses
are included.

## Updates

Refreshed monthly from the State's weekly export: each month's snapshot is a release tagged with the State's export
date, with the CSV attached. The live, weekly copy is always at https://contractiowa.com/data/iowa-registered-contractors.csv

## License

Public record (State of Iowa), not copyrightable: Feist v. Rural Telephone (1991). See LICENSE.md.

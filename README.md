# Courts In Demand

## How Tennis Clinic Programming Relates to Daily Member and Inn-Guest Bookings at High Hampton Country Club

This project examines whether tennis clinics are associated with changes in daily member and inn-guest court bookings at High Hampton Country Club.

The analysis uses daily tennis activity data from four summer seasons, 2023–2026. It evaluates whether clinics are associated with lower aggregate regular court-booking volume after accounting for weekday, month, and year.

## Main finding

After accounting for calendar patterns, tennis clinic participation was positively associated with daily regular court bookings rather than lower booking volume. Days with clinics of 6–10 participants and 11 or more participants had higher expected booking rates than comparable days without clinics.

These results describe an association and do not establish that clinics cause higher booking demand or eliminate possible time-specific access constraints.

## Files

- `HH_project.Rmd`: R Markdown source code for data cleaning, modeling, tables, and figures.
- `HH_project.pdf`:project report.

## Methods

The primary outcome was daily member and inn-guest tennis court bookings. The primary predictor was the number of tennis clinic participants.

Negative-binomial regression models adjusted for:

- Weekday
- Month
- Year

A secondary model compared booking activity across clinic-size categories:

- No clinic
- 1–5 participants
- 6–10 participants
- 11+ participants

## Data availability

The raw operational data are not included in this repository because they contain internal club information. The analysis code is provided for documentation and reproducibility for authorized users with access to the source data.

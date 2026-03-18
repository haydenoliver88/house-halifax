# Wrangling Notes

## Tools Used
- Tableau
- Excel

## Dataset 1: CMHC Rental Market Data
### Issues Found
- Data was spread across multiple sheets
- Column names were inconsistent
- Some values required interpretation (e.g., affordability metrics)

### Steps Taken
- Selected relevant variables (vacancy rate, rent/affordability)
- Cleaned and organized columns in Tableau
- Removed unnecessary fields

### Assumptions / Decisions
- Used affordability-related variables as a proxy for rent
- Focused on most recent available data

## Dataset 2: Halifax Rental Market Survey Zones (LEMR)
### Issues Found
- Some variables had unclear naming conventions
- Percentage values were incorrectly aggregated in Tableau

### Steps Taken
- Selected key variables (zone, renter %, affordability measures)
- Changed aggregation from SUM to AVG where necessary
- Filtered and structured data for visualization

### Assumptions / Decisions
- Assumed renter percentage reflects housing demand pressure
- Used zone-level data to analyze spatial differences

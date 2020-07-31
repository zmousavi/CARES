# CARES

CARES Act data: PPP, EIDL and more.

Data downloaded from the [Small Business Administration's DropBox](https://sba.app.box.com/s/tvb0v5i57oa8gc6b5dcm9cyw7y2ms6pp)

## PPP Data Dictionary

### Structure

Rows: 4,885,388
Potential duplicate rows: ~4,353 (still investigating)

Variables:



|variable      | n_missing| perc_missing|
|:-------------|---------:|------------:|
|LoanRange     |   4224170|         86.5|
|BusinessName  |   4224171|         86.5|
|Address       |   4224170|         86.5|
|City          |         1|          0.0|
|State         |         0|          0.0|
|Zip           |       224|          0.0|
|NAICSCode     |    133527|          2.7|
|BusinessType  |      4723|          0.1|
|RaceEthnicity |         0|          0.0|
|Gender        |         0|          0.0|
|Veteran       |         0|          0.0|
|NonProfit     |   4703708|         96.3|
|JobsRetained  |    324122|          6.6|
|DateApproved  |         0|          0.0|
|Lender        |         0|          0.0|
|CD            |         0|          0.0|
|LoanAmount    |    661218|         13.5|

Notes: LoanRange is missing from all state data, giving the 86.5% missing number, but actual loan amount is included instead.
RaceEthnicity, Gender, and Veteran do not indicate missing data, but most of the data in those fields are "Not Answered" due to these questions being optional.
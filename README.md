# QualityControl
A REST API to ingest and validate a set of station data against data expectation

## Scope
The app is instended to run as a service app (via a docker container) and be fed tabular data. The columns are the validated using a set of defined quality measures (using great_expectations).

## Checks
### Basic Data Integrity
These expectations test for valid data (no NaN, continous data, target values ranges)

### Anomaly Detection
This could be relevant in the scope of MOSES. The aim is to spot hot spots/ hot moments or other distinct events that require immediate attention

## API structure
TBD

# DataCollection

## Feature

Storing data in the remote server using "JSON" format.

## Acceptance Criteria

### Scenario: Data collection from wearable device

  Given the patient uses wearable device compatible with google fit

  When every time interval passes

  Then wearable device collects the reading from the wearable device and stores
  it in a remote secure server.

# CerVota
## Simple voting system built on Drupal 10

### Basic setup
This system was built using DDEV. Lando may also work; YMMV.

Config Sync files are present at `web/sites/default/files/sync/`.

There's also 3 nice pictures to give you a head start on re-creating the options for the default Survey.

There's a database dump (cervota.sql.gz) in case you get stuck, but otherwise feel free to contact me.

### Voting
Visit `/form/survey` to cast your vote.

### Results
Voting results are shown on `/form/survey/confirmation` after voting. These can be hidden via Permissions at `/admin/people/permissions`.

### REST Endpoint
Third-party apps can access voting results at `/survey/rest`.

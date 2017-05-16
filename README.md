# Creating a new event entry

1. Open `/event.template`.
2. Save a copy as `_events/<YEAR>-<MONTH>-<DAY>-<TITLE>.md`; e.g. `_events/2011-01-20-test.md`.
3. Modify as you see fit.  Create multiple sessions within the event by creating a list of objects under the `session:` key.

On a `page`, the text "$BUCKET" will be replaced with the URL in `_config.yml:path_to_bucket`.  This is used for pointing to assets on Amazon S3.
## Notes
This has a minimal repro up to and including the data loading but no queries or anything since it doesn't seem needed to show the issue.

## Data

Uncompress comments.7z under the hn_track directory.

## Rally Invocation

`esrally race --kill-running-processes --track-path=./hn_track --offline --target-hosts=localhost:9200 --pipeline=benchmark-only`

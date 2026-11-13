# Beacon Release Tracker

Change records and release escalations for the Beacon line.

## Escalation convention

License escalations are filed as issues titled
`[LICENSE-BLOCK] <component_key>` and must quote the upstream project's
canonical GitHub slug in the issue body. The canonical slug is the location
recorded for the component in the release register.

## Upstream license watch

Register metadata is refreshed at each release gate; upstream projects may
relicense between gates without an entry here. Verification always reads the
license committed in the mirror subtree at the pinned commit.

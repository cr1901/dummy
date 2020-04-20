This is a dummy repo for testing Atom's Git Plus functionality in Atom
(as MVCE).

On Windows, it appears `GIT_SSH` _must_ be set for the `Fetch`/`Pull` button
to work. In addition, `GIT_SSH` _must_ use forward-slashes for paths (`/`),
as an msys shell will otherwise fail to find an `ssh` binary with a cryptic
`unable to fork` error.

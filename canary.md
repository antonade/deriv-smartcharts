# Authorized canary (HackerOne, @antonade)

This file exists to demonstrate, with Deriv's written permission, that a pull
request can deliver agent configuration past the "Strip PR-supplied agent
config" step by committing it as a symlink.

It reads no secret, makes no network call, writes nothing outside /tmp, and is
deleted with this pull request.

# plushu-meta-app-env

This Plushu plugin provides general metadata about an app's configuration to
its release environment in the form of environment variables.

These environment variables are:

## PLUSHU_APP

The name of the app.

## PLUSHU_APP_DOMAINS

A space-separated list of domains configured for the app (including
automatically-determined domains, like the one based on the app's name).

## PLUSHU_APP_ADDONS

A space-separated list of the addons configured for this app.

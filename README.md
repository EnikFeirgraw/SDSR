# SIMPLE DISK SPACE REPORTER

## What is it?
SDSR is a small, simple shell script for monitoring disk usage via du -P (POSIX PORTABLE), then reporting via email to administrators when a specified threshold has been reached/exceeded.

## Configuration
In order to make SDSR work for your environment, you will want to edit the $EMAIL and $THRESHOLD variables.

$THRESHOLD is a integer from 0-100, which directly relates to the usage percentage you would like a warning

$EMAIL is an array, delimited by spaces. Enter all required email address in the array.

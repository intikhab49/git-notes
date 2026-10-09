# Databases in CI with services

A job's `services:` block starts containers like `postgres:16` beside the runner. On a Linux runner without a job container, map ports and connect to `localhost`; add a health-cmd so steps wait for readiness.

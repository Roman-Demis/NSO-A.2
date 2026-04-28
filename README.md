# NSO Assignment 2 – HAProxy + Flask + Ansible

This repository contains:

- `hosts` — inventory file
- `site.yaml` — main playbook
- `README.md` — documentation

## What the playbook does

1. Installs and runs the Flask app from `application2.py` on devA, devB, devC.
2. Installs and configures HAProxy to load balance between the three servers.
3. Performs a functional test by sending 3 HTTP requests and verifying that all three backends respond.

## SSH

The grader runs:


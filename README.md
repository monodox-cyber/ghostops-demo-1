# GhostOps Demo Repository 1

This repository is intentionally vulnerable and used for demonstrating GhostOps scanning capabilities.

## Purpose
- Test secret leak detection
- Validate infrastructure configuration scanning
- Demonstrate webhook-based automation
- Showcase PR remediation generation

## Contents
- `.env` - Contains exposed secrets for testing
- `infra/sample.yaml` - Insecure infrastructure configurations
- `CHANGELOG.md` - Used for testing push events

## GhostOps Features Tested
- Secret leakage detection
- Infrastructure config scanning  
- Webhook-based scan automation
- PR creation on remediation fixes

⚠️ **Warning**: This repository contains intentionally insecure code and should only be used for testing purposes.
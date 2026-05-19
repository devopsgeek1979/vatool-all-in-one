# VATool All-in-One (AegisOS)

Public demo repository for the AegisOS security operations toolkit, packaged for Linux, macOS, and Windows.

## What is included

- HTTPS web dashboard for security operations
- Role based access control with these roles:
  - Admin
  - Operator
  - Security Consultant
- First run setup flow for account bootstrap
- Login, signup, recovery, and password reset paths
- CIS Benchmarks views for compliance posture tracking
- Machine enrollment by hostname, network address, and network range
- Machine activation workflow for deployment execution
- Live operational logs in the browser
- Public certificate download endpoint for browser trust onboarding
- Cross platform package outputs with embedded install and uninstall scripts

## Download packages

Assets are attached to the project release.

- Linux package: latest release asset with prefix `aegisos-linux-`
- macOS package: latest release asset with prefix `aegisos-macos-`
- Windows package: latest release asset with prefix `aegisos-windows-`

Direct links are listed on the GitHub Pages demo site.

## Demo site

The live demo page is published with GitHub Pages from this repository and summarizes all platform functionality.

## Notes

This repository publishes package artifacts and a static demo experience. The full backend runtime is distributed in the attached installers and must run on a target host for live behavior.

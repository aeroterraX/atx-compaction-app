# ATX Compaction Field App

AeroTerraX Land Solutions — Soil Compaction Field Data Entry Tool

## Overview

A mobile-optimized web app for logging GPS-referenced soil compaction data in the field using the Agratronix penetrometer (ASAE S313.3). Exports QGIS-ready CSV directly to Google Drive.

## Features

- Survey header with auto-generated Survey ID
- Tip selection test block with manufacturer guidance
- PSI entry at 3", 6", 9", 12", 15", 18" depths with live color coding
- Auto-saves to browser local storage after every point
- Session resume on reopen
- Export CSV directly to Google Drive (Field Data / ATX Field Compaction Surveys)
- Local CSV and JSON backup export options

## Deployment

Hosted on GitHub Pages at: https://aeroterrax.github.io/atx-compaction-app

## Setup

1. Clone this repository
2. Enable GitHub Pages in repository Settings → Pages → Source: main branch / root
3. No build step required — single static HTML file

## Google Drive Integration

Requires authorization on first use. Click "Connect Drive" in the app header and sign in with your AeroTerraX Google account. Authorization persists for the session.

Files are saved to: `My Drive / Field Data / ATX Field Compaction Surveys`

Folders are created automatically if they do not exist.

## Document References

- ATX-SOP-SC-001: Soil Compaction Data Mapping QGIS Workflow Guide
- ATX-FRM-SC-001: Compaction Field Worksheet
- Agratronix Soil Compaction Tester Operators Manual (DOCU-M0116)

---

AeroTerraX Land Solutions | Smarter Land. Healthy Habitat.

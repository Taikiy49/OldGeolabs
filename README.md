<div align="center">
  <h1>OldGeolabs</h1>
  <p><strong>An archived React and Flask engineering-workspace prototype.</strong></p>
  <p><img alt="React" src="https://img.shields.io/badge/React-303840?style=flat-square" /> <img alt="Python" src="https://img.shields.io/badge/Python-303840?style=flat-square" /> <img alt="Archived" src="https://img.shields.io/badge/Status-Archived-78716c?style=flat-square" /></p>
</div>

---

## Overview

An earlier Geolabs software implementation, preserved as an archived project. It contains a React interface, a Flask backend, document-processing experiments, local databases, and generated application artifacts.

For the newer engineering workspace, see [GeoSoftware](https://github.com/Taikiy49/GeoSoftware).

## What’s inside

- A React frontend and Flask application.
- OCR, document parsing, text cleanup, and database-processing scripts.
- Historical application packaging and deployment artifacts.

## Getting started

This is a historical snapshot rather than a supported deployment. Inspect configuration, credentials, dependencies, and database content before executing it. The frontend scripts are `npm start` and `npm run build`; the backend entry point is `backend/app.py`, with its own `backend/requirements.txt`.

The frontend uses an older Create React App/OpenSSL compatibility setup. The original deployment configuration is historical and should not be assumed operational.

## Repository map

| Location | Purpose |
| --- | --- |
| [`package.json`](./package.json) | Historical React scripts and dependencies |
| [`backend/app.py`](./backend/app.py) | Flask application |
| [`backend/requirements.txt`](./backend/requirements.txt) | Backend dependencies |
| [`backend/clean_txt_process/`](./backend/clean_txt_process/) | Document text cleanup |

## Archive and data status

This repository remains archived. It contains committed account/employee databases, session artifacts, and internal documents. Those files are historical application data, not a sanitized sample dataset. Earlier commits also contain credentials; removing a credential from a current file does not revoke it or erase history. Review and rotate affected credentials before reuse.

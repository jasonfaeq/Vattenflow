# MDM-Vattenflow

An internal tool for managing WBS and Cost Center change requests between Controllers and Master Data Management (MDM) teams. Originally prototyped inside Vattenfall; this is a generic public version.

Live: https://mdm-vattenflow.vercel.app/

## Why

WBS and Cost Center requests usually run on Excel templates, emails and manual re-entry, which leads to inconsistent data, rework and delays. Vattenflow replaces that with a structured form, request tracking and a standardized Excel export.

## Features

**Controllers**
- Submit WBS and Cost Center requests with region and type specific fields
- Add multiple WBS elements, with validation
- Track status, comment and export to Excel

**Admins**
- Review, edit and comment on requests
- Change request status
- View usage metrics and basic analytics

## Screenshots

| | |
|---|---|
| ![My Requests](./Screenshots/Homepage.png) | ![Create Request](./Screenshots/Create-Request.png) |
| My Requests | Create Request |
| ![Request View](./Screenshots/Request-View.png) | ![Admin Panel](./Screenshots/Admin-Panel.png) |
| Request View and Export | Admin Panel |
| ![Admin Requests](./Screenshots/Admin-Panel%20Requests.png) | ![AI Analysis](./Screenshots/AI-Analysis.png) |
| Admin Request Management | AI Analytics (prototype) |

## Tech Stack

Next.js, Firebase Auth, Firestore, and a Python backend using xlwings for Excel export.

## Demo

Controller login: `johndoe@vattenflow.com` / `123456`. Message me for admin access.

Excel export needs a VM running xlwings to fill a macro-enabled template, so it does not work in the public version.

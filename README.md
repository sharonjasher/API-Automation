# API Automation

[![n8n](https://img.shields.io/badge/built%20with-n8n-3ebd70.svg)](https://n8n.io/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)

---

## Table of Contents

- [Project Overview](#project-overview)
- [Motivation](#motivation)
- [Features](#features)
- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Usage](#usage)
- [Workflow Details](#workflow-details)
- [License](#license)
- [Author & Contact](#author--contact)
- [Acknowledgements](#acknowledgements)

---

## Project Overview

**API Automation**  
An n8n workflow that automates multiple Google services and email tasks triggered manually. It sends an email, creates a folder in Google Drive, generates a Google Document inside that folder, and schedules a Google Calendar event with attendees.

---

## Motivation

Automating routine API tasks that involve email communication, file management, and calendar scheduling improves efficiency and reduces manual work. This workflow leverages n8n to orchestrate these common Google service operations in a seamless pipeline.

---

## Features

- Manual trigger to initiate the workflow on demand
- Sends a text email using Gmail
- Creates a new folder in Google Drive
- Creates a Google Document inside the specified Drive folder
- Creates a Google Calendar event with specified attendees and description
- Operates with proper authentication using OAuth2 credentials for all Google services

---

## Prerequisites

- n8n instance (Cloud or self-hosted)
- Google account with OAuth2 credentials for Drive, Docs, Calendar
- Gmail OAuth2 credentials for sending email
- Node.js installed if self-hosting n8n
- Modern browser to access n8n Editor UI

---




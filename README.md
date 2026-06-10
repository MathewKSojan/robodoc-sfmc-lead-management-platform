# RoboDoc - SFMC Lead Management & Journey API Integration

## Overview

RoboDoc is a Salesforce Marketing Cloud project that demonstrates an end-to-end lead management workflow for healthcare organizations interested in robotic surgery solutions.

The solution captures leads through CloudPages, triggers a Journey Builder journey using the REST API Fire Event endpoint, sends personalized emails, and allows users to update their information through a profile management page.

---

## Business Scenario

Healthcare institutions such as hospitals, clinics, and healthcare providers can request consultations regarding RoboDoc robotic surgery systems.

The solution automates lead capture, engagement, and profile management within Salesforce Marketing Cloud.

---

## Solution Components

### CloudPage A - Lead Capture Form

Captures:

* Contact Information
* Organization Information
* Clinical Interests
* Consultation Preferences
* Consent Information

---

### CloudPage B - Preprocessing Layer

Responsibilities:

* Receives form submissions
* Inserts/updates records in Data Extension
* Authenticates against Marketing Cloud REST API
* Triggers Journey Builder using Fire Event API
* Redirects users to Thank You page

---

### CloudPage C - Thank You Page

Displays confirmation after successful submission.

---

### Journey Builder

Entry Source:

* API Event

Activities:

* Send Personalized Email

---

### Email

Contains:

* Personalized subscriber information
* Call-To-Action button linking to profile update page

---

### CloudPage D - Profile Update Center

Features:

* Pre-populated subscriber information
* Editable fields
* Data Extension update functionality

---

## Technologies Used

* Salesforce Marketing Cloud
* CloudPages
* AMPScript
* Server-Side JavaScript (SSJS)
* Journey Builder
* REST API
* Fire Event API
* Data Extensions

---

## Architecture

Lead Capture Form
→ Preprocessing Page
→ Fire Event API
→ Journey Builder
→ Email Send
→ Profile Update Page
→ Data Extension Update

---

## Skills Demonstrated

* Marketing Cloud Development
* API Integrations
* Journey Builder Automation
* Dynamic Personalization
* Subscriber Data Management
* CloudPages Development
* AMPScript Development
* SSJS Development

---

## Disclaimer

All credentials, URLs, Event Definition Keys, and business identifiers have been replaced with placeholders for security purposes.

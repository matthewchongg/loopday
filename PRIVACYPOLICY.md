# Privacy Policy for LoopDay

**Effective Date:** November 1, 2026  
**Last Updated:** November 1, 2026

## 1. Overview
**LoopDay** ("the Add-on") is an automated Google Workspace Add-on built to assist university students in extracting academic deadlines, coursework assignments, and class schedule updates from incoming emails and synchronizing them into Google Calendar. 

We respect your privacy. This policy details what data is processed, how it is handled, and your rights regarding your personal information.

---

## 2. Information We Process
LoopDay operates entirely within your personal Google Workspace environment. The Add-on processes:

* **Email Content:** Unread email messages matching your specified sender filters (e.g., Canvas, Moodle, university notification domains) to parse coursework titles, due dates, description details, and class updates.
* **Calendar Data:** Existing Google Calendar event titles and time ranges strictly to check for duplicate entries or update existing rescheduled events in-place.
* **User Configuration Settings:** Stored parameters including your chosen Google Calendar ID, custom email search filters, service status toggles (Active/Snoozed), and your personal Google Gemini API Key.

---

## 3. How Information Is Used
Your data is processed strictly for the core functionality of the Add-on:
* Parsing academic event details using Google’s Gemini API endpoints.
* Creating and updating events within your selected Google Calendar.
* Ensuring duplicate events are not created across your schedule.

---

## 4. Data Storage & Security
* **No External Data Collection:** LoopDay **does not** collect, store, or transmit your personal emails, calendar data, or setup credentials to any third-party external databases or servers managed by the developer.
* **Local Workspace Storage:** User settings (such as your Gemini API Key and email filters) are stored securely inside your personal Google Account using Google Apps Script `PropertiesService`.
* **API Encryption:** Data sent to Google Gemini REST endpoints for event extraction is encrypted in transit via standard HTTPS/TLS protocols.

---

## 5. Third-Party Services
LoopDay integrates with the following Google Cloud and AI services:
* **Google Apps Script:** Execution environment for sidebar cards and background triggers.
* **Google Workspace APIs:** Gmail API, Google Calendar API, and PropertiesService.
* **Google Gemini API:** Used strictly to analyze email text and convert unformatted text into structured event JSON objects. 

> **Note:** Your Gemini API usage is governed by your own Google AI Studio agreement and API terms.

---

## 6. User Control & Data Retention
* **Service Controls:** You can pause background processing at any time using the "Auto-Sync Status" toggle within the Add-on settings.
* **Data Deletion:** Uninstalling the Add-on revokes all OAuth permissions instantly. You can clear stored configuration settings by removing the add-on or resetting properties within the sidebar.

---

## 7. Contact Information
If you have questions regarding this Privacy Policy or the security of the application, please reach out via our open GitHub repository issues page.

# CanusLupus – Forensic Dossier on Google AI Studio & Gemini Interactions API

This repository documents reproducible forensic evidence demonstrating that Google AI Studio and the Gemini Interactions API do not execute backend data deletion, even when users explicitly request it. The findings show persistent storage of “deleted” interactions, violations of documented TTL guarantees, and fully automated compliance workflows without human oversight.

## Contents
- Forensic PDFs (IssueTracker evidence)
- Video evidence (YouTube)
- Archived documentation (archive.ph, web.archive.org)
- Interactions API official docs
- Technical analysis of Google AI Studio deletion workflow
- GDPR Article 17 & 22 legal framework

## Key Findings
- Restored `.json` pointers in Google Drive instantly resurrect full conversations from Google’s backend, proving no physical deletion occurred.
- The AI Studio “Delete” action only removes the client-side pointer; no cascading backend purge is executed.
- The documented 1‑day TTL for Free Tier interactions is not enforced in practice.
- All compliance and support channels (IssueTracker, Buganizer, DPO requests) are handled exclusively by automated bots, violating GDPR Article 22.

## Evidence Links
- IssueTracker: https://issuetracker.google.com/issues/557281747
- Google AI Developers Forum threads
- Forensic verification videos
- Archived documentation and screenshots

## Purpose
The goal of this repository is to consolidate technical and legal evidence, inform developers, and support upcoming GDPR Article 79 civil proceedings requiring court‑ordered discovery of Google’s backend logs and audit trails.

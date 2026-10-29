# Lead Management Automation - Salesforce Flow

## Problem
Sales teams waste time manually qualifying leads, assigning them to the wrong queues, and following up without consistent communication. This project automates the entire lead intake process inside Salesforce.

## Features
- Screen Flow with 8 qualification steps and decision branches
- Auto-assigns lead to 1 of 5 queues based on geography
- Sends confirmation email on submission using custom email templates
- Validation rules enforce 98% data completeness
- Reports and dashboard for lead pipeline visibility

## Tech Stack
Salesforce Flow Builder | Email Templates | Validation Rules | Reports & Dashboards


## What I Learned
Building the 7-decision Screen Flow was the hardest part - getting the branching logic right for 5 different queue assignments took several iterations. I learned how to use fault paths in Flow to handle errors gracefully. Connecting validation rules with Flow conditions taught me how both layers work together to enforce data quality.
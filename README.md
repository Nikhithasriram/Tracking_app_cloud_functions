# Firebase Cloud Functions For PD Tracker

Backend cloud functions for the Peritoneal Dialysis Tracker app, providing server-side operations for the Flutter frontend.

## Overview

This directory contains Firebase Cloud Functions that handle backend operations for the PD tracker application. These functions are automatically deployed to Google Cloud and are called from the Flutter app.

## Functions

### `deleteUserAndData`
Handles complete user account deletion including all associated data.

**Purpose:**
- Deletes user authentication account
- Removes all user data from Firestore
- Removes all subcollections and documents


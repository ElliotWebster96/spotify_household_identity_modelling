Spotify Household Identity Resolution 🎧
Executive Summary
This project addresses a core challenge in streaming analytics: Account Sharing & Persona De-averaging. When multiple users share a single Spotify account, recommendation engines become "polluted." This project develops a machine learning pipeline to distinguish between multiple users (User A vs. User B) using behavioral biometrics and temporal fingerprints, specifically designed to function in the absence of hardware-level Device IDs.

The Problem Statement
Persona De-averaging: Accurately separate listening sessions of two distinct users to ensure personalized recommendation integrity.

Identity Resolution: Identify "Identity Collisions" (concurrent or geographically distinct usage) to drive conversion from Individual to Duo/Family plans.

Data Architecture
The project utilizes the Spotify Extended Streaming History (JSON), processed into a structured feature store.

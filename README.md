# Xophz Treasure Map

> **Category:** Compass Components · **Version:** 0.0.1

Gamified onboarding, discovery, and reward engine mapping user progression.

## Description

**Treasure Map** is a gamified discovery and onboarding engine within the COMPASS platform. It visualizes the user's journey through YouMeOS, rewarding them for embracing platform features (such as configuring their Treasure Trove or connecting to the Noosphere). It integrates directly with the XP gamification system.

### Core Capabilities

- **Waypoints (Milestones)** – Listens to global COMPASS actions to unlock waypoints (e.g., "First Login", "Data Encrypted").
- **Reward Matrix** – Integrates with `xophz-compass-xp` to grant XP or digital assets upon reaching milestones.
- **Celestial Map UI** – A 3D/2.5D visual representation of progress using the platform's WebGL engine, bypassing flat walkthroughs.

## Requirements

- **Xophz COMPASS** parent plugin (active)
- **Xophz XP** gamification plugin (active)
- WordPress 5.8+, PHP 7.4+

## Status

🔴 **In Development** - Scaffolding complete. Defined within the Sovereign Unity architecture. Awaiting WebGL map integration.

## Installation

1. Ensure **Xophz COMPASS** is installed and active.
2. Upload `xophz-compass-treasure-map` to `/wp-content/plugins/`.
3. Activate through the Plugins menu.
4. Access via the My Compass dashboard → **Treasure Map**.

## Frontend Routes

| Route | View | Description |
|---|---|---|
| `/treasure-map` | Map View | Visual map of completed waypoints and available quests |

## Changelog

### 0.0.1

- Initial scaffolding mapping the Sovereign Unity architectural goals.

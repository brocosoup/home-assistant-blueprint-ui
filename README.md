# Garage Cover Automation Blueprint

This repository contains a Home Assistant blueprint for automating a garage cover based on distance, temperature, lightning risk, and manual authorization.

## What this includes

- A blueprint file with a native Home Assistant configuration UI
- User-facing inputs for entities, thresholds, and cooldown behavior
- Installation notes for copying the blueprint into a Home Assistant configuration

## Blueprint location

Copy the blueprint into your Home Assistant config folder:

- Source: blueprints/automation/brocosoup/garage_cover_automation.yaml
- Target: /config/blueprints/automation/brocosoup/garage_cover_automation.yaml

## Notes on the UI

The configuration form is rendered directly in Home Assistant because the blueprint uses the input block with selectors such as entity, select, and number. That means users configure the automation from the Home Assistant UI instead of from a separate web app.

## Quick start

1. Copy the blueprint file into your Home Assistant config directory.
2. Reload automations or restart Home Assistant.
3. Create a new automation from the blueprint.
4. Fill in the form fields shown in the Home Assistant UI.

[![Open your Home Assistant instance and show the blueprint import dialog with a specific blueprint pre-filled.](https://my.home-assistant.io/badges/blueprint_import.svg)](https://my.home-assistant.io/redirect/blueprint_import/?blueprint_url=https%3A%2F%2Fraw.githubusercontent.com%2FMrSmits%2FINNR_RC210_Blueprint%2Frefs%2Fheads%2Fmain%2FINNR_RC210_blueprint.yaml)

# INNR_RC210_Blueprint

This blueprint creates an automation that translates the ZHA events which are sent by the INNR RC210 smart button (https://www.innr.com/nl/product/smart-button/) to actions.

Credits for this blueprint go to the original creator of the blueprint for the RC250 remote. Thank you!
For the RC250 remote see this post:
https://community.home-assistant.io/t/innr-zigbee-remote-rc250-blueprint-with-three-modes-to-use-with-zha/796828?u=smitsmans

## Prerequisites

* The remote has to be paired with a Zigbee controller using the ZHA integration.
* Due to the use of modern syntax ('actions', 'triggers'), 2024.10 is the minimum HA core version supproted

## Configuration
Configuration should be as simple as:
1. Selecting the action type
2. Selecting the RC210 remote
3. Selecting or creating a helper
4. Select the lights that you want to affect
5. Configure the fixed action settings. You can configure 4 actions at the moment (On, Off, Long press, Double press)

---
title: Twitch
description: Instructions on how to integrate Twitch sensors into Home Assistant.
ha_category:
  - Social
ha_release: '0.10'
ha_iot_class: Cloud Polling
ha_domain: twitch
ha_platforms:
  - sensor
ha_integration_type: integration
ha_codeowners:
  - '@joostlek'
ha_config_flow: true
---

The Twitch integration will allow you to monitor [Twitch](https://www.twitch.tv/) channel status from within Home Assistant and setup automation based on the information.

## Get Twitch application credentials

Create a new app at "Register Your Application" in the [Twitch developer portal](https://dev.twitch.tv/console/apps). Then get the __Client ID__ and __Client secret__ for the new application.

{% include integrations/config_flow.md %}

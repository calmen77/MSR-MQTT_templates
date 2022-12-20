# MSR-mqtt_templates
MQTT templates for Multi-hub Reactor

# Installation
Download the desired yaml files or bundled zip archives and save them under reactor/config/mqtt_templates (no need to exctract the zip files), restart Reactor.

To update an existing template it's the same procedure.

# Configuration
To add an entity using the downloaded template please refer to https://reactor.toggledbits.com/docs/MQTTController/#easy-device-configuration-using-existing-template and supply the `topic:` and template name (listed below) in the `uses_template:` key.

All *zigbee2mqtt_** templates have an optional key named `prefix:` that you can add and supply a value for if your Zigbee2MQTT prefix is not the default *zigbee2mqtt*.

### Zigbee2MQTT settings
mqtt_device.online requires `legacy_availability_payload: true` in Zigbee2MQTT devices availability settings.

# Templates
| Template name | Description | Capabilities | Additional info | Bundled in |
| --- | --- | --- | --- | --- |
| `zigbee2mqtt_ikea_tradfri_control_outlet` | Zigbee2MQTT template for [IKEA TRADFRI control outlet](https://www.zigbee2mqtt.io/devices/E1603_E1702_E1708.html#ikea-e1603%252Fe1702%252Fe1708) | ***_power_switch_***, value_sensor, string_sensor, toggle | - | zigbee2mqtt_ikea_tradfri.zip |
| `zigbee2mqtt_ikea_tradfri_light_bulb` | Zigbee2MQTT template for [IKEA TRADFRI LED bulb E26/E27 806 lumen, dimmable, warm white](https://www.zigbee2mqtt.io/devices/LED1836G9.html#ikea-led1836g9) | ***_power_switch_***, dimming, light_effect, value_sensor, string_sensor, toggle | Possible values for light_effect.start are: *blink, breathe, okay, channel_change, finish_effect, stop_effect*. Current light_effect is not readable from device. | zigbee2mqtt_ikea_tradfri.zip |
| `zigbee2mqtt_ikea_tradfri_light_bulb_color_temp` | Zigbee2MQTT template for [IKEA TRADFRI bulb E12/E14/E17 WS 450/470/440 lumen, dimmable, white spectrum, opal white](https://www.zigbee2mqtt.io/devices/LED1903C5_LED1835C6.html#ikea-led1903c5%252Fled1835c6) | ***_power_switch_***, dimming, color_temperature, light_effect, value_sensor, string_sensor, toggle | Possible values for light_effect.start are: *blink, breathe, okay, channel_change, finish_effect, stop_effect*. Current light_effect is not readable from device. | zigbee2mqtt_ikea_tradfri.zip |
| `zigbee2mqtt_tuya_smart_plug_power_monitoring` | Zigbee2MQTT template for [IKEA TRADFRI bulb E12/E14/E17 WS 450/470/440 lumen, dimmable, white spectrum, opal white](https://www.zigbee2mqtt.io/devices/LED1903C5_LED1835C6.html#ikea-led1903c5%252Fled1835c6) | ***_power_switch_***, dimming, color_temperature, light_effect, value_sensor, string_sensor, toggle | Possible values for light_effect.start are: *blink, breathe, okay, channel_change, finish_effect, stop_effect*. Current light_effect is not readable from device. | zigbee2mqtt_ikea_tradfri.zip |
| `zigbee2mqtt_xiaomi_aqara_mini_switch` | List all *new or modified* files |
| `zigbee2mqtt_xiaomi_aqara_occupancy_illuminance` | Zigbee2MQTT template for [IKEA TRADFRI bulb E12/E14/E17 WS 450/470/440 lumen, dimmable, white spectrum, opal white](https://www.zigbee2mqtt.io/devices/LED1903C5_LED1835C6.html#ikea-led1903c5%252Fled1835c6) | ***_power_switch_***, dimming, color_temperature, light_effect, value_sensor, string_sensor, toggle | Possible values for light_effect.start are: *blink, breathe, okay, channel_change, finish_effect, stop_effect*. Current light_effect is not readable from device. | zigbee2mqtt_ikea_tradfri.zip |
| `zigbee2mqtt_xiaomi_aqara_illuminance_occupancy` | Zigbee2MQTT template for [IKEA TRADFRI bulb E12/E14/E17 WS 450/470/440 lumen, dimmable, white spectrum, opal white](https://www.zigbee2mqtt.io/devices/LED1903C5_LED1835C6.html#ikea-led1903c5%252Fled1835c6) | ***_power_switch_***, dimming, color_temperature, light_effect, value_sensor, string_sensor, toggle | Possible values for light_effect.start are: *blink, breathe, okay, channel_change, finish_effect, stop_effect*. Current light_effect is not readable from device. | zigbee2mqtt_ikea_tradfri.zip |
| `zigbee2mqtt_xiaomi_aqara_temperature_humidity` | Zigbee2MQTT template for [IKEA TRADFRI bulb E12/E14/E17 WS 450/470/440 lumen, dimmable, white spectrum, opal white](https://www.zigbee2mqtt.io/devices/LED1903C5_LED1835C6.html#ikea-led1903c5%252Fled1835c6) | ***_power_switch_***, dimming, color_temperature, light_effect, value_sensor, string_sensor, toggle | Possible values for light_effect.start are: *blink, breathe, okay, channel_change, finish_effect, stop_effect*. Current light_effect is not readable from device. | zigbee2mqtt_ikea_tradfri.zip |
| `zigbee2mqtt_xiaomi_aqara_humidity_temperature` | Zigbee2MQTT template for [IKEA TRADFRI bulb E12/E14/E17 WS 450/470/440 lumen, dimmable, white spectrum, opal white](https://www.zigbee2mqtt.io/devices/LED1903C5_LED1835C6.html#ikea-led1903c5%252Fled1835c6) | ***_power_switch_***, dimming, color_temperature, light_effect, value_sensor, string_sensor, toggle | Possible values for light_effect.start are: *blink, breathe, okay, channel_change, finish_effect, stop_effect*. Current light_effect is not readable from device. | zigbee2mqtt_ikea_tradfri.zip |

# Support
Support is provided by @Crille through https://smarthome.community/

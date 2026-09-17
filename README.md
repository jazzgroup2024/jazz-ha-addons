# Jazz Custom Zigbee2MQTT Add-ons (Multi-Instance 01-30)

Этот репозиторий содержит **30 полноценных независимых копий Zigbee2MQTT** для Home Assistant.

Каждый аддон:
- Имеет цветные иконки (`icon.png`, `logo.png`);
- Создает свою собственную папку конфигурации: `/config/zigbee2mqtt_01` ... `/config/zigbee2mqtt_30`;
- Имеет отдельный Ingress Web UI и порты (`8091` ... `8120`);
- Привязан к Mosquitto MQTT и аппаратному порту;
- Обновляется автоматически.

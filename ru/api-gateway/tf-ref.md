---
title: Справочник {{ TF }} для {{ api-gw-full-name }}
description: На этой странице приведен справочник ресурсов и источников данных провайдера {{ TF }}, которые поддерживаются для сервиса {{ api-gw-name }}.
---

# Справочник {{ TF }} для {{ api-gw-full-name }}

{% include [terraform-ref-intro](../_includes/terraform-ref-intro.md) %}

## Ресурсы {#resources}

Для {{ api-gw-name }} поддерживаются следующие ресурсы провайдера {{ TF }}:

| **Ресурс {{ TF }}** | **Ресурс {{ yandex-cloud }}** |
| --- | --- |
| [yandex_api_gateway]({{ tf-provider-resources-link }}/api_gateway) | [API-шлюз](./concepts/index.md) |

## Источники данных {#data-sources}

Для {{ api-gw-name }} поддерживаются следующие источники данных провайдера {{ TF }}:

| **Источник данных {{ TF }}** | **Описание** |
| --- | --- |
| [yandex_api_gateway]({{ tf-provider-datasources-link }}/api_gateway) | Информация об [API-шлюзе](./concepts/index.md) |
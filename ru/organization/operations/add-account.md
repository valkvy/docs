# Добавить пользователя

## Пригласить пользователя Яндекса{#add-or-invite-user-account}

Если у сотрудников компании есть аккаунты на Яндексе (например, `{{login-example}}`), они могут использовать эти аккаунты для доступа к сервисам {{yandex-cloud}}, подключенным к вашей организации.

{% note info %}

Приглашать пользователей может администратор (роль `organization-manager.admin`) или владелец (роль `organization-manager.organizations.owner`) организации. Как назначить роль пользователю, читайте в разделе [Роли](../security/index.md#admin).

{% endnote %}

Чтобы пригласить сотрудников в организацию:

{% include [invite-user](../../_includes/organization/invite-user.md) %}

## Добавить федеративных пользователей {#add-user-sso}

Если при [настройке федерации](../concepts/add-federation.md#federation-usage) вы не включили опцию **{{ ui-key.yacloud_org.entity.federation.field.autocreateUsers }}**, федеративных пользователей нужно добавить в организацию вручную.

Для этого вам необходимо знать Name ID пользователей, которые возвращает сервер поставщика удостоверений (IdP) вместе с ответом об успешной аутентификации. Обычно это основной email пользователя. Если вы не знаете, что возвращает сервер в качестве Name ID, обратитесь к администратору, который настраивал аутентификацию в вашей федерации.

Чтобы добавить пользователей федерации в организацию:

{% include [add-federateduser](../../_includes/organization/add-federateduser.md) %}

#### Что дальше {#what-is-next}

* [Назначьте роли добавленным пользователям](../../iam/operations/roles/grant.md).
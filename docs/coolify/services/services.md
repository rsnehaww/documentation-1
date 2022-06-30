---
sidebar_position: 1
---

# Services

Services are popular open-sourced and self-hostable applications provided as a service for you.

You can suggest new services by [opening an issue on GitHub](https://github.com/coollabsio/coolify/issues/new).

## Types of services supported

- [WordPress](./wordpress)
- [Ghost](https://ghost.org)
- [Plausible Analytics](./plausible-analytics)
- [NocoDB](https://nocodb.com)
- [VSCode Server](https://github.com/cdr/code-server)
- [MinIO](https://min.io)
- [VaultWarden](https://github.com/dani-garcia/vaultwarden)
- [LanguageTool](https://languagetool.org)
- [pltext]([https://pltext.com/]
- [n8n](https://n8n.io)
- [Uptime Kuma](https://github.com/louislam/uptime-kuma)
- [MeiliSearch](https://github.com/meilisearch/meilisearch)
- [Umami](https://github.com/mikecao/umami)
- [Fider](https://fider.io)
- [Hasura](https://hasura.io)

:::tip
Some applications could take several minutes to start up.
:::

## Requirements
Each service requires a specific amount of CPU / memory/storage. Choose your services based on their requirements.

## Exposed Port
You can expose your application to a port on the host system.

> Useful if you would like to use your own reverse proxy or tunnel and also in development mode of Coolify. 

## Persistency
All data are persistent. That means, if you stop a service, all your data persist on a Docker Volume. If you stop/start a service, you will keep your data as-is.

## Logs
You can check the runtime logs of your services.

## Secrets
There are some predefined secrets on the frontend, that are generated automatically (like passwords, users.) or you can fill manually. If you need any futher environment variable, you can define them in the secrets tab.

## Update service to the latest version
If you stop/start a service, the latest docker image will be pulled for the selected image tag.

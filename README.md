# Matrix Chart

A Helm chart for deploying a Matrix homeserver stack in Kubernetes.

## Features

- Latest version of Synapse
- (Optional) Latest version of Riot Web
- (Optional) Choice of lightweight Exim relay or external mail server for email notifications
- (Optional) Coturn TURN server for VoIP calls (latest version!)
- (Optional) PostgreSQL cluster via stable/postgresql chart
- (Optional) [matrix-org/matrix-appservice-irc](https://github.com/matrix-org/matrix-appservice-irc) IRC bridge
- (Optional) [tulir/mautrix-whatsapp](https://github.com/tulir/mautrix-whatsapp) WhatsApp bridge
- (Optional) [Half-Shot/matrix-appservice-discord](https://github.com/matrix-org/matrix-appservice-discord) Discord bridge
- (Optional) SAML integration (eg, Keycloak)
- Fully configurable via values.yaml
- Ingress definition for federated Synapse and Riot

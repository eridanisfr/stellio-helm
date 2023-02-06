# stellio-helm
to hold an helm chart to deploy stellio context-broker on kubernetes

stellio is composed of the following components :
- a TimescaleDB PostgreeSQL based database server
- 2 backend services (search-service, subscription-service)
- a front api gateway
- and a kafka sitting between back-end services

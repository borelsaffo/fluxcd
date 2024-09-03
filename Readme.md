

# Définitions



helm-controller

    Ce contrôleur gère les déploiements de chartes Helm dans votre cluster Kubernetes. Il s'occupe d'installer, mettre à jour et surveiller les chartes Helm définies dans vos manifestes Flux.

kustomize-controller 

    Ce contrôleur applique les configurations définies avec Kustomize dans votre cluster Kubernetes. Kustomize est un outil qui permet de personnaliser les configurations Kubernetes sans dupliquer les manifestes YAML.

notification-controller

    Ce contrôleur gère les notifications et alertes dans l'écosystème Flux. Il peut être configuré pour envoyer des notifications vers des systèmes de messagerie (comme Slack, Microsoft Teams, etc.) lorsque des événements spécifiques se produisent dans votre cluster (par exemple, lorsqu'un déploiement réussit ou échoue).

source-controller

    gère les sources de configurations, telles que les dépôts Git ou les archives Helm, que Flux utilise pour déployer des applications. Il surveille ces sources pour détecter les changements et déclencher des déploiements en conséquence.
 

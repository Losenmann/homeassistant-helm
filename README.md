# homeassistant-helm
## Install
```
    helm repo add homeassistant https://losenmann.github.io/homeassistant-helm
    helm repo update
    helm upgrade --install homeassistant https://losenmann.github.io/homeassistant-helm -n smarthome --create-namespace
```
## Upgrade
```
    helm upgrade --install homeassistant https://losenmann.github.io/homeassistant-helm
```
## Delete
```
    helm uninstall homeassistant -n smarthome
```
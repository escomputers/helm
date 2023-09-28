1. helm package homeassistant
2. move package into "helm" repository
3. helm repo index helm/ --url https://escomputers.github.io/helm/
4. helm repo add helm/ https://escomputers.github.io/helm/
5. helm install helm/homeassistant --name=homeassistant
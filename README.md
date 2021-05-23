# Cuebook Helm Charts

### Adding cuebook helm repo
```bash
helm repo add https://cuebook.github.io/helm-charts/
helm repo update
```

### Installing Cuelake
Installing cuelake with default configuration:
```bash
helm install cuelake cuelake/cuelake
```

For installing cuelake with custom configuration download the values.yaml file for cuelake.
```bash
wget https://raw.githubusercontent.com/cuebook/helm-charts/main/helm-chart-sources/cuelake/values.yaml
```
Edit the file and install Cuelake:
```bash
helm install cuelake cuelake/cuelake -f values.yaml
```

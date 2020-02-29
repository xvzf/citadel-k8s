traefik:
	helm upgrade --install traefik --namespace kube-system -f values.yaml stable/traefik
	kubectl apply -f ipv6.yaml


.PHONY: build
build:
	docker build -t jamesharr/ubuntu-netshoot:latest .

.PHONY: push
push:
	docker push jamesharr/ubuntu-netshoot:latest

.PHONY: start-daemonset
start-daemonset:
	kubectl apply -f kube-daemonset.yaml

.PHONY: delete-daemonset
delete-daemonset:
	kubectl delete -f kube-daemonset.yaml

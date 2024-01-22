# argocd-test-repo
Testing argo cd

#commands
helm install helios-test-application-BE app1/ -f app1/values-dev.yaml -n development
helm install helios-test-application-sqs app1/ -f app1/values-dev.yaml -n development
helm install helios-test-application app1/ -f app1/values-prod.yaml -n production
helm ls --all-namespaces
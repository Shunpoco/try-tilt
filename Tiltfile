docker_build('example-go-image', '.', dockerfile='deployment/Dockerfile')
k8s_yaml('deployment/deployment.yaml')
k8s_resource('example-go', port_forwards=8000)

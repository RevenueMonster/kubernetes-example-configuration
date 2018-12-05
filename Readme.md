## Create Namespace
`kubectl apply -f namespace/`

## Create Deployment Image
`kubectl apply -f deployment/`

## Create Service
`kubectl apply -f service/`

## Create Ingress for Routing
`kubectl apply -f ingress/`

## Update New Docker Image for Deployment
`kubectl set image deployment rm-service rm-service={docker_image_path} --namespace=dev`

## Create Config Map
`kubectl apply -f config-map/`

## Create Secret
`kubectl apply -f secret/`

## Create CronJob
`kubectl apply -f cronjob/`

## Kubectl Command Line CheatSheet
`https://kubernetes.io/docs/reference/kubectl/cheatsheet/#creating-objects`
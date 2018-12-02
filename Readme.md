## Deployment Image
`kubectl apply -f deployment/rm-service.yaml`

## Update Deployment Image
`kubectl set image deployment rm-service rm-service={docker_image_path} --namespace=dev`

## Deployment Service
`kubectl apply -f service/rm-service.yaml`

## Deployment Ingress
`kubectl apply -f ingress/dev.yaml`
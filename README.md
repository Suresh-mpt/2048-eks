prerequisite for deploying EKS

    1) kubectl install
    2) eks cli install
    3) AWS cli
    
Eks cluster has been created through cli

![cluster created](https://github.com/Suresh-mpt/2048-eks/assets/173250817/5665a6cd-f7e7-47e1-a179-e7e0d9682e4b)

cluster is availabe on aws UI

![UI cluster](https://github.com/Suresh-mpt/2048-eks/assets/173250817/2f1578f7-4d53-4d31-9d9f-b286823a2812)

Fargate profile created 

![fargate prof](https://github.com/Suresh-mpt/2048-eks/assets/173250817/00ffb79c-11f5-4c04-9b6e-0d6c8f5cc812)

creating all yaml files ( deploy,svc,namepace,ingress resource )

![yaml creation](https://github.com/Suresh-mpt/2048-eks/assets/173250817/9cc74da6-db55-4d5d-a5f4-f09ccf165563)

Configuring IAM OIDC provider ( The k8s pods talks to some AWS service (ALB) )

![oidc provider](https://github.com/Suresh-mpt/2048-eks/assets/173250817/72987775-4d46-4755-9819-adb33a88714b)

Creating IAM policy

![policy json](https://github.com/Suresh-mpt/2048-eks/assets/173250817/c968a9c6-648a-42bf-86c3-62df7936a4d8)

Creating service account and attach the role to the service account of the pod

![service acc](https://github.com/Suresh-mpt/2048-eks/assets/173250817/d1485521-715a-4a1e-a0ad-510e14dee511)

Creating ingress controller and still not yet

![no ing controller](https://github.com/Suresh-mpt/2048-eks/assets/173250817/b0b688df-c193-44e5-8a4e-7cafb7562d14)

Helm install and helm chart creating actuall controller

![helm install](https://github.com/Suresh-mpt/2048-eks/assets/173250817/33d63256-1b14-4116-aa88-491bb91525ca)

alb controller and alb installed 

![alb get installed](https://github.com/Suresh-mpt/2048-eks/assets/173250817/9976984b-551b-49e6-b846-8defac73eeb8)

loadbalancer visible on aws ui

![alb](https://github.com/Suresh-mpt/2048-eks/assets/173250817/15927c13-a4e2-46a5-8b71-d3daec2fa988)

Search with load balancer url

![DNS url](https://github.com/Suresh-mpt/2048-eks/assets/173250817/b6cec462-d28d-4024-8586-c40cc65cf239)

2048-game successfully deployed on EKS and lets play !!!

![2048 running](https://github.com/Suresh-mpt/2048-eks/assets/173250817/76795316-f27b-475b-a3b0-3c6bfec0003d)














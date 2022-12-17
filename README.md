# Docker examples

## Environments
* `OS Linux`
* `https://docs.docker.com/engine/install/`

## Structure
```
.
├── 01_hello-world-docker
│   ├── 01_01_empty
│   │   ├── Dockerfile
│   │   ├── hello.sh
│   │   └── README.md
│   ├── 01_02_with_app
│   │   ├── Dockerfile
│   │   ├── hello.sh
│   │   └── README.md
│   ├── 01_03_push
│   │   ├── Dockerfile
│   │   ├── hello.sh
│   │   └── README.md
│   ├── 01_04_pid
│   │   ├── Dockerfile
│   │   ├── hello.sh
│   │   └── README.md
│   └── 01_05_memory
│       ├── Dockerfile
│       ├── hello.sh
│       └── README.md
├── 02_api_example
│   ├── app.py
│   ├── data.csv
│   ├── Dockerfile
│   ├── make_request.py
│   ├── README.md
│   └── requirements.txt
└─── 03_kubernetes_manifests
    ├── configmap-env.yaml
    ├── configmap-ml.yaml
    ├── env_0.yaml
    ├── env_1.yaml
    ├── env_config_map.yaml
    ├── env-job.yaml
    ├── fastapi1.yaml
    ├── fastapi-config-map.yaml
    ├── fastapi-deployment.yaml
    ├── fastapi-health.yaml
    ├── fastapi-replicaset.yaml
    ├── fastapi-resources.yaml
    ├── fastapi-service.yaml
    ├── fastapi.yaml
    ├── http-liveness.yaml
    └── README.md
```


# pykube
Sandbox python application for python lab

## Testing

```bash
docker build -t pykube .
docker run -d --name pykubecontainer -p 80:80 pykube 
```

- Visit `http://127.0.0.1` for hello world
- Visit `/docs` for doc

## Deployment

https://fastapi.tiangolo.com/deployment/docker/

TODO: Setup CICD with Jenkins / GitLab etc.
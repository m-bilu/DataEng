## Notes
Link: https://www.youtube.com/watch?v=fqMOX6JJhGo


#### Docker Overview:
- Docker containers are similar to virtual envs
- containers share same kernel (windows, linux), have individual OS (ubuntu) + apps running + env vars + directories + allocated resources
- allows for abstraction of diff apps and what they need to run, security, etc.
- much more lightweight than virtual machines due to shared kernel
- Containers (just like vms) made from pre-determined images from dockerhub

#### Basic Commands:
- will fill later


#### Run Extensions:
- Tag: tag required version of image for ur container
- STDIN: -it collects STDIN and prints code
- Port Mapping to docker root machine's available port
- Volume Mapping for databases to folder on docker root


#### ENV Vars in Docker
- Your containerized app may use environment variables as constants
- Good practice to keep them out of code
- Container, like Virtual Env, will need it's own initialization of env vars, just like its own directory/assigned resources/etc.
- Hence, pass em as key-val pairs after docker run -e indicator
- Using docker inspect container-name, we find env variables under Env json object


#### Creating ur own image
- As opposed to taking image from dockerhub
- Images are created of apps that can run on CLI, not of frameworks, libraries, etc.
- 


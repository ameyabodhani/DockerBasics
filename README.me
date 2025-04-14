# 🐳 Docker Cheat Sheet

A comprehensive reference for installing, running, and managing Docker images, containers, volumes, Swarm, Compose, and more.

---

## 🛠️ Installation

```bash
# Update the apt cache
sudo apt-get update

# Install prerequisites
sudo apt-get install ca-certificates curl

# Create keyrings directory
sudo install -m 0755 -d /etc/apt/keyrings

# Download the GPG key
sudo curl -fsSL https://download.docker.com/linux/ubuntu/gpg -o /etc/apt/keyrings/docker.asc
sudo chmod a+r /etc/apt/keyrings/docker.asc

# Add Docker’s official repository
echo   "deb [arch=$(dpkg --print-architecture) signed-by=/etc/apt/keyrings/docker.asc] https://download.docker.com/linux/ubuntu   $(. /etc/os-release && echo "$VERSION_CODENAME") stable" |   sudo tee /etc/apt/sources.list.d/docker.list > /dev/null

# Update the apt cache again
sudo apt-get update

# Install Docker Engine
sudo apt-get install docker-ce docker-ce-cli containerd.io docker-buildx-plugin docker-compose-plugin

# Check Docker service
sudo systemctl status docker

# Start and enable Docker service
sudo systemctl start docker
sudo systemctl enable docker

# Add current user to docker group
sudo usermod -aG docker $USER

# Restart the machine and verify Docker
docker version
```

---

## 📦 Image Commands

```bash
# List all images
docker image ls

# Pull an image
docker image pull hello-world

# Remove an image
docker image rm hello-world

# Inspect an image
docker image inspect hello-world
```

---

## 📦 Container Commands

```bash
# List running containers
docker container ls

# List all containers
docker container ls -a

# Create a container
docker container create hello-world

# Inspect a container
docker container inspect <container_id_or_name>

# Start/Stop/Remove containers
docker container start <id_or_name>
docker container stop <id_or_name>
docker container rm <id_or_name>
docker container rm --force <id_or_name>
```

---

## ▶️ Run Containers

```bash
# Run a container (new each time)
docker container run <image>

# Set container name
docker container run --name <name> <image>

# Run in detached + interactive mode
docker container run --name <name> -itd <image>

# Port forwarding
docker container run --name myhttpd -itd -p 8080:80 httpd

# Run MySQL with environment variable
docker container run --name mysql -itd -p 3306:3306 -e MYSQL_ROOT_PASSWORD=root mysql

# Run command inside container
docker container exec myhttpd date

# Access container shell
docker container exec -it myhttpd bash

# View container logs
docker container logs mysql
```

---

## 📁 Volumes

```bash
# List volumes
docker volume ls

# Remove unused volumes
docker volume prune

# Create a volume
docker volume create myvolume

# Inspect and remove volume
docker volume inspect myvolume
docker volume rm myvolume

# Attach volume to container
docker container run --name mysql -itd -p 3306:3306 -v myvolume:/var/lib/mysql -e MYSQL_ROOT_PASSWORD=root mysql
```

---

## 🛠️ Dockerfile Basics

- `FROM` – Base image  
- `COPY` – Copy files into image  
- `WORKDIR` – Set working directory  
- `RUN` – Execute commands during build  
- `CMD` – Default command at container start  
- `EXPOSE` – Port to be exposed

```bash
# Build custom image
docker image build -t myimage .

# Tag image for Docker Hub
docker image tag myimage myuser/myimage

# Push to Docker Hub
docker login -u <username>
docker image push myuser/myimage

# Build for multiple architectures
docker buildx build --platform linux/amd64,linux/arm64 -t myimage .
```

---

## 🐝 Docker Swarm

```bash
# Check swarm status
docker system info | grep Swarm

# Initialize swarm
docker swarm init

# Leave swarm
docker swarm leave --force

# Get worker join token
docker swarm join-token worker
```

---

## 🧱 Docker Nodes

```bash
docker node ls                     # List nodes
docker node inspect <node_id>     # Inspect node
docker node rm <node_id>          # Remove node
docker node promote <id>          # Promote to manager
docker node demote <id>           # Demote to worker
```

---

## ⚙️ Docker Services

```bash
docker service ls                                       # List services
docker service create --name myservice httpd           # Create service
docker service create --replicas 5 --name httpd -p 8080:80 httpd
docker service ps <service>                            # List service tasks
docker service rm <service>                            # Remove service
watch -n 1 docker container ls                         # Watch containers
docker service scale myservice=10                      # Scale service
```

---

## 🧩 Docker Compose

- Used to manage multiple services during development.

```bash
docker compose ls               # List compose projects
docker compose build            # Build images
docker compose up -d           # Start containers
docker compose down            # Stop containers
docker compose down --rmi all  # Remove containers + images
```

---

## 🧱 Docker Stack (with Swarm)

```bash
docker stack ls                                           # List stacks
docker stack deploy --compose-file docker-stack.yaml myapp
docker stack rm myapp                                     # Remove stack
```

---

## 🧹 Misc

```bash
# Clean up system (stopped containers, dangling images, unused volumes/networks)
docker system prune -a
```

---

### ✅ Author

Ameya's Docker Guide – organized for clarity, speed, and practical use.

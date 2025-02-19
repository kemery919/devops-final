# Linux Docker install

sudo dnf config-manager --add-repo https://download.docker.com/linux/centos/docker-ce.repo

sudo dnf install -y docker-ce docker-ce-cli containerd.io docker-compose-plugin

sudo systemctl start docker

sudo systemctl enable docker


# Allow non-root user access

sudo usermod -aG docker $USER
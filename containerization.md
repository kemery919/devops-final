# Linux Docker install
sudo dnf config-manager --add-repo https://download.docker.com/linux/centos/docker-ce.rep
sudo dnf install -y docker-ce docker-ce-cli containerd.io docker-compose-plug
sudo systemctl start docker
sudo systemctl enable docker

# Allow non-root user access
sudo usermod -aG docker $USER
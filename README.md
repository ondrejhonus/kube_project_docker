# Installation
```
# Clone the repository to your computer
git clone https://github.com/ondrejhonus/kube_project_docker

# Enter the directory
cd kube_project_docker

# Create a virtual enviroment .venv
python -m venv .venv

# Activate the virtual enviroment
. .venv/bin/activate

# Install the requirements
pip install -r requirements.txt

# Build the container
docker build -t test .

# Run the docker container
docker run -p 5000:5000
```

### You can then create a github action and publish a docker container to use in Kubernetes
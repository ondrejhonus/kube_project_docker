# Installation
```
git clone https://github.com/ondrejhonus/kube_project_docker

cd kube_project_docker

python -m venv .venv

. .venv/bin/activate

pip install -r requirements.txt

docker build -t test .

docker run -p 5000:5000
```
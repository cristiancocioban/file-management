aws ecr get-login-password --region eu-central-1 | docker login --username AWS --password-stdin 637423311357.dkr.ecr.eu-central-1.amazonaws.com

docker tag app 637423311357.dkr.ecr.eu-central-1.amazonaws.com/app
docker push 637423311357.dkr.ecr.eu-central-1.amazonaws.com/app

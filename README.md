kubectl create secret docker-registry aws-ecr --docker-server=624783896224.dkr.ecr.us-east-1.amazonaws.com --docker-username=AWS --docker-password=$(aws ecr get-login-password)


 image: 624783896224.dkr.ecr.us-east-1.amazonaws.com/frontend
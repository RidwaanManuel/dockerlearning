# dockerlearning
Want to start documenting what I learn regarding docker 
for example this usefull command
docker run --entrypoint "" -v "$PWD":/var/task "public.ecr.aws/lambda/nodejs:14" /bin/sh -c "npm install aws-sdk; exit"

This can help when creating lambda function/layer and needing to install a module using a lambda container. Similar command can be used for python with pip install 

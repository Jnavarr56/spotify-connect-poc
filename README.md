
on mac:
chmod +x wait-for-it.sh 
git add wait-for-it.sh 
git commit
docker-compose up --build

on windows:
git add --chmod=+x -- entrypoint.sh
git commit
docker-compose up --build
# cloud_server

----------------
ssh-keygen -t rsa -b 4096 -C "g00u00@outlook.com"
eval $(ssh-agent -s)
ssh-add  ~/.ssh/id_rsa
cat  ~/.ssh/id_rsa.pub
echo "ssh -T git@github.com"
------------------
git init

git config user.name "g00u00"

git config user.email "g00u00@outlook.com"

git remote add origin git@github.com:g00u00/cloud_server.git

git pull origin main


====================

# root cat > stop.sh:

service tor stop

service transmission-daimond  stop

service cron  stop


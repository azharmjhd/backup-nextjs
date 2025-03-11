# backup-nextjs
pipelines

Config SSH GitLab CI/CD

ssh-keygen -t rsa -b 4096 -C "gitlab-ci"
cat ~/.ssh/id_rsa.pub

vi ~/.ssh/authorized_keys

add private key to GitLab CI/CD Variables:

open GitLab → Repository → CI/CD → Variables
add SSH_PRIVATE_KEY ( private key from server).


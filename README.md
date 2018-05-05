# my-dev-machine
Dev Machine Configuration using ansible 

# How to run Ansible playbook
$ ansible-playbook -K playbook.yml

$ ansible-playbook -K packages.yml


$ ./ngrok http -host-header="localhost:port" -subdomain=subdomain port
[exposing-localhost-to-the-internet-via-tunneling-using-ngrok](https://stackoverflow.com/questions/30535336/exposing-localhost-to-the-internet-via-tunneling-using-ngrok-http-error-400)

# How to run playbook without prompting for sudo password.
$ ansible-playbook sample.yml -vvv --become --vault-password-file=/samplepasswordfile
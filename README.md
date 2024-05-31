# GenAIMCQ
## Generative AI project to build mcq questions and answers and evaluate its difficulty level using the gpt-3.5-turbo and deployed locally using streamlit library

pip install ipykernel
conda create -p mcq python=3.8 -y

source activate ./mcq

pip list

git status

ls -a

conda install -p mcq ipykernel --update-deps --force-reinstall

git push -f origin main
   
pip install -r requirements.txt 

## Steps to deploy the strealit app

### first login to the AWS: https://aws.amazon.com/console/

### search about the EC2

### you need to config the UBUNTU Machine

### launch the instance

### update the machine:

### if you want to add openai api key
### create .env file in your server touch .env
### vi .env #press insert #copy your api key and paste it there #press and then :wq ### and hit enter

### go with security and add the inbound rule add the port 8501

```bash

sudo apt update

sudo apt-get update

sudo apt upgrade -y

sudo apt install git curl unzip tar make sudo vim wget -y

git clone "Your-repository"

sudo apt install python3-pip

pip3 install -r requirements.txt

python3 -m streamlit run StreamlitAPP.py

```
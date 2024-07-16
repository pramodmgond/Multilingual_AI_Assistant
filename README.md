# Multilingual_AI_Assistant
python=3.9

gemini api key :  https://aistudio.google.com/app/apikey

# Multilingual-AI-Assistant


# How to run?
### STEPS:

Clone the repository

```bash
Project repo: https://github.com/
```
### STEP 01- Create a conda environment after opening the repository

```bash
conda create -n llmapp python=3.8 -y
```

```bash
conda activate llmapp
```


### STEP 02- install the requirements
```bash
pip install -r requirements.txt
```

### Create a `.env` file in the root directory and add your GOOGLE_API_KEY credentials as follows:

```ini
GOOGLE_API_KEY = "xxxxxxxxxxxxxxxxxxxxxxxxxxxxx"
```


```bash
# Finally run the following command
streamlit run app.py
```

Now,
```bash
open up localhost:
```


### Techstack Used:

- Python
- Google API
- Streamlit
- PaLM2
- s2t
- t2s



# How to Deploy Streamlit app on EC2 instance

## 1. Login with your AWS console and launch an EC2 instance

## 2. Run the following commands

### Note: Do the port mapping to this port:- 8501

```bash
sudo apt update
```

```bash
sudo apt-get update
```

```bash
sudo apt upgrade -y
```

```bash
sudo apt install git curl unzip tar make sudo vim wget -y
```


```bash
git clone "Your-repository"
```

```bash
sudo apt install python3-pip
```
or 
Install the venv module if it's not already installed:
sudo apt install python3-venv

Create a virtual environment:
python3 -m venv myenv

Activate the Virtual Environment:
source myenv/bin/activate
pip install -r requirements.txt

install pyaudio seperately
sudo apt install portaudio19-dev
python3 -m  pip install PyAudio

```bash
pip3 install -r requirements.txt
```

```bash
#Temporary running
python3 -m streamlit run app.py
```

```bash
#Permanent running
nohup python3 -m streamlit run app.py
```

Note: Streamlit runs on this port: 8501







# install from requirements
virtualenv venv
source venv/bin/activate
pip install -r requirements.txt

# install normal
virtualenv venv
source venv/bin/activate
pip install notebook librosa matplotlib
pip freeze > requirements.txt

# run
jupyter notebook


# TO CHECK
Fairseq
Fairseq speech extension
Torchaudio 0.3.0  --> spectograms and MFCCs



# coping files from vm
scp -i /home/oscar/.ssh/aws_key ubuntu@18.191.58.37:/home/ubuntu/dataSet/pourquoi/0008.wav .


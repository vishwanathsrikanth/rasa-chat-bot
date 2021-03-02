#  Rasa Chat Bot

## Version Information

```
Rasa Version     : 2.3.0
Rasa SDK Version : 2.3.1
Rasa X Version   : None
Python Version   : 3.7.9
Operating System : Windows-10-10.0.19041-SP0
```

## Dependency Versions

```
absl-py==0.11.0
aio-pika==6.7.1
aiofiles==0.6.0
aiohttp==3.6.3
aiormq==3.3.1
APScheduler==3.7.0
astroid==2.4.2
astunparse==1.6.3
async-generator==1.10
async-timeout==3.0.1
attrs==20.3.0
backcall==0.2.0
bidict==0.21.2
blis==0.4.1
boto3==1.17.6
botocore==1.20.6
cachetools==4.2.1
catalogue==1.0.0
certifi==2020.12.5
cffi==1.14.5
chardet==3.0.4
cloudpickle==1.6.0
colorama==0.4.4
colorclass==2.2.0
coloredlogs==14.3
colorhash==1.0.3
cryptography==3.4.4
cycler==0.10.0
cymem==2.0.5
decorator==4.4.2
dm-tree==0.1.5
dnspython==1.16.0
docopt==0.6.2
en-core-web-md @ https://github.com/explosion/spacy-models/releases/download/en_core_web_md-2.2.5/en_core_web_md-2.2.5.tar.gz
fbmessenger==6.0.0
future==0.18.2
gast==0.3.3
google-auth==1.26.1
google-auth-oauthlib==0.4.2
google-pasta==0.2.0
grpcio==1.35.0
h11==0.9.0
h5py==2.10.0
httpcore==0.11.1
httplib2==0.19.0
httptools==0.1.1
httpx==0.15.4
humanfriendly==9.1
idna==2.10
importlib-metadata==3.4.0
ipykernel==5.3.4
ipython==7.19.0
ipython-genutils==0.2.0
isort==5.6.4
jedi==0.17.2
jmespath==0.10.0
joblib==0.15.1
jsonpickle==1.5.2
jsonschema==3.2.0
jupyter-client==6.1.7
jupyter-core==4.7.0
kafka-python==2.0.2
Keras-Preprocessing==1.1.2
kiwisolver==1.3.1
lazy-object-proxy==1.4.3
Markdown==3.3.3
matplotlib==3.3.4
mattermostwrapper==2.2
mccabe==0.6.1
multidict==4.7.6
murmurhash==1.0.5
networkx==2.5
numpy==1.16.6
oauth2client==4.1.3
oauthlib==3.1.0
opt-einsum==3.3.0
packaging==20.9
pamqp==2.3.0
pandas==1.2.2
parso==0.7.1
pickleshare==0.7.5
Pillow==8.1.0
plac==1.1.3
preshed==3.0.5
prompt-toolkit==2.0.10
protobuf==3.14.0
psycopg2-binary==2.8.6
pyasn1==0.4.8
pyasn1-modules==0.2.8
pycparser==2.20
pydot==1.4.1
Pygments==2.7.2
PyJWT==2.0.1
pykwalify==1.8.0
pylint==2.6.0
pymongo==3.10.1
pyparsing==2.4.7
pyreadline==2.1
pyrsistent==0.17.3
pyTelegramBotAPI==3.7.6
python-crfsuite==0.9.7
python-dateutil==2.8.1
python-engineio==3.13.2
python-socketio==5.0.0
pytz==2020.5
pyzmq==20.0.0
questionary==1.5.2
rasa==2.3.0
rasa-sdk==2.3.1
redis==3.5.3
regex==2020.9.27
requests==2.25.1
requests-oauthlib==1.3.0
requests-toolbelt==0.9.1
rfc3986==1.4.0
rocketchat-API==1.9.1
rsa==4.7
ruamel.yaml==0.16.12
ruamel.yaml.clib==0.2.2
s3transfer==0.3.4
sanic==20.9.0
Sanic-Cors==0.10.0.post3
sanic-jwt==1.5.0
Sanic-Plugins-Framework==0.9.5
scikit-learn==0.24.1
scipy==1.6.0
sentry-sdk==0.19.5
six==1.15.0
sklearn-crfsuite==0.3.6
slackclient==2.9.3
sniffio==1.2.0
spacy==2.2.4
SQLAlchemy==1.3.23
srsly==1.0.5
tabulate==0.8.7
tensorboard==2.4.1
tensorboard-plugin-wit==1.8.0
tensorflow==2.3.2
tensorflow-addons==0.12.0
tensorflow-estimator==2.3.0
tensorflow-hub==0.10.0
tensorflow-probability==0.11.1
termcolor==1.1.0
terminaltables==3.1.0
thinc==7.4.0
threadpoolctl==2.1.0
toml==0.10.2
tornado==6.1
tqdm==4.56.2
traitlets==5.0.5
twilio==6.50.1
typed-ast==1.4.1
typeguard==2.10.0
typing-extensions==3.7.4.3
tzlocal==2.1
ujson==4.0.2
urllib3==1.26.3
wasabi==0.8.2
wcwidth==0.2.5
webexteamssdk==1.6
websockets==8.1
Werkzeug==1.0.1
wincertstore==0.2
wrapt==1.12.1
yarl==1.5.1
zipp==3.4.0
```

## Environment Setup

```
conda create rasa
conda activate rasa
pip install rasa 
pip install rasa[Spacy]
pip install pandas
```




## Dev and Test

```
rasa data validate
rasa train
rasa run actions
rasa shell
```

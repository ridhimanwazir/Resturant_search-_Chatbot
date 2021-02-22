This is the readme file to run and config FOODIE THE ARTIFICIAL INTELLIGENCE CHATBOT that is here to help everyone with there hunger cravings
FOODIE works on zomato api so in order to get it working a zomato api key is used
visit https://developers.zomato.com/ for further documentation and how to use it and below are some ways to use the api




1. Installing visual studio and all the dependencies required for the project
Download Visual Studio 2k19 for community edition from the link ----> https://visualstudio.microsoft.com/downloads/
after installing the installer install all the dependencies below :- 
-> Python development 
-> .NET desktop development 
-> Desktop development with C++ 
-> Game development with C++ 

---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

2. Python environment setup and all the libraries required

Installing python and pip ---->

WINDOWS :- https://www.python.org/ (version 3.6.8 or above)
check python version :- python3 --version
installing pip :- pip3 install -U pip

MACOS :- https://www.python.org/ (version 3.6.8 or above)
(Before installing Python, you have to install the Homebrew package manager if you haven’t already)

Creating virtual environment ---->

WINDOWS :- python3 -m venv --system-site-packages ./venv
MACOS :- python3 -m venv --system-site-packages ./venv

Activating the virtual environment ---->

WINDOWS :- .\venv\Scripts\activate
MACOS :- source ./venv/bin/activate

Installing rasa and all the libraries ---->

pip install rasa-x --extra-index-url https://pypi.rasa.com/simple

pip install rasa 

Installing spacy and nlu for the chatbot ---->

pip install rasa[spacy]

python -m spacy download en_core_web_md

python -m spacy link en_core_web_md en


If required below are the libraries which can be used for installing the libraries in the environment ---->

absl-py==0.9.0
aiofiles==0.5.0
aiohttp==3.6.2
alembic==1.4.2
APScheduler==3.6.3
astor==0.8.1
astroid==2.3.2
astropy==3.2.3
async-generator==1.10
async-timeout==3.0.1
atomicwrites==1.3.0
attrs==19.3.0
backcall==0.1.0
beautifulsoup4==4.8.0
bleach==3.1.0
blis==0.2.4
boto3==1.12.41
botocore==1.15.41
bs4==0.0.1
cachetools==3.1.1
certifi==2019.6.16
cffi==1.14.0
chardet==3.0.4
cloudpickle==1.2.2
colorama==0.4.1
colorclass==2.2.0
coloredlogs==10.0
colorhash==1.0.2
confuse==1.0.0
contextvars==2.4
cryptography==2.9
cycler==0.10.0
cymem==2.0.3
decorator==4.4.0
defusedxml==0.5.0
Django==2.2.6
dnspython==1.16.0
docopt==0.6.2
docutils==0.15.2
en-core-web-md==2.1.0
entrypoints==0.3
fbmessenger==6.0.0
future==0.18.2
gast==0.2.2
gevent==1.4.0
gitdb==4.0.4
GitPython==3.1.1
google-api-python-client==1.7.11
google-auth==1.6.3
google-auth-httplib2==0.0.3
google-auth-oauthlib==0.4.1
google-pasta==0.2.0
graphviz==0.13.2
greenlet==0.4.15
grpcio==1.28.1
h11==0.8.1
h2==3.2.0
h5py==2.10.0
hpack==3.0.0
hstspreload==2020.4.14
htmlmin==0.1.12
httplib2==0.13.1
httptools==0.1.1
httpx==0.9.3
humanfriendly==8.2
hyperframe==5.2.0
idna==2.8
idna-ssl==1.1.0
imbalanced-learn==0.6.2
imblearn==0.0
immutables==0.11
importlib-metadata==0.23
ipykernel==5.1.0
ipython==7.3.0
ipython-genutils==0.2.0
ipywidgets==7.4.2
isodate==0.6.0
isort==4.3.21
jedi==0.13.3
Jinja2==2.10
jmespath==0.9.5
joblib==0.14.1
json5==0.8.5
jsonpickle==1.3
jsonschema==3.2.0
jupyter==1.0.0
jupyter-client==6.1.3
jupyter-console==6.1.0
jupyter-contrib-core==0.3.3
jupyter-contrib-nbextensions==0.5.1
jupyter-core==4.6.3
jupyter-highlight-selected-word==0.2.0
jupyter-latex-envs==1.4.6
jupyter-nbextensions-configurator==0.4.1
jupyterthemes==0.20.0
kafka-python==1.4.7
Keras-Applications==1.0.8
Keras-Preprocessing==1.1.0
kiwisolver==1.0.1
lazy-object-proxy==1.4.3
lesscpy==0.13.0
llvmlite==0.30.0
lxml==4.4.1
Mako==1.1.2
Markdown==3.2.1
MarkupSafe==1.1.1
matplotlib==3.1.3
mattermostwrapper==2.2
mccabe==0.6.1
missingno==0.4.2
mistune==0.8.4
more-itertools==7.2.0
multidict==4.7.5
murmurhash==1.0.2
nbconvert==5.4.1
nbformat==4.4.0
networkx==2.4
nltk==3.4.5
notebook==6.0.2
numba==0.46.0
numpy==1.16.2
oauth2client==4.1.3
oauthlib==3.1.0
opencv-python==4.0.0.21
opt-einsum==3.2.1
packaging==19.0
pandas==0.24.2
pandas-profiling==2.3.0
pandocfilters==1.4.2
parso==0.3.4
patsy==0.5.1
phik==0.9.8
pickleshare==0.7.5
pika==1.1.0
plac==0.9.6
pluggy==0.13.0
ply==3.11
preshed==2.0.1
prometheus-client==0.6.0
prompt-toolkit==2.0.9
protobuf==3.11.3
psycopg2-binary==2.8.5
py==1.8.0
pyasn1==0.4.6
pyasn1-modules==0.2.6
pycparser==2.20
pydot==1.4.1
pydotplus==2.0.2
Pygments==2.3.1
PyJWT==1.7.1
pykwalify==1.7.0
pylint==2.4.3
pymongo==3.8.0
pyparsing==2.3.1
pypiwin32==223
pyreadline==2.1
pyrsistent==0.14.11
PySocks==1.7.1
pytest==5.2.2
pytest-pylint==0.14.1
python-crfsuite==0.9.7
python-dateutil==2.8.0
python-editor==1.0.4
python-engineio==3.11.2
python-socketio==4.4.0
python-telegram-bot==11.1.0
pytz==2019.3
pywin32==224
pywinpty==0.5.5
PyYAML==5.1.2
pyzmq==18.0.1
qtconsole==4.4.3
questionary==1.5.2
rasa==1.9.6
rasa-sdk==1.9.0
rasa-x==0.27.5
redis==3.4.1
requests==2.23.0
requests-oauthlib==1.2.0
requests-toolbelt==0.9.1
rfc3986==1.4.0
rocketchat-API==0.6.36
rsa==4.0
ruamel.yaml==0.15.100
s3transfer==0.3.3
sanic==19.12.2
Sanic-Cors==0.10.0.post3
sanic-jwt==1.3.2
Sanic-Plugins-Framework==0.9.2
scikit-learn==0.22.1
scipy==1.4.1
seaborn==0.9.0
Send2Trash==1.5.0
six==1.12.0
sklearn==0.0
sklearn-crfsuite==0.3.6
slackclient==2.5.0
smmap==3.0.2
sniffio==1.1.0
soupsieve==1.9.3
spacy==2.1.9
SQLAlchemy==1.3.16
sqlparse==0.3.0
srsly==1.0.2
statsmodels==0.10.1
tabulate==0.8.7
tensorboard==2.1.1
tensorflow==2.1.0
tensorflow-addons==0.9.1
tensorflow-estimator==2.1.0
tensorflow-hub==0.7.0
tensorflow-probability==0.7.0
termcolor==1.1.0
terminado==0.8.1
terminaltables==3.1.0
testpath==0.4.2
thinc==7.0.8
tornado==6.0.3
tqdm==4.31.1
traitlets==4.3.2
treebank==0.0.0
twilio==6.26.3
typed-ast==1.4.0
typeguard==2.7.1
typing-extensions==3.7.4.2
tzlocal==2.0.0
ujson==1.35
uritemplate==3.0.0
urllib3==1.25.3
virtualenv==16.7.5
virtualenvwrapper-win==1.2.5
wasabi==0.6.0
wcwidth==0.1.7
webencodings==0.5.1
webexteamssdk==1.1.1
websockets==8.1
Werkzeug==1.0.1
widgetsnbextension==3.4.2
wrapt==1.11.2
yarl==1.4.2
zipp==0.6.0


---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

3. Running the chatbot

After installing the env. and activating it open a command prompt inside the chatbot folder

Go to zomato API and then generate an API key which will be needed to config the zomatopy object inside the actions.py file 


To train nlu type :- rasa train nlu
To train core type :- rasa train core
To train the model :- rasa train -vv -dump-stories --force

When starting the chatbot we need to run the action.py file to do that
In cmd run :- rasa run actions

When starting the server run 
rasa run 

To run the model in cmd 
rasa shell

To debug the model and generate new stories efficiently run
rasa interactive

---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

4. Deploying the chatbot 

To deploy the chatbot create a workspace in Slack and then create an app where we will generate a API key for the application that is needed to be added to the credentials.yml file
Then run ngrock.exe http 5005(the server on which rasa is running)



---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

5. config.py

This file can be used to config the policies of the rasa chatbot

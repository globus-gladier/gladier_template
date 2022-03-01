# gladier-client-template


## Installing

This is an example on how to set your gladier The main core of gladier uses Globus for transfers and FuncX for executions.

### Installing Gladier 

    conda create -n gladier pip
    conda activate gladier

    git clone https://github.com/globus-gladier/gladier-client-template
    cd gladier-client-template
    
    pip install -r requirements.txt

    python setup.py develop


### Establishing the Data Fabric

#### Installing Globus Transfer endpoint

#### Installing FuncX endpoint

## Creating a new gladier client

- Start your repo with globus-gladier/gladier-client-template as template
- change the gladier-client folder to reflect your new name
- change the setup.py to reflect your new name

## Running

Gladier works on top of several different services and it may be complicated to explain all at once.
We supply different notebooks to introduce each topic. 

### FuncX server versioning

FuncX endpoints and versions need to be synced between clients. Trying to execute a function registered on the wrong version will result on an exception and the termination of the flow.
Try notebooks/get_server_info notebook.

### Basic FuncX and Globus Automate flow 
basic_funcx_flow

### Basic Gladier Client demo
gladier_basic_client

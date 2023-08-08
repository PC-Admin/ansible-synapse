# ansible-synapse

A ansible playbook to deploy a simple Synapse server. (For testing purposes only!)


## Install Prerequisites

`$ pip install psycopg2`


## Setup Server

1) Configure the [inventory/](inventory/) files for all the desired hosts appropriately.

2) Run the setup.yml playbook:

`ansible-synapse$ ansible-playbook -v -i inventory/hosts setup.yml`

# pg_faker

> fake data for postgres databases

This project creates a `faker` schema in the database and then adds tables
of faker data to that schema.

Get up and running with ansible:

```
$ ansible-playbook setup.yml --extra-vars "database_name=my_database"
```

Complete:

    #pedroAkiraDanno/pg_faker
    #ROOT
    cd ~
    #cd /etc/ansible/  && rm -rf /etc/ansible/*
    cd /etc/ansible/
    git clone https://github.com/pedroAkiraDanno/pg_faker.git

    cd /etc/ansible/pg_faker/ ; mv  *  /etc/ansible/
    cd /etc/ansible/  && rm -rf pg_faker/

    $ ansible-playbook setup2.yml --extra-vars "database_name=my_database"

opichon.docker-blackfire
=========

Ansible role to run [blackfire.io](https://blackfire.io/docs/integrations/docker) agent as a docker container.

Role Variables
--------------

* blackfire_hostname: blackfire
* blackfire_network: blackfire
* blackfire_server_id
* blackfire_server_token
* blackfire_state: started

Dependencies
------------

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
        - name: Deploy blackfire agent
         	role: opichon.docker-blackfire

License
-------

MIT

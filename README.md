pip
===

This role install pip and configure repository mirror.

Role Variables
--------------

There are only two variables for repository mirror, as the default values listed below:

    pip_index_url: http://mirrors.aliyun.com/pypi/simple/
    pip_trusted_host: mirrors.aliyun.com

Usually you don't need to change them.

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: frank6866.pip }

License
-------

MIT

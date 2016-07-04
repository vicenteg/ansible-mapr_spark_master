sparkmaster
========

Installs a Spark master.

Requirements
------------

This role assumes that the MapR apt/yum repositories have been configured.

Role Variables
--------------

`default/main.yml` contains the following:

```
spark_version: 0.9.1
spark_home: /opt/mapr/spark/spark-{{spark_version}}
```

There's not currently a need to modify these.

Dependencies
------------

mapr-prerequisites


Example Playbook
-------------------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: sparkmasters
      roles:
         - { role: mapr-spark-master, spark_version: "0.9.1" }


License
-------

Apache

Author Information
------------------

Vince Gonzalez

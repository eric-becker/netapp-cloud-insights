Role Name
=========

Role to install NetApp Cloud Insights telegraf agent. Simply pass in the two variables. 

Requirements
------------

N/A

Role Variables
--------------

cloudinsights_domain: psXXXX.c02.cloudinsights.netapp.com
cloudinsights_apikey: **************************************

Dependencies
------------

N/A

Example Playbook
----------------

    - name: Play to Deploy Telegraf for NetApp Cloud Insights
      hosts: all
      roles:
        - netapp-cloud-insights
 
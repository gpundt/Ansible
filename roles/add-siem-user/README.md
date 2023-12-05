add-siem-user
=========
This Ansible role will add a user to the SIEM Stack. It will install a Vector Agent onto hosts, Configure rsyslog to forward logs, and point everything to the SIEM Stack VM where all data can be collected, visualized, and filtered

Requirements
------------
THIS PLAYBOOK CAN ONLY RUN ON ROCKY, CENTOS, AND RHEL LINUX DISTRIBUTIONS

This role requires a functional SIEM Stack that uses Vector Aggregator as its log / metric collector.

Please download the newest Vector RPM at https://vector.dev/download/ and place in /add-siem-user/files/


Author Information
------------------
Name: Griffin Pundt
Occupation: Student
School: RIT
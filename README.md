[![Build Status](https://travis-ci.org/RealSalmon/ansible-time.svg?branch=master)](https://travis-ci.org/RealSalmon/ansible-time)

RealSalmon.time
===============
Set system timezone and ensure that NTP is running

Requirements
------------
- Ubuntu 14.04
- Ansible 1.9

Role Variables
--------------
- time_timezone: "America/New_York"

Dependencies
------------
None

Example Playbook
----------------
    ---
    - hosts: all
      roles:
        - RealSalmon.time

License
-------
BSD

Author Information
------------------
Ben Jones <ben@fogbutter.com>

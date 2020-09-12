# Cisco_ASA_Split_Tunnel_AWS_LBs Playbook
Run "aws elb|elbv2 describe-load-balancers" to create a list to update Cisco ASA object-group for interesting traffic for remote access VPN. 

## Problem
Cisco ASA Anyconnect VPN split tunnel access lists do not allow FQDN entries.

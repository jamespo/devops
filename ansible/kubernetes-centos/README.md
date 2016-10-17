# Deploy kubernetes on Centos 7

## Description

An ansible playbook to deploy kubernetes from packages as per
http://kubernetes.io/docs/getting-started-guides/centos/centos_manual_config

## Setup

2 Centos 7 machines (bare metal or virtual) ssh accessible from ansible master.
This playbook assumes the remote accounts have full sudo access.

On ansible master create /etc/hosts entry with centos-master & centos-minion addresses.

## Run

ansible-playbook deploykub.yml


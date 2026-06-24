# Day 6 - Introduction to SSH

## Objective

Learn the basics of SSH and install an SSH server on Ubuntu.

## Commands Learned

ssh -V

which ssh

sudo apt update

sudo apt install openssh-server -y

systemctl status ssh

hostname -I

## Concepts Learned

### SSH

SSH (Secure Shell) is a secure protocol used to remotely access and manage Linux systems.

### SSH Client

Used to connect to remote systems.

### SSH Server

Accepts incoming SSH connections from other systems.

## Practical Tasks

Installed OpenSSH Server

sudo apt install openssh-server -y

Started SSH Service

sudo systemctl start ssh

Verified SSH Status

systemctl status ssh

Connected to Localhost Using SSH

ssh localhost

Accepted SSH Fingerprint

Successfully Logged In Using SSH

## Key Learning

* SSH provides secure remote access to Linux systems.
* SSH commonly uses TCP Port 22.
* SSH is essential for Cloud Computing, Networking, DevOps and Cybersecurity.
* OpenSSH Server allows remote users to connect to a Linux machine.

## What I Learned

* SSH is widely used in Linux administration.
* Cloud servers are usually managed through SSH.
* Ubuntu requires the OpenSSH Server package to accept SSH connections.

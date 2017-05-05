Vagrant Demo
===============

A simple demonstration of [Vagrant](https://vagrant.com).

# Instructions

The following instructions are meant to be used at your computer's command
prompt. Each command is typed at a command line.

## Clone the Project

Use Git to acquire a local copy of this project in order to 'boot' the Vagrant virtual machine.

~~~~~~shell
git clone https://github.com/100i/Vagrant-Demonstration.git
~~~~~~


## 1. Start

Start the virtual machine with Vagrant.
```shell
vagrant up
```

## 2. Connect
Connect to the virtual machine create by Vagrant.

```shell
vagrant ssh
```

## 4. Return to Host

After connecting to the guest machine, you can exit with [exit]() at the
command prompt.

```
exit
```

## 5. Reload VM Configuration

Reload the VM, and provision (reload any VM configuration settings).

```shell
vagrant reload --provision
```

## 6. Destroy

```shell
vagrant destroy
```

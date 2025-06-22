# Hi there! 👋

This GitHub repository provides code for kubernetes container with the yaml language 

# Kubernetes nginx container with yaml files

# Getting started

## Requirements
* Virtual machine e.g Virtual box from oracles official website: 
* Enable Hyper-V with your windows machine and enable virtualization with BIOS from windows machine:
* Install chocolatey 
    ```bash
    Set-ExecutionPolicy Bypass -Scope Process -Force; [System.Net.ServicePointManager]::SecurityProtocol = [System.Net.SecurityProtocolType]::Tls12; iex ((New-Object System.Net.WebClient).DownloadString('https://chocolatey.org/install.ps1'))
    ```
* Kubernetes extension from microsoft on visual studio code
* Google cloud code extension.

##  Installation
* Install Kubernetes-cli with choco
    ```bash
    choco install kubernetes-cli
    ```
* Install minikube to run kubernetes and virtual machines
    ```bash
    choco install minikube
    ```
* Start minikube 
    ```bash
    minikube start
    ```

## Running the App
* Running Kubernetes
    ```bash
    kubernetes get nodes
    ```

    
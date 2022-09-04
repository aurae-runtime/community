# Aurae Community

Welcome to the Aurae project (auræ).

The project name is pronounced like the English word "aura" and is named after a minor Greek/Roman mythological deity, whose name means "breeze".

### What is Aurae?

Aurae is a free and open source distributed runtime that solves problems similar to Kubernetes and Systemd.

#### What it is?

Aurae is made up of 2 main components. 

 - A user-side shell called `aurae`.
 - A core daemon that listens over a unix domain socket called `auraed`.
 
 That's it. 

#### What it does?

Aurae is designed to do a lot of things. Simply put though it runs and schedules workloads at scale.

 - Runs workloads in "sandbox" environments
  - Regular processes (Seccomp, selinux, systemcall filtering, etc)
  - Containerized processes (Cgroup namespaces, and container runtimes like containerd and docker)
  - Virtual Machine processes (Small lightweight firecracker style microVMs)
  
Aurae is built around a standard library, that is designed to be the ultimate standard library for application teams.  
    
# Getting Involved

If you would like to get involved with Aurae development. 

 - Join our [discord](https://discord.gg/JqvvtUZkMD) and find the `#aurae` channel.
 - Follow the instructions in the [authz](https://github.com/aurae-runtime/authz) repository to get access to the code.
 - You probably also want to introduce yourself in Discord and start getting to know a few folks.
 
 
# Mailing List

We are working on creating a public mailing list now.

  
  

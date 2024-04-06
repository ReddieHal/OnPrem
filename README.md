# OnPrem

## Senior Project:
Idea/Abstract: Original idea was setting up an on-prem cloud at my homelab as a way to gain some knowledge about OpenStack and setting up my own custom stack to just do some self-hosted services but our conversation the other day got me thinking about setting up a class lab env from scratch similar to what's in the existing server room. An environment that allows (admins/professors) to upload golden images or a golden network template that can be automatically constructed given a class roster list. Where students and professors can access the VMs remotely, can't access anyone else's, can be configured to reach out to the internet. With reset buttons for both students and professors.

## Main Goals (Kinda in Order):
- pfSense Firewall with DDNS/Domain Set-up (I have my own for now) / Microtik RouterOS
- Openstack research on which modules to set up for compute, networking, storage, virtualization, orchestration, and management
  - Spin up Openstack modules, play around with secure settings
- Spin up some virtual machines on an isolated network
- Apache Guacamole pointing toward those machines
- Set up an admin panel to
  - Upload vm images
  - Handle upload and available
  - Verify images can be instantiated
  - Potentially access student VM's
  - Set up to reset VM's
  - Once one isolated network can be made with golden images
  - AUTOMATE with rosters!
DOCUMENT EVERYTHING - There has to be an internal tool that can host documentation so people can access it. As well as this github.

## Deep Dive Goals(Done if main goals were met):
- Handle special case scenarios like ML work scheduling(?)
- Deeper configuration/ pentest analysis
- Variable student-isolated networks
- I.e Like Spring Quarter setting up a network with all the students' VMs on the same net and being able to attack each other for one class, alongside another with the standard set-up etc.

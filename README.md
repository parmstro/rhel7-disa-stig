DISA STIG for Red Hat Enterprise Linux 7
=========

## Purpose
This project will create a series of Ansible playbooks and/roles designed to be used in conjunction with Ansible Tower and Red Hat Satellite 6.x for the remediation of systems that are required to meet DISA STIGs. The first implementation is that for a simple system running base RHEL7. Satellite's OpenSCAP feature is being used for checking and reporting on the STIG while Ansible Tower will be called for remeditation. 

When a system fails a report, a service will be enabled and the service will perform automated remediation if it is able.




Ansible remediation role for profile stig-rhel7-disa  
Profile Title:  DISA STIG for Red Hat Enterprise Linux 7  
Profile Description:  
  
This profile contains configuration checks that align to the   
DISA STIG for Red Hat Enterprise Linux V1R1.  
  
In addition to being applicable to RHEL7, DISA recognizes this   
configuration baseline as applicable to the operating system  
tier of Red Hat technologies that are based off RHEL7, such as RHEL  
Server,  RHV-H, RHEL for HPC, RHEL Workstation, and Red Hat   
Storage deployments.  
  
  
Benchmark ID:  RHEL-7  
Benchmark Version:  0.1.37  
  
XCCDF Version:  1.1  
  
This file was generated by OpenSCAP 1.2.16 using:  
	$ oscap xccdf generate fix --profile stig-rhel7-disa --template urn:xccdf:fix:script:ansible sds.xml   
  
This script is generated from an OpenSCAP profile without preliminary evaluation.  
It attempts to fix every selected rule, even if the system is already compliant.

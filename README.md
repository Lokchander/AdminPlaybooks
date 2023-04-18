AdminPlaybooks

This is the place where I have created and Kept the Admin related playbooks
=============================================================================================
. version - 0.0.2
. date - 17-APR-2023

---------------------------------------------------------------------------------------------

1) TempSudo Playbook - tempsudo.yaml 
   - A playbook for providing the temp sudo access for the given ID. Expiry date should be given so that the access will be revoked automatically on that date.
   - edate format been enforced to match the syntax 
   - facts been set for entering the values in the cron module.
   - job in the cron can be added with the mailx/mail command to send email when the access is revoked.

2) ReaR backup configuration Playbook - rearbackup.yaml
   - A Playbook for installing and  configuring the ReaR backup tool in the linux servers.
   - The rear-local.conf.j2 can be edited for giving input configs for the ReaR based on the environment.
   - backup url can be defined inside the playbook.  

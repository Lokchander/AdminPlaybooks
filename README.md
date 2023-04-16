# AdminPlaybooks
This is the place where I have created and Kept the Admin related playbooks

version - 0.0.1
date - 16-APR-2023

1) TempSudo Playbook - tempsudo.yaml 
   - A playbook for providing the temp sudo access for the given ID. Expiry date should be given so that the access will be revoked automatically on that date.
   - edate format been enforced to match the syntax 
   - facts been set for entering the values in the cron module.
   - job in the cron can be added with the mailx/mail command to send email when the access is revoked.


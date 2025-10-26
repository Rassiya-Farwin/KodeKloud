The Nautilus DevOps team is in the process of developing scripts to be executed on various schedules. Currently, they are provisioning cron jobs within the Kubernetes cluster with placeholder commands (to be substituted with actual scripts). Below are the specifications for creating a cronjob:


a. Create a cronjob named datacenter-t3q1.

b. Set Its schedule to something like */3 * * * *, you set any schedule for now.

c. Container name should be cron-datacenter-t3q1.

d. Use nginx image with latest tag only and remember to mention the tag i.e nginx:latest.

e. Run a dummy command echo Welcome to xfusioncorp!.

f. Ensure restart policy is OnFailure.

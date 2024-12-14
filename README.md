# Simple SIEM Lab
<h2>Objectives</h2>

- <b>Generate security events on the Kali VM</b>
- <b>Configure and set up an agent to forward data from the Kali VM to the SIEM</b>
- <b>Query and analyze the forwarded logs in the Elastic SIEM</b>
<br />

<h2>Requirements</h2>

- <b>Oracle VirtualBox</b> : https://www.virtualbox.org/wiki/Downloads
- <b>Elastic Cloud</b>     : https://cloud.elastic.co/registration
- <b>Kali</b>              : https://www.kali.org/get-kali/#kali-virtual-machines.
- <b>Basic Knowledge of Linux</b>
<br />

<h2>Steps to follow</h2>

<p align="center">
  
- <b>Set up a free Elastic account and Install the Kali VM.</b>

- <b>Configure the Elastic Agent on the Linux VM to collect the logs and forward it to the SIEM.</b>

- <b>Generate security events on the Kali VM.</b>

- <b>Query to find the security events in the Elastic SIEM.</b>

- <b>Create a Dashboard to visualize security events.</b>

- <b>Create alerts for security events.</b>
<br />

<h2>Implementation</h2>

1. <b>Set up a free Elastic account and Install the Kali VM:</b>

      1.1 <b>Set up a free Elastic account: </b>Use Elastic Cloud registration link from above to Sign up for a free trial account. Then log in to the Elastic Cloud console, click on the “Start your free trial”.
      Click on the “Create Deployment” button and select “Elasticsearch” as the deployment type. Choose a region and deployment size according to your needs and click on the “Create Deployment”.
      Wait for the configuration to complete. Once the deployment is ready, click “Continue”.

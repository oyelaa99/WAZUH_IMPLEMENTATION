# WAZUH_IMPLEMENTATION
step by step to implement wazuh(SIEM) in virtual box environment 


In this repository I will implement one of the open source SIEM tools and also free which mean no limitation in term of ressource so adapt for the homelab

REQUIREMENT 

Before we start there are some hardware requirement that we should follow in order to make it run properly without bug or crash 
you can see the hardware requirement here :https://documentation.wazuh.com/current/quickstart.html#requirements

DOWNLOAD AND INSTALLATION

Download and run the wazuh installation assistance by using the following link

curl -sO https://packages.wazuh.com/4.12/wazuh-install.sh && sudo bash ./wazuh-install.sh -a

Once the assistant finishes the installation, the output shows the access credentials and a message that confirms that the installation was successful.
After the installation complete you will see the login credential that you will use to login in wazuh interface
Access the Wazuh web interface with
https://<WAZUH_DASHBOARD_IP_ADDRESS> and your credentials:

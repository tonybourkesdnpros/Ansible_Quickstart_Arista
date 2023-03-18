This directy is for using AVD directly with EOS, bypassing CVP entirely. 

CVP is sometimes difficult to home lab, as it requires 16 cores even for the lab version (which most people don't have in their home lab). 

The build, document, and test playbooks are the same. Only the deploy model is different. 

The data models are modified as when you deploy to EOS directly, the *entire* configuration needs to be built. If you're missing something like the management interface, you'll lock yourself out of the switch. 

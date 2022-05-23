#Ansible Networking Testing

Commands are documented under cmd/ 

Update this to point to updated vars files

Once variables files are tuned, run
	cmd/setup-bridges
	cmd/setup-vlans

Bridges must be created prior to vlans being created, as vlans reference the bridges when created.
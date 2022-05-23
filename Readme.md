# Ansible Networking Testing

Commands are documented under cmd/ 

Update cmd/* to point to updated vars files

Once variables files are tuned, run
	`cmd/setup-bridges`
	`cmd/setup-vlans`

*NOTE: Bridges must be created prior to vlans being created, as vlans reference the bridges when created.*

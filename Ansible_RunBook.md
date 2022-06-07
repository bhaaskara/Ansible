# Multi tier application deployments on k8s using ansible
https://developer.ibm.com/tutorials/orchestrate-multi-tier-application-deployments-on-kubernetes-using-ansible-pt-3/

# Run ansible play book with user/password
`ansible-playbook -i <hostsfile> <playbook.yml> -u <username> -k -K`

it will prompt for password and sudo password.
Note: for play book, `hosts` will be mentioned in the file, instead of command line arg. 
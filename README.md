# azure

Template create vm linux (centos/ubuntu) azure using ansible , edit di bagian Resource groups 



note: - az vm image list
     
      - az vm create -n master01 -g 1-d5a72f-playground-sandbox --image CentOS  --admin-username andi --admin-password Cikarang123$
       ( create vm lewat powershell )
      
       https://docs.microsoft.com/en-us/azure/virtual-machines/windows/quick-create-cli   
       https://docs.microsoft.com/en-us/azure/azure-resource-manager/templates/template-syntax#resources
       https://docs.microsoft.com/en-us/azure/virtual-machines/windows/quick-create-powershell
       https://docs.microsoft.com/en-us/powershell/module/az.compute/get-azvmimagepublisher?view=azps-3.4.0



Ansible lamp centos 
( lampinstall.yaml ) 
http://cloudnixpro.com/2018/05/11/ansible-playbook-install-lamp-on-cent-os-7/



az account list
az account get-access-token --resource-type ms-graph
az login

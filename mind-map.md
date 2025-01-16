--- Setup DNS in their  Registrar/DNS Provider , it the annuray throught wich the domain will be known in the network
     ( easy since we will only add the domain name in the annuary )
	
	A Record:
        example1.com → Your.Server.IP.Address
    A Record:
        example2.com → Same.Server.IP.Address 

--- Setup appache server, with ssl ( hard ) , we will need to add a new configuration folder and maybe ask the modification of the 
    other team  rename the folders , and modify the configurations, and maybe environement variables ( no problem appache virtual host handles this) 
    
/var/www/
├── app1/
│   ├── conf/
│   ├── logs/
│   └── html/
└── app2/
    ├── conf/
    ├── logs/
    └── html/
      



--- Hard Setup Ansible we need to deploy each application separately on the same server without modifying the configuration 
 

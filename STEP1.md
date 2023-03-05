## STEP 1 — INSTALLING APACHE AND UPDATING THE FIREWALL

update a list of packages in package manager

    $ sudo apt update

#run apache2 package installation

    $ sudo apt install apache2

    To verify that apache2 is running as a Service in our OS

    $ sudo systemctl status apache2

    To access our apache2 from the internet:

    Open TCP Port 80 in the inbound connection

    T access apache in our ubuntu shell , run

          curl http://localhost:80
or
       
         curl http://44.199.226.188:80    
# Setup Multiple Static Websites on a Single Server Using Nginx Virtual Hosts

# Setup a Static Website Using Nginx

|S/N | Project Tasks                                                                            | Key Concepts Covered         |
|----|------------------------------------------------------------------------------------------|------------------------------|
| 1  |Install and configure Nignx on a server                                                   | Subdomains                   |
| 2  |Create two website directories with two different website templates.                      | Nginx Virtual Hosts routing. |
| 3  |Create two subdomains                                                                     | Wildcard SSL (Letsencrypt)   |
| 4  |Add the IP of the server as A record to the two subdomains.                               |                              |
| 5  |Configure the Virtual host to point two subdomains to two different website directories.  |                              |
| 6  |Validate the setup accessing the subdomains.                                              |                              |
| 7  |Create a wildcard Letsencrypt SSL certificate for the root Domain.                        |                              |
| 8  |Configure wildcard SSL on Nginx for two websites.                                         |                              |
| 9  |Validate the subdomain websites’ SSL using OpenSSL utility.                               |                              |

## Checklist

- [ ] Task 1: Spin up a Ubuntu server & assign an elastic IP to it.
- [ ] Task 2: SSH into the server and install and configure Nignx on a server.
- [ ] Task 3: Create two website directories with two different website templates.
- [ ] Task 4: Create two subdomains
- [ ] Task 5: Add the IP of the server as A record to the two subdomains.
- [ ] Task 6: Configure the Virtual host to point two subdomains to two different website directories.
- [ ] Task 7: Validate the setup accessing the subdomains.  
- [ ] Task 8: Create a wildcard Letsencrypt SSL certificate for the root Domain.
- [ ] Task 9: Configure wildcard SSL on Nginx for two websites.
- [ ] Task 10: Validate the subdomain websites’ SSL using OpenSSL utility.

## Documentation

Please reference [**Project1**](https://github.com/StrangeJay/DevOps_Projects/blob/main/DevOpsCube/project1/project1.md) for guidance on spinning up an Ubuntu server, as well as creating and associating an elastic IP address with your server, among other tasks.

- Spin up your ubuntu server, create an elastic IP and associate it to your instance.

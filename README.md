# NetworkSharer
This project gives basic HTML, CSS, PHP wire frame to share files over the network. It can be useful to share large files quickly over network (for example LAN) without much haze.

# How to use


  - Clone the repository
  - Put the files you want to share over the network in `files` folder
  - Run the command `php -S 0.0.0.0:4000` from inside the project folder to deploy your project over the network
  
Host: `0.0.0.0` is used to allow access to other users over network. Change the port `4000` to any required port.
The files will be accessible at `<IP Address>:4000` over the network

# Requirements
1. PHP 5.4+

# Screenshots

![Alt text](/assets/img/ss.png?raw=true "Screenshot File Browser")
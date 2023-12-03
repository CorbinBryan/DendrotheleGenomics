# Required Software
Regardless of your current operating system and hardware, I recommend that all students of this tutorial have the following software installed: 
* Visual Studio Code (or your preferred integrated development environment)
* Docker
* miniconda3 (or your preferred conda distribution)
## Set-up for Windows Users
Windows users will need access to a Linux distribution. Microsoft Windows, unlike macOS X and Linux distributions, is not based on Unix. Thankfully, Windows machines hold a simple majority of the marketbase, and many bioinformaticians use Microsoft Windows. Thus, people far more computationally gifted than myself have already solved this problem. 
### Method 1: WSL (Windows Subsystem for Linux)
Open Windows Powershell in administrator mode. In the command center, right-click on Windows Powershell and select "Run as administrator". Then, enter the following: 
```bash
# install wsl 
wsl --install
# check wsl version and distribution 
wsl -v -l 
```
### Method 2: VM
Virtual machines run containerized operating systems from a server or host machine. There are very few (if any) entirely free virtual machines available to the bioinformatician, but most paid services offer a free tier. [Microsoft Azure](https://azure.microsoft.com/en-us/pricing/purchase-options/pay-as-you-go/) and [Amazon Web Services](https://aws.amazon.com/free/?gclid=Cj0KCQiA67CrBhC1ARIsACKAa8TOlc-OBDyG1tXLSK0GWsf2xHn_ifHhC-ZSMlOhotpBxQnQfdR9ysIaAjEYEALw_wcB&trk=6a4c3e9d-cdc9-4e25-8dd9-2bd8d15afbca&sc_channel=ps&ef_id=Cj0KCQiA67CrBhC1ARIsACKAa8TOlc-OBDyG1tXLSK0GWsf2xHn_ifHhC-ZSMlOhotpBxQnQfdR9ysIaAjEYEALw_wcB:G:s&s_kwcid=AL!4422!3!651751059777!e!!g!!amazon%20web%20services!19852662197!145019195737&all-free-tier.sort-by=item.additionalFields.SortRank&all-free-tier.sort-order=asc&awsf.Free%20Tier%20Types=*all&awsf.Free%20Tier%20Categories=*all) both offer free Linux virtual machines. Virtual machines, when accessed through a remote desktop viewer, function just like physical ones. [Microsoft's remote desktop viewer](https://apps.microsoft.com/detail/9WZDNCRFJ3PS?hl=en-US&gl=US) can be used to accessed VMs on Windows, though there are many other viewers available for download online. 
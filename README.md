# burnin
Well this should be an interesting first start in making my job easier. Hopefully.
Customers frequently order new workstations and after we receive those workstations, we go through a process of "burning" them in.
This process requires us to upgrade to windows 10 if machine was received with win7, run windows updates, install two monitoring agents, uninstall the preinstalled office 365, install a few third party apps, and possibly more depending on the customer.
I would like to use this project to make this process easier but first we might identify what we are up against here.
Windows updates are run using our internal Windows update server that is self maintained by executing a file hosted on an internal server.
The two agents are tools for monitoring, remote access, and anti virus. One is generic for all customers while the second is customer site specific.
Third party apps consist mainly of chrome, adobe reader dc, certain office version.
Ideally I would like a single local page that I can navigate to internally that will know what my current os is and go through this process with minimal effort. Eventually setting it and forgetting it would be ideal.

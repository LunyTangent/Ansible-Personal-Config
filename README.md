# Ansible-Personal-Config
Some personal Ansible code mostly for reference. This repo is not intended for actual use, but you can clone or fork it to make some changes for your environment.

I wrote this code with the intention of using it with ansible-pull rather than the usual ansible command. The reason for that is because it sets up a cron job to automatically pull the lastest version from github, which means I can make changes to the code without having to manually re-run it from a command machine against an inventory file I'd also have to maintain when I add new VMs or devices to the network. This also means that any laptops or machines that go offline for any reason will automatically update themselves with any new stuff I've added to this repo since the last time they were online.

If you do want run this as-is for some reason the command for that is "ansible-pull -U https://github.com/LunyTangent/Ansible-Personal-Config.git"
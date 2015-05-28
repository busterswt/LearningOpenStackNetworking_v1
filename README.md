# LearningOpenStackNetworking_v1

The purpose of this repository is to provide updates to the installation process documented in "Learning OpenStack Networking (Neutron)" - First Edition.

Since the release of OpenStack Kilo (or maybe even sometime before), the Havana repository for CentOS is no longer available. In addition, CentOS 6.5 has been replaced by CentOS 6.6. Because of this, readers will not be able to install the release of OpenStack documented in the book. I have hastily updated the process to install the Icehouse release on CentOS 6.6. The process documented in this repo currently configures ML2/Linuxbridge for flat and vlan network support only. Feel free to ping me and I will see what I can do to add in vxlan and OVS support as time allows.

The current book based on Havana/Icehouse and is available at Amazon at http://www.amazon.com/Learning-OpenStack-Networking-Neutron-Denton/dp/1783983302.

I am working on a second edition geared towards Juno/Kilo that may be ready later this year.

If you run into issues with the process documented within, please let me know and I'll see what I can do. As always, feel free to follow the deployment guides at http://docs.openstack.org, as they should be relatively up-to-date.


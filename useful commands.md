<details>

<summary>show system info</summary>

```
admin@Netlab-PA> show system info

hostname: Netlab-PA
ip-address: 10.255.255.128
public-ip-address: unknown
netmask: 255.255.255.0
default-gateway: 10.255.255.1
ip-assignment: dhcp
ipv6-address: unknown
ipv6-link-local-address: fe80::20c:29ff:fec9:b5b7/64
ipv6-default-gateway:
mac-address: 00:0c:29:c9:b5:b7
time: Sun Jun 29 04:46:46 2025
uptime: 0 days, 0:23:47
family: vm
model: PA-VM
serial: unknown
vm-mac-base: BA:DB:EE:FB:AD:00
vm-mac-count: 255
vm-uuid: 564D903C-CB33-D89C-877A-76476CC9B5B7
vm-cpuid: ESX:A3060B00FFFB8B1F
vm-license: none
vm-cap-tier: unknown
vm-cpu-count: 2
vm-memory: 8158328
vm-mode: VMware ESXi
cloud-mode: non-cloud
sw-version: 11.0.0
global-protect-client-package-version: 0.0.0
device-dictionary-version: 1-211
device-dictionary-release-date:
app-version: 8635-7675
app-release-date:
av-version: 0
av-release-date:
threat-version: 0
threat-release-date:
wf-private-version: 0
wf-private-release-date: unknown
url-db: paloaltonetworks
wildfire-version: 0
wildfire-release-date:
wildfire-rt: Disabled
url-filtering-version: 0000.00.00.000
global-protect-datafile-version: unknown
global-protect-datafile-release-date: unknown
global-protect-clientless-vpn-version: 0
global-protect-clientless-vpn-release-date:
logdb-version: 11.0.0
dlp: dlp-4.0.0
vm_series: vm_series-4.0.0
platform-family: vm
vpn-disable-mode: off
multi-vsys: off
operational-mode: normal
advanced-routing: off
device-certificate-status: None

admin@Netlab-PA>
```
</details>

<details>

<summary>request dhcp client management-interface renew</summary>

```
admin@Netlab-PA> request dhcp client management-interface renew
Warning: Performing DHCP Renew can cause firewall's management IP to change and access to firewall can be lost.  A console connection can be used to recover access if available. Do you wish to continue? (y or n)
DHCP: new ip 10.255.255.128 : mask 255.255.255.0
DHCP: new ip 10.255.255.128 : mask 255.255.255.0

Renew succeeded
admin@Netlab-PA>
```

</details>

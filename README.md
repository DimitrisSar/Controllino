<div align="center">
  <br>
  <b><a name="header"><h1 align="center" style="font-size:40px">Manage your Controllino v1</h1></a></b>
  <p style="font-size:15px">Be sure to :star: this repo so you can keep up to date on any daily progress!<br><br>
  <p style="font-size:30px"><b>Disclaimer:</b> Proceed with caution!</p>
  <p style="font-size:20px" align="justify">Using the information contained within this repository to modify your device will lead to <b>warranty violation !</b><br>
  The responsibility lies entirely with you if you damage/destroy your device or cause any other trouble.
  The purpose of this collection is to <b>share</b> information about managing your Controllino v1 device and not to cheat the Helium Network.
  No configuration found here will help you increase your mining rewards.  This depends entirely on your hotspot placement and antenna installation.<br><br></p>
</div>
<font size="3">
<div align="center"><a name="menu"></a>
  <h4>
    <a href="https://github.com/DimitrisSar/Controllino#hardware">
      Hardware
    </a>
    <span> | </span>
    <a href="https://github.com/DimitrisSar/Controllino#open">
      Open Chassis
    </a>
    <span> | </span>
    <a href="https://github.com/DimitrisSar/Controllino#backup">
      Backup SD & Enable SSH
    </a>
    <span> | </span>
    <a href="https://github.com/DimitrisSar/Controllino#p2p">
      P2P Variables
    </a>
    <span> | </span>
    <a href="https://github.com/DimitrisSar/Controllino#chain">
      Chain Sync
    </a>
    <span> | </span>
    <a href="https://github.com/DimitrisSar/Controllino#stats">
      Stats
    </a>
    <span> | </span>
    <a href="https://github.com/DimitrisSar/Controllino#scripts">
      Scripts
    </a>
    <span> | </span>
    <a href="https://github.com/DimitrisSar/Controllino#tips">
      Hints & Tips
    </a>
  </h4>

![Screenshot of Controllino v1 Header](https://raw.githubusercontent.com/DimitrisSar/Controllino/main/www/images/Controllino_v1.png)
<br><br>
|<--- Add intro text --->|<br>
</div>

<table align="center" border="0">
<tr ><td colspan="4">
<p align="center"><strong>Hardware Used</strong>
<a name="hardware" href="https://github.com/DimitrisSar/Controllino#header"><img align="right" border="0" src="https://raw.githubusercontent.com/DimitrisSar/Controllino/main/www/images/up_arrow.png" width="22"></a>
</td></tr>

<td align="center"><a href="https://www.raspberrypi.com/products/raspberry-pi-4-model-b/" target="_blank">Raspberry Pi 4B 8GB</a></td>
<td align="center"><a href="https://us.transcend-info.com/Embedded/Products/No-1043" target="_blank">Transcend 420T</a></td>
<td align="center" colspan="2"><a href="http://www.embit.eu/" target="_blank">Embit LoRa</a></td>

<tr>
<td align="center"><a href="https://www.raspberrypi.com/products/raspberry-pi-4-model-b/" target="_blank"><img border="0" src="https://raw.githubusercontent.com/DimitrisSar/Controllino/main/www/images/rPi4b8G.png" height="130" width="200"></a></td>
<td align="center"><a href="https://us.transcend-info.com/Embedded/Products/No-1043" target="_blank"><img border="0" src="https://raw.githubusercontent.com/DimitrisSar/Controllino/main/www/images/TS32GUSD420T.png" height="130" width="173"></a></td>
<td align="center"><a href="http://www.embit.eu/products/oem-gateways/emb-lr1302-mpci-e-prova/" target="_blank"><img border="0" src="https://raw.githubusercontent.com/DimitrisSar/Controllino/main/www/images/EMB-LR1302-mPCIe.png" height="130" width="200"></a></td>
<td align="center"><a href="http://www.embit.eu/products/oem-gateways/accessories/emb-raspi-lr130x-cape/" target="_blank"><img border="0" src="https://raw.githubusercontent.com/DimitrisSar/Controllino/main/www/images/EMB-RasPI-130x-Cape.jpg" height="130" width="200"></a></td>

<tr><td colspan="4" align="left">
|<-- Add some blah-blah about the Hardware -->|<br><br>

<details>
  <summary>Possibly add links to some external content</summary>
  <p align="center"><a href="https://youtu.be/BpJCAafw2qE" target="_blank">Raspberry Pi 4 Getting Started</a>
  <p align="center"><a href="https://youtu.be/8Ue1WDp3QoA" target="_blank">Make your own Gateway</a>
  </details><br>
</table>

<hr>

<table align="center" border="0">
<tr ><td colspan="4">
<p align="center"><strong>Open Chassis</strong>
<a name="open" href="https://github.com/DimitrisSar/Controllino#hardware"><img align="right" border="0" src="https://raw.githubusercontent.com/DimitrisSar/Controllino/main/www/images/up_arrow.png" width="22"></a>
</td></tr>

<td align="center">T15 Torx bit</td>
<td align="center">5mm Hex Female bit</a></td>
<td align="center"><a href="https://www.amazon.de/-/en/gp/product/B093FQH5WS" target="_blank">M2.5 Hex Spacers</a></td>
<td align="center">General Tools</a></td>

<tr>
<td align="center"><img border="0" src="https://raw.githubusercontent.com/DimitrisSar/Controllino/main/www/images/T15_bit.png" height="130" width="200"></a></td>
<td align="center"><img border="0" src="https://raw.githubusercontent.com/DimitrisSar/Controllino/main/www/images/5mm_Hex_bit.png" height="130" width="173"></a></td>
<td align="center"><a href="https://www.amazon.de/-/en/gp/product/B093FQH5WS" target="_blank"><img border="0" src="https://raw.githubusercontent.com/DimitrisSar/Controllino/main/www/images/M25_Spacers.png" ></a></td>
<td align="center"><img border="0" src="https://raw.githubusercontent.com/DimitrisSar/Controllino/main/www/images/General_Tools.jpg" height="130"></a></td>

<tr><td colspan="4" align="left">
<br>
To open the Controllino v1 Chassis, follow the steps below:<p><br>
<i>Step 1)</i> Unscrew the first 4 top T15 Torx screws using the Torx screwdriver bit.  You may sheer off the bottom part of the screw of the top threaded pillar.<p>
<i>Step 2)</i> Open the top cover and remove IPX antenna connector and the LoRa mPCIe card.  Lift the power connector from its socket<p>
<i>Step 3)</i> Gently remove the LoRa hat (lift slowly from both sides)<p>
<i>Step 4)</i> Using the 5mm Hex Female bit, secure the M2.5 15mm Spacers and unscrew the bottom screws.  Do not use pliers to hold the spacers because they may slip and damage the rPi board<p>
<i>Step 5)</i> Remove the rPi and take out the SD Card<p>
<i>Step 6)</i> Replace broken standoffs with new ones<p>
<p>&nbsp;</p>
<details>
  <summary>Pictures</summary>
  <p align="center"><img border="0" src="https://raw.githubusercontent.com/DimitrisSar/Controllino/main/www/images/Step1_Open_Chassis.png">
  <p align="center"><img border="0" src="https://raw.githubusercontent.com/DimitrisSar/Controllino/main/www/images/Step2_Open_Chassis.png">
  <p align="center"><img border="0" src="https://raw.githubusercontent.com/DimitrisSar/Controllino/main/www/images/Step3_Open_Chassis.png">
    <p align="center"><img border="0" src="https://raw.githubusercontent.com/DimitrisSar/Controllino/main/www/images/Step5_Open_Chassis.png">
  </details><br>
</table><hr><br><br>

<table align="center" border="0">
<tr ><td colspan="4">
<p align="center"><strong>Backup SD & enable SSH</strong>
<a name="backup" href="https://github.com/DimitrisSar/Controllino#open"><img align="right" border="0" src="https://raw.githubusercontent.com/DimitrisSar/Controllino/main/www/images/up_arrow.png" width="22"></a>
</td></tr>

<td align="center">micro SD Card Reader</td>
<td align="center"><a href="https://win32diskimager.org/" target="_blank">Win32 Disk Imager</a></td>
<td align="center"><a href="https://www.paragon-software.com/home/linuxfs-windows/" target="_blank">ext4 Mount Util</a></td>
<td align="center">Windows PC</a></td>

<tr>
<td align="center"><img border="0" src="https://raw.githubusercontent.com/DimitrisSar/Controllino/main/www/images/SD_Card_Reader.png" height="130" width="200"></a></td>
<td align="center"><img border="0" src="https://win32diskimager.org/wp-content/uploads/2020/05/Win_sel.png" width="173"></a></td>
<td align="center"><a href="https://www.paragon-software.com/home/linuxfs-windows/" target="_blank"><img border="0" src="https://www.paragon-software.com/wp-content/themes/paragon_3_test/image/Logo.svg" ></a></td>
<td align="center"><img border="0" src="https://raw.githubusercontent.com/DimitrisSar/Controllino/main/www/images/Windows_OS.png" width="200"></a></td>

<tr><td colspan="4" align="left">
<br>
To backup the contents of your SD Card, follow the steps below:<p><br>
<i>Step 1)</i> Connect your SD Card to your Windows PC using a micro SD Card reader<p>
<i>Step 2)</i> Download Win32 Disk Imager and install it<p>
<i>Step 3)</i> Choose a location to store the image file and select "Read" to initiate the backup<p>
<i>Step 4)</i> Create and place a blank file named <b>ssh</b>  (no file extension) onto the boot partition of the SD Card<p>
<i>Step 5)</i> Download and install Paragon ExtFS <b>trial</b> edition and install it<p>
<i>Step 6)</i> Mount the ext4 partition and create a folder <b>.ssh</b> in directory /home/pi/<p>
<i>Step 7)</i> Create a text file <b>authorized_keys</b> (no file extension) within directory /home/pi/.ssh/ and place your public ssh key inside.  See useful links below for more details on how to setup SSH keys</p>
<i>Step 8)</i> Unmount the SD Card, place it back into the Controllino v1 and power up the hotspot</p>
<i>Step 9)</i> Use any SSH client to authenticate with username: <b>pi</b> using Public Key method</p>
<br>
<details>
  <summary>Useful Links</summary>
  <p align="center"><a href="https://howchoo.com/g/nmexndnlmdb/how-to-back-up-a-raspberry-pi-on-windows" target="_blank">How to Back Up a Raspberry Pi SD Card in Windows</a>
  <p align="center"><a href="https://pimylifeup.com/raspberry-pi-ssh-keys/" target="_blank">How to Setup Raspberry Pi SSH Keys</a>
  <p align="center"><a href="https://www.raspberrypi.com/documentation/computers/remote-access.html#enabling-the-server" target="_blank">Enabling the SSH Server (headless setup)</a>
  <p align="center"><a href="https://www.tomshardware.com/reviews/raspberry-pi-headless-setup-how-to,6028.html" target="_blank">Headless Raspberry Pi</a>
</details><br>
</table><hr><br><br>

<table align="center" border="0">
<tr ><td colspan="4">
<p align="center"><strong>P2P Peer Book Size Increase</strong>
<a name="p2p" href="https://github.com/DimitrisSar/Controllino#backup"><img align="right" border="0" src="https://raw.githubusercontent.com/DimitrisSar/Controllino/main/www/images/up_arrow.png" width="22"></a>
</td></tr>

<tr><td colspan="4" align="left">
<br>
<p>Based on the work of: <a href="https://github.com/inigoflores">https://github.com/inigoflores/</a></p>
<br>

P2P Communications are used for several purposes by the miner.  This will change when HIP55 will be fully implemented and the new light hotspots will emerge.

Until then, you can try to increase the parameters for P2P comms to see if you get less warnings & errors of the following type:

<b>/var/log/console.log:</b>

```console
2022-03-02 11:25:18.707 8 [warning] <0.23459.1>@miner_onion_server:send_witness:
{243,37} failed to dial challenger "/p2p/<hotspot_id>": not_found"
```

<b>/var/log/error.log:</b>

```console
2022-03-02 11:26:47.667 [error] <0.23303.1>@miner_onion_server:send_witness:
{207,5} failed to send witness, max retry
```

To modify the P2P parameters, follow the steps below:<p><br>
<i>Step 1)</i> Take a backup of your existing config file<p>

```console
root@controllinohotspot:~# cd /home/pi/docker_config/
root@controllinohotspot:/home/pi/docker_config# cp docker.config docker.config.old
```

<p>
<i>Step 2)</i> Edit <b>/home/pi/docker_config/docker.config</b> using the text editor of your choise (i.e. vim, nano, etc)<p>

```console
root@controllinohotspot:~# vi /home/pi/docker_config/docker.config
```

<p>
<i>Step 3)</i> Add the following 3 new options in the section <b>blockchain</b> of the config file:<p>

```json
     {peerbook_update_interval, 180000},
     {max_inbound_connections, 50},
     {outbound_gossip_connections, 10}
```
<p>
Careful when adding these options to fix the commas on the existing ones otherwise the miner will not start.  Save the file and exit the editor.

<b>Important Note:</b> The config file will be overwitten when the miner is upgraded to a new release or when you perform `Clear Miner Data` from the Controllino Dashboard.  You will have to redo the changes in `/home/pi/docker_config/docker.config` following the miner update/clear.

<details>
<summary>Complete docker.config file</summary>
  <p align="center"><img border="0" src="https://raw.githubusercontent.com/DimitrisSar/Controllino/main/www/images/docker_config.png">

</details><br>
<i>Step 4)</i> Restart miner<p>

```console
root@controllinohotspot:~# docker restart miner
```
<i>Step 5)</i> Check new Peer Book info:<p>
```console
root@controllinohotspot:~# docker exec miner miner peer book -s
root@controllinohotspot:~# docker exec miner miner peer book -c
```
You can also refresh the peer with:<p>
```console
root@controllinohotspot:~# docker exec miner miner peer refresh /p2p/<peerid>
```
<br>
<details>
  <summary>Useful Info</summary>
  <p align="center"><a href="https://docs.helium.com/mine-hnt/full-hotspots/become-a-maker/basic-miner-operation/" target="_blank">Basic Miner Operation</a>
  <p align="center"><a href="https://github.com/inigoflores/pisces-p100-tools/tree/main/Not_Found_Fix" target="_blank">Challenger Not Found Peerbook Size Increase Fix</a>
  <p align="center"><a href="https://github.com/inigoflores/helium-miner-log-analyzer" target="_blank">Helium Miner Logs Analyzer</a>
  <p align="center"><a href="https://github.com/helium/miner/blob/master/config/sys.config" target="_blank">Default Helium Miner Config</a>
  </details><br>
</table><hr><br><br>

<table align="center" border="0">
<tr ><td colspan="4">
<p align="center"><strong>Real-time performance statistics</strong>
<a name="stats" href="https://github.com/DimitrisSar/Controllino#p2p"><img align="right" border="0" src="https://raw.githubusercontent.com/DimitrisSar/Controllino/main/www/images/up_arrow.png" width="22"></a>
</td></tr>

<tr><td colspan="4" align="left">
<br>
<p>Using <a href="https://github.com/netdata/netdata">Netdata</a> monitoring agent, we will collect thousands of metrics from our Controllino v1 system (hardware, containers, and applications) with zero configuration.<p>

Because it's free, open-source, and requires only 1% CPU utilization to collect thousands of metrics every second, Netdata is a superb single-node monitoring tool.<p><br>

To install the netdata agent on your Controllino v1, follow the steps below:<p>
<i>Step 1)</i> (optional) Update your Rasbpian packages to the latest versions<p>

```console
root@controllinohotspot:~# apt update && apt upgrade
```

<p>
<i>Step 2)</i> Install Netdata, including all dependencies, disable telemetry, and get automatic stable updates<p>

```console
root@controllinohotspot:~# wget -O /tmp/netdata-kickstart.sh \
https://my-netdata.io/kickstart.sh && sh /tmp/netdata-kickstart.sh \
--stable-channel --disable-telemetry
```

<p>
<i>Step 3)</i> Modify the netdata agent config file (<b>/etc/netdata/netdata.conf</b>) parameter <b>"bind to ="</b> (from 127.0.0.1 to 0.0.0.0) to allow remote connections:<p>

```console
[global]
    run as user = netdata

    # the default database size - 1 hour
    history = 3600

    # some defaults to run netdata with least priority
    process scheduling policy = idle
    OOM score = 1000

[web]
    web files owner = root
    web files group = netdata

    # by default do not expose the netdata port
    bind to = 0.0.0.0
```

<i>Step 4)</i> Enable the netdata service for auto-startup<p>

```console
root@controllinohotspot:~# systemctl enable netdata
```

<i>Step 5)</i> Access the local netdata dashboard to see your node's real-time metrics by browsing to `http://NODE:19999`, replacing `NODE` with the `IP address` of your Controllino<p>

  <p align="center"><img border="0" src="https://user-images.githubusercontent.com/1153921/80825153-abaec600-8b94-11ea-8b17-1b770a2abaa9.gif">

<p>
Enjoy the metrics!

<b>Multiple Nodes:</b> You can use <a href="https://www.netdata.cloud/">Netdata Cloud</a> to have a single view of all your Controllinos running the netdata agent.  You can customize key metrics from any number of Controllino monitored nodes and seamlessly navigate to any node’s dashboard for granular performance troubleshooting.

<br>
<details>
  <summary>Useful Info</summary>
  <p align="center"><a href="https://learn.netdata.cloud/docs/agent/packaging/installer" target="_blank">Official Netdata Installation Guide</a>
  <p align="center"><a href="https://learn.netdata.cloud/docs/configure/nodes" target="_blank">Official Netdata Configuration Guide</a>
  <p align="center"><a href="https://learn.netdata.cloud/docs/cloud/visualize/dashboards" target="_blank">Build new dashboards</a>
  <p align="center"><a href="https://github.com/netdata/netdata/blob/master/docs/monitor/configure-alarms.md" target="_blank">Configure health alarms</a>
  <p align="center"><a href="https://github.com/netdata/netdata/blob/master/docs/export/external-databases.md" target="_blank">Export metrics to external time-series databases</a>
  </details><br>
</table><hr><br><br>

<p align="left"><strong><a name="software"></a>Notable Software on my Laptop:</strong><br>

* [Debian 11](https://www.debian.org/download) - It all starts here.
* [Docker](https://docker.com) - Docker
* [XShell 7](https://www.netsarang.com/en/xshell/) - The industry’s most powerful SSH client
* [Netdata](https://github.com/netdata/netdata) - Infrastructure monitoring and troubleshooting

<br>
<br>
<p align="left"><strong>Todo List <a name="todo" href="https://github.com/DimitrisSar/Controllino#stats"><img align="right" border="0" src="https://raw.githubusercontent.com/DimitrisSar/Controllino/main/www/images/up_arrow.png" width="22" ></a></strong><br>

The [issues section](https://github.com/DimitrisSar/Controllino/issues?q=is%3Aissue+is%3Aopen+sort%3Aupdated-desc) on github is where I store all my wishful ideas and future enhancements.
Feel free to join the conversations there.<br><br>

<hr>
<br>
<br>

<p align="left"><strong>Still have questions?</strong>

<p align="center"><strong>Join us at the Controllino Discord :</strong>
<p align="center">
  <a href="https://discord.gg/z8kxkgMn44"><img src="https://raw.githubusercontent.com/DimitrisSar/Controllino/main/www/images/Discord_Logo.png" height="40" width="145" alt="Discord server"></a>
</p>

<p align="center">
<a target="_blank" href="https://www.buymeacoffee.com/DimitrisS"><img src="https://www.buymeacoffee.com/assets/img/BMC-btn-logo.svg" alt="Buy me a coffee"><span style="margin-left:5px">You can buy me a coffee</span></a><a target="_blank" href="https://www.buymeacoffee.com/DimitrisS"><img src="https://www.buymeacoffee.com/assets/img/BMC-btn-logo.svg" alt="Buy me a coffee"></a>
<br>
<a name="bottom" href="https://github.com/DimitrisSar/Controllino#todo"><img align="right" border="0" src="https://raw.githubusercontent.com/DimitrisSar/Controllino/main/www/images/up_arrow.png" width="22" ></a><br>
</p>

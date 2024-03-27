# Warp and Warp +
#### This is a trick to create a permanent and unlimited configuration that can only be run and connected with the special [Hiddify-next](https://github.com/hiddify/hiddify-next/releases) client program.
 To create this configuration, I have placed a default configuration file in JSUN format here. You should put the output of the following commands in the places I explained and finally add the entire text as a profile.

---------------------------------------------------------------------
### 2. Android, Linux and Mac
###  Multi-platform IP peer WARP optimization + unlimited generation of WARP-Wireguard configurations.

1. Copy the [Config file](WarpAnWarp-/TwoWarp+_endip.json) to an editor.

2. Run the below command in the termux(Android Shell), linux or mac.The command for finding the clean IP/Ports is from Warp Cloudflare.
```
bash <(curl -fsSL https://raw.githubusercontent.com/Ptechgithub/warp/main/endip/install.sh)
```
3. Replace the two IP/Ports of the copied config file (Step 1) with one of the resulted IP/Port of the step 2.
4. Run the below instruction two times to acquire two free Warp accounts. Each time you run it, writes 3 lines including IPv6, private key and reserved bytes. You can replace the corresponding values of the copied config (Step 1) with these values.
```
curl -sL "https://api.zeroteam.top/warp?format=sing-box" | grep -Eo --color=never '"2606:4700:[0-9a-f:]+/128"|"private_key":"[0-9a-zA-Z\/+]+="|"reserved":\[[0-9]+(,[0-9]+){2}\]'
```
5. Finally, you need to apply the file resulting from the changes you made in Hidify Next.
Open the file with any editor you have and copy all its text.
Open the Hidify app and click the + icon and select from clipboard.
The connection profile is now created in the app. By pressing the connection button, you can easily go through the filtering steps and enjoy free internet at a suitable speed.
--------------------------------------------------------------
### 3. Windows platform warp official client prefers peer IP application

Note: The default can only be operated on the C drive or desktop

How to use: Unzip the download (WIN WIN WIRP optional IP-V23.11.15.zip) file,
Must read:
1. Preferred IP ports can be used for wireguard clients
2. Remember that the preferred operations on each platform must be performed without an agent.

The following two warp official client operation methods can be executed at any location without dragging files into the warp official client installation directory.

Warp official client operation:
1. Manual method:
1. First open the warp official client and ensure that the device ID has been generated and is closed.
2. Double-click the 'Manual Method 1' file first, and generate the result.csv file after execution (the IP port can be extracted to the wireguard client)
3. Double-click the 'Manual Mode 2' file again and copy the top IP port in the result.csv file into the window.
4. Start the warp official client and it will be successful.

2. Automatic mode:
1. First open the warp official client and ensure that the device ID has been generated and is closed.
2. As demonstrated in the video tutorial (the automatic method can easily cause the protection software to warn you that it is poisonous, just add the 'automatic method' file to the whitelist)


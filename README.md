# Welcome To How To Secure Your Router.

- here in this case we had used a syrotech router for this demonstration purpose.

- you can use any of the router you have most of the settings will be same.

- please make sure to study the documentation provided by the router or reffer online for more details.

- the router showed here is a typical Indian router given by the ISP(internet service provider).

## prerequisites You Need To Have.

1. - [x] router(any router)
2. - [x] A laptop/Desktop/mobile.

### Loging Into The Router.

- please see the back side of the router you will find a small sticker with the default IP address and default credentials.

- in the most of the cases these two IP address are the default IP address.

```
192.168.0.1
```

```
192.168.1.1
```

- please copy the Ip address And paste it your favorite browser.

- now you see a login page.

- ![login page](https://github.com/yakkalasaisumanth/Home-Security-Using-Router/blob/main/images/loginpage.png)

- most of the cases the default credentials are as bellow.

- username
```
admin
```

- password
```
admin
```

- username
```
user
```

- password
```
user
```

### After Successful login You Must see Your Router Page.

- this is my router home page.

- ![1st page](https://github.com/yakkalasaisumanth/Home-Security-Using-Router/blob/main/images/1st%20page.png)

- as you can see it shows the device basic info 

- it shows the information like.
 1. device model.
 2. device ID.
 3. hardware 
 4. software version.

- in here make sure to check the software version is up to date.

- ypu can check it with simply googling it.

- you can simply search by typing the router company and visiting the router company website.

- now in router page select the model of your router and download.

- for suppose your router shows a version of 2.0 and the google says v 3.0 is latest then download the v 3.0 from official website and install.

- installing is very easy just go to the management tab and select update software by uploading the file.

- make sure in this process there should not occur a power cut or your router may become unusable.

- as my router is up to date i am skipping this step.

### Now Open The Network Tab.

- network page looks like this.

- ![network page](https://github.com/yakkalasaisumanth/Home-Security-Using-Router/blob/main/images/lan%20settings.png)

- ![network firstpage](https://github.com/yakkalasaisumanth/Home-Security-Using-Router/blob/main/images/network%20first%20page.png)

- now you can see a lot of information, don't worry we will break it down for you.

1. the first thing we see is a IP address and subnet mask.

2. in my case the IP address in 192.168.1.1 and subnet is 255.255.255.0

3. note do not change this IP address as it is given by the ISP. changing it will cause a internet problem.

4. how ever you can change subnet mask if you want like 255.0.0.0, 255.255.0.0, 255.255.255.0, 255.255.255.255, etc,. 

5. now coming up to the DHCP settings DHCP means dynamic host configuration protocol which assigns a devices with a dynamically created public IP address to connect to the internet.

6. which is a best setting we can make to connect to the internet.

7. there is also a static IP which is assigns a fixed IP to the Devices.

8. as the IP address never changes it may have a great risk of visibility of the device information on internet.

9. we can set the IP address of the DHCP server like shown in the image start IP 192.168.1.2 and end IP 192.168.1.254

10. you can also set the start IP and End IP as 172.168.1.2  to 172.168.1.254 if your primary ip starts with 172.168.1.1 or similar.

11. now for the lease time i have set it to the one day which means if DHCP server assigned a IP for a device it will expire in one day.

12. this setting is very essential so that a device connects to the internet it changes its ip daily.

13. now talking about DNS we have two options.
 1. AUTO DNS
 2. Manual DNS.

14. what is DNS?. 

15. DNS means Domain name server it helps to connect to the internet.

16. most people use auto DNS as it is easier to setup and readily available.

- ![DHCP LOGO](https://github.com/yakkalasaisumanth/Home-Security-Using-Router/blob/main/images/dhcp%20config.png)

17. in my case i have opted manual DNS ans set it to 8.8.8.8 which is google DNS you can also set it as 0.0.0.0 or 8.8.4.4, etc,.

- ![lan dns](https://github.com/yakkalasaisumanth/Home-Security-Using-Router/blob/main/images/lan%20dns.png)

18. you can select the LAN DNS Shown IN the image.

19. I have set it to hgwproxy you can set it to WLAN or static also.

20. setting WLAN requires the WLAN configuration which we will discuss later.

- ![lan dns1](https://github.com/yakkalasaisumanth/Home-Security-Using-Router/blob/main/images/lan%20dns%202.png)

21. we can also assign a mac address to specific IP if we have a lot of devices connecting to the network.

- ![MAC IP](https://github.com/yakkalasaisumanth/Home-Security-Using-Router/blob/main/images/configuring%20mac%20to%20static%20ip.png)

22. it helps in identifying the device easily but you cannot set a DHCP START IP and END IP.if you enable this setting.

- ![IP MAC](https://github.com/yakkalasaisumanth/Home-Security-Using-Router/blob/main/images/configured%20the%20mac%20to%20ip.png)

23. if you have configured the IP You see the Following screen as showed in the above image.

24. you can set the LAN ipv6 settings as you like it has two options for me.
 1. wandelegate
 2. static

25. we can also choose the prefix of the ipv6 from here i have selected wandelegate. because it is better than static or fixed.

-![LAN ipv6](https://github.com/yakkalasaisumanth/Home-Security-Using-Router/blob/main/images/lan%20ipv6.png)

26. that's it for the LAN settings. if want to modify any lan setting please make sure you have the relevant document with you and you have some networking knowledge.

### WLAN Settings.

- ![WLAN settings](https://github.com/yakkalasaisumanth/Home-Security-Using-Router/blob/main/images/wlan%20settings.png)

1. here comes the settings we are waiting for most of the home users uses WI-FI rather than LAN.

2. setting up WLAN is very easy.

3. First You have to select the band of the WI-FI in my case it is 2.4 GHz(B + G + N)

4. in most of the cases you see only 2.4 GHz band routers only some use dual band routers i.e,. 2.4 ans 5 GHz routers.

5. we are looking into 2.4GHz router only but don't worry the settings of 5 GHz are also the same you can easily follow along.

6. then comes the mode it is a optional setting you may or may not find this setting any way leave it default.

7. now comes SSID which is the wireless network display name please provide a name you want to display.

8. disable SSID interface just hides the SSID and Block WLAN access to web will block the router form connecting to the internet.

9. disable broad cast  will disable from broadcasting a channel.

- ![disable SSID](https://github.com/yakkalasaisumanth/Home-Security-Using-Router/blob/main/images/blocking relay.png)

10. if you hide the SSID your mobiles can't connect to the network. and even a person who is monitoring traffic cannot see your wireless device.

11. block relay is used for bitcoin related queries where if your network gets compromised enabling this feature will save your device from connecting to the multiple crypto sites.

- ![block relay](https://github.com/yakkalasaisumanth/Home-Security-Using-Router/blob/main/images/blocking relay.png)


12. now other settings you can increase or decrease the channel width. this setting lets you increase and decrease the coverage area.

13. you can setup a channel number if you want.

14. here comes the important setting called client number .

15. where you can set a limit of devices connecting to the router.

16. after configuring the settings please click apply changes to apply.

17. if you go to WLAN advanced settings we can find a setting called multiple SSID.

18. Which provides a user to create multiple SSID for analyzing traffic from each WLAN separately.

19. now you can create multiple SSID as you wish. we have already discussed about block relay and broadcast settings.

20. what is WMM?. it is WI-FI multimedia you can enable or disable this setting. if you want to connect a multimedia device to the router you have to enable it.

- ![multi SSID](https://github.com/yakkalasaisumanth/Home-Security-Using-Router/blob/main/images/config%20multipule%20ssid's.png)

21. configuring each WLAN settings.

- ![WLAN settings](https://github.com/yakkalasaisumanth/Home-Security-Using-Router/blob/main/images/config%20each%20wlan%20settings.png)

22. now you can change the WLAN for configuring each one of them example.

- ![WLAN change](https://github.com/yakkalasaisumanth/Home-Security-Using-Router/blob/main/images/changing%20wlan.png)

23. now choose the encryption type in my case the best available encryption is wpa2 mixed if you have wpa3 choose that.

- ![WLAN Encryption](https://github.com/yakkalasaisumanth/Home-Security-Using-Router/blob/main/images/selecting%20the%20encryption%20type.png)

24. for wpa and wpa2 cipher please chose the AES option because it is the best encryption technique.

25. now in pre shared key select the passphrase and in give your desired most secure password.

26. now click apply changes to apply these settings.

27. you can configure all the WLAN's as the same.

### Security Tab

1. first setting is the WLAN access configuration.

- ![WLAN access](https://github.com/yakkalasaisumanth/Home-Security-Using-Router/blob/main/images/security%20tab.png)

2. you can see tow settings URL filtering and filter mode.

3. now enabling the URl filtering option user can specify the URL's.

4. in filter mode if he selects the black list then the URLs specified by the user will be blocked and no one can access them.

5. if he selects the white list option than he can access only the specified URLs.

- ![URL filtering](https://github.com/yakkalasaisumanth/Home-Security-Using-Router/blob/main/images/enabling%20url%20filtering.png)

6. now comes to firewall in most of the cases the best settings are pre applied but if you want to modify you can do so.

7. in my case the firewall is set to medium and i have changed to high accordingly.

- ![firewall settings](https://github.com/yakkalasaisumanth/Home-Security-Using-Router/blob/main/images/setting%20up%20default%20firewall.png)

8. but we cannot create our own firewall rules in the router to do it we must setup a home lab or do a dd-wrt to the router which only some routers support.

9. now comes mac filtering.

10. this setting allows the specified mac users only to connect to the network.

- ![mac filtering](https://github.com/yakkalasaisumanth/Home-Security-Using-Router/blob/main/images/mac%20filtering.png)

### Application Settings.

1. DDNS(dynamic domain name search) which maps a dynamic IP address to a static IP address.

- ![DDNS Settings](https://github.com/yakkalasaisumanth/Home-Security-Using-Router/blob/main/images/ddns%20setup.png)

2. this setting is used to search details accordingly like the host name, user name, server, interface, etc,. 

3. which helps network admins to easily access the logs.


4. if you do not have any knowledge about the DDNS. please leave it as default.

5. and hit save/apply.

6. the settings will be updated.

### Management Settings.

1. the  most important settings.
 1. user management.
 2. device management.

- ![management settings](https://github.com/yakkalasaisumanth/Home-Security-Using-Router/blob/main/images/ddns setup.png)

2. here a user can ***Change The Default Credentials***

3. like username and password.

4. please change the default username and password.

5. and hit save/apply.

6. the settings will be updated.

7. device management is where a user installs the software downloaded from the internet. as discussed in the beginning.

8. and hit save/apply to save/apply settings.

### Save & Reboot.

1. now select the save and reboot option to save the entire settings made and rebooting the router.

2. please wait for some time to start the router.

3. now your home router or network is secured.

4. please keep in mind that this is not the best security but we can mitigate so many attacks like capturing, brute forcing, unauthorized devices, harmful websites,etc,.

#### Thank You For Reading The Entire Article If like The Article Please ***Comment Like***.

#### If You Have Any Suggestions Please Let Me Know.

#### If You Are Facing Any Issue Please Post it In The Issues Section.

##### Once Again Thank you All For Your Valuable Time.
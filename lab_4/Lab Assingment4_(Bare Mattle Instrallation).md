<center>
![](http://i.imgur.com/3bJqTvL.jpg)
</center>
<br>
</br>
####<center>**SRI LANKA INSTITUTE OF INFORMATION TECHNOLOGY**</center>
 
###<center>**Enterprise Standards and Best Practices for IT Infrastructure**</center>                                                                      
                          

####<center>_4th Year 2nd Semester 2014_<center>


<br>
</br>

------------------------------------------------------------------------




#####Name: Fernando W.W.S.D

#####SLIIT ID: IT13032616

#####Practical Session: WD Friday

#####Practical Number: complete installation of ESXi 5 and the vSphere Client.(Lab-4)

#####Date of Submission: 17.08.2016



---------------------------------------------------------------------------
<br>
</br>
###Title :complete installation of ESXi 5 and the vSphere Client 
<br>
</br>

1) Need to add _new virtual machine on top of the current Operation System_.First open the VMware player.And click on **new virtual machine**.

![](http://i.imgur.com/vJgUe4E.png)


2) Then need to _install the baremetal OS_. Browse the baremetal installer to the **installer disk image file**.

![](http://i.imgur.com/CukZ95Q.png)

![](http://i.imgur.com/HWOCoAI.png)

![](http://i.imgur.com/T6kNSZC.png)

![](http://i.imgur.com/nDVndCx.png)

![](http://i.imgur.com/EpL3XmU.png)


4) Then click on **next button**.

![](http://i.imgur.com/ae6d5og.png)


5) Choose Store virtual disk as a _single file_. go **next**

![](http://i.imgur.com/UKK2Ubr.png)


6) Then click on **finish**.

![](http://i.imgur.com/uJ67l8f.png)


7) you start your server. From this menu, choose the _first option to start the ESXi 5 installer_.

After you choose the installation option, the installer provides you with a window that details the **status of each file** that needs to be loaded.

![](http://i.imgur.com/XDzMWQB.png)


8) Below, you can see a screen that shows you some information _about your server_, including the **processor type** and **system RAM**.

![](http://i.imgur.com/1Dg497D.png)


9) Then you can see a dialog _Welcome to the VMware ESXI Installation_ and to continue with the installation, **press Enter** on your keyboard.

![](http://i.imgur.com/BJCuWXd.png)


10) Then you can see the _End user license agreement_ to accept the agreement **press F11**.

![](http://i.imgur.com/Eo9KwmI.png)

![](http://i.imgur.com/wJ6Zz5C.png)


11) Then we have to _choose a location to install ESXi 5_.
you can see that I have a single 40 GB volume from which to choose as an install location on my machine.Then **press Enter**. 

![](http://i.imgur.com/LrnyEl9.png)


12) As the keyboard layout _choose the US default option_.**press Enter**.

![](http://i.imgur.com/lgERU74.png)


13) Then provide a _password_ for the root user account.**press Enter**.

![](http://i.imgur.com/5pOwYpU.png)


14) Then the _ESXi installer_ scans the system to get additional information.

![](http://i.imgur.com/SpVCG7S.png)


15) Then ask to confirm install.**Press F11 button** to install.

![](http://i.imgur.com/k93r1I5.png)


16) _installation status_ will be shown next.

![](http://i.imgur.com/C7lGCjm.png)


17) Then the installation complete dialog box will be _shown to Reboot_ ,**press Enter**.

![](http://i.imgur.com/rCpSa9U.png)


18) Get the **IP address** shown in below.

![](http://i.imgur.com/57s9xBO.png)


19) Get the _command prompt_ and type ping **192.168.79.131**.

![](http://i.imgur.com/ClIy6je.png)


20) then you can see the _replies getting from the server_.

![](http://i.imgur.com/mMe293Z.png)


21) Install the **vSphere Client**.

Get the _IP address_ and search in a web browser.There you can _download_ the **vSphere client**.

![](http://i.imgur.com/ljqGf3r.png)

![](http://i.imgur.com/ammXeW0.png)

![](http://i.imgur.com/3ZlnwzA.png)

![](http://i.imgur.com/txEVdYU.png)

![](http://i.imgur.com/UPdRj0S.png)

![](http://i.imgur.com/0iKYEgZ.png)


22) Execute the _client software installation routine_.

![](http://i.imgur.com/l3EobJd.png)

![](http://i.imgur.com/7P0nR22.png)


23) Then **VMware vSphere** client is installing.

![](http://i.imgur.com/EqB8HTw.png)


24) Then click on **finish button**.

![](http://i.imgur.com/WOFmWJa.png)


25) You’ve installed the **hypervisor – ESXi5 and a management tool – vSphere Client**.

Start the **vSphere client**.

Provide the _ip address_ for your **ESXi5 host** and also provide the _root user name and password_ that you specified during the setup of your server.

![](http://i.imgur.com/9IqEes9.png)


26) This is the _interface_ after logging to the **VMware vSphere Client**.

![](http://i.imgur.com/L2N7A9a.png)


27) Then click on the **Inventory**.Then there are several tabs.Getting started tab is in this _interface_.

![](http://i.imgur.com/gLwDYvZ.png)


28) **Summary tab**.

![](http://i.imgur.com/jTQvbdO.png)


29) **Virtual machines tab**.

![](http://i.imgur.com/GChco2b.png)


30) **Resource allocation tab**.

![](http://i.imgur.com/iVebLsF.png)


31) **Performance tab**.

![](http://i.imgur.com/e88hzYx.png)


32) **Configuration tab**.

![](http://i.imgur.com/9nRq4h3.png)


33) **Local users and groups tab**.

![](http://i.imgur.com/VdXhGIU.png)


34) **Events tab**.

![](http://i.imgur.com/W95I6KP.png)


35) **Permissions tab**.

![](http://i.imgur.com/XHyo7Ze.png)


36) In _summary tab_, there is a resource called **storage**.right click on the _database and select Browse data store_.

![](http://i.imgur.com/VmGVEYz.png)


37) In data store browser, there is an icon in navigation pane.(_4th icon_).
click on that icon and **select Upload File**.

![](http://i.imgur.com/hUea8h9.png)


38) select the available _linux/windows image file_.
Here I was uploaded the **kali linux image file** to the data store.

![](http://i.imgur.com/cRFgXor.png)

![](http://i.imgur.com/nhbOHpf.png)

![](http://i.imgur.com/6wlHOGM.png)


39) Then right click on the **ip address** shown in the top left corner.Select _New virtual Machine_.

![](http://i.imgur.com/mOXNuNh.png)


40) Then we create a new virtual machine using usual steps.Choose **Typical**.
Then **click on next**.

![](http://i.imgur.com/FNr8Fzq.png)


41) Give a **specific name** for this virtual machine.

![](http://i.imgur.com/oiA08iU.png)


42) Then choose the _data store_.Then **click on next**.

![](http://i.imgur.com/GW0xzbz.png)


43) Specify the _guest operating system_ to use with this virtual machine. I choose the **Linux** because I chose the **kali linux image file**.Click **next**.

![](http://i.imgur.com/QKPQsyY.png)


44) Specify the Adapter as **E1000** and **tick the Connect at power on**.
The E1000 is an emulated version of the Intel 82545EM Gigabit Ethernet adapter. Not all guest operating systems include support for this adapter.

![](http://i.imgur.com/klBkO36.png)


45) Specify the **virtual disk size** and **provisioning policy**.As the Provision I selected the _Thin provision_.Then **next**.

![](http://i.imgur.com/CI3SUQh.png)


46) Then **click next**.

![](http://i.imgur.com/4vs4d8e.png)


47) Then you can see the _kali_linux instance has been created under the IP address top left corner_.Right click on that instance and **go to Edit Settings**.

Then click on the **CD/DVD drive 1**.In the right side you can see the Datastore _ISO file_.**Tick on that and browse the kali linux image file** inside the datastore1.

![](http://i.imgur.com/YXKmLJ2.png)

![](http://i.imgur.com/dGt59Lk.png)

![](http://i.imgur.com/izbBUgR.png)

![](http://i.imgur.com/JiXnh0a.png)

![](http://i.imgur.com/YGPjj1H.png)


48) After that click on **power on the Virtual machine**.

![](http://i.imgur.com/slqACMy.png)


49) Then go to _Getting started tab_ and Start the virtual machine.
Then go to **Console tab**. Then you can see the** kali_linux virtual machine is getting started** to work.

![](http://i.imgur.com/RVpzIcq.png)

![](http://i.imgur.com/1XiVoqG.png)

![](http://i.imgur.com/ypTq90s.png)
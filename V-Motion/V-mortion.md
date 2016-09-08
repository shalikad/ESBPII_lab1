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

#####Practical Number: V-Motion Assignment(lab-5)

#####Date of Submission: 10.09.2016



---------------------------------------------------------------------------
<br>
</br>
###Title : V-Motion Assignment
<br>
</br>

###Description:
 
V-Motion is the tool with which active virtual systems can be migrated from one **ESX-host to another** without any interruption to the virtual machines themselves or to their provided services. With **vSphere 5.x** previous limits on simultaneous migrations of virtual machines on **an ESXi-host- and datastore-basis** have been lifted.

1)
Requirements:

####i)Having a Virtual Center.
 
####ii) Have physical servers with ESXi installed.
 
####iii)Having a Gigabit network cable to connect from one server to another     directly.

![](http://i.imgur.com/YMhgz2R.jpg)

2) First click on **configuration tab** and then go to the _networking_.
Then click on _Add networking_ to create the **VSwitch**.

![](http://i.imgur.com/2ZuAp5N.jpg)

3) Select **VMKernal** and click on _next_.

![](http://i.imgur.com/WKRpCso.jpg)

4) Then making a network card or cards that have connected from one server to another.(in my case **vmnic2** )
Then click on _next_.
Set **use this port group for vMotion**.And put the **Vmotion** to the label network.

![](http://i.imgur.com/s7zTEyZ.jpg)

5)Then set **Use the following IP setting**
**IP Address**:192.168.1.101
**Subnet mask**:255.255.255.0
Click on _next_.

![](http://i.imgur.com/imieD62.jpg)

6)Click on _Finish_.

![](http://i.imgur.com/40Lz1VZ.jpg)

7)Then can see they have created a new virtual switch with Vmotion.

After connect to _another server involved_.

Then select the tab **Configuration-> Network Adapters** and see that have visibility of _new connections_. 

After can see the tab **Configuration -> networking**

Then click on Add Networking to create the **vSwitch**.

![](http://i.imgur.com/JpkSmbA.jpg)

8)Select **VMKernal** and click on _next_.

![](http://i.imgur.com/GM96yHY.jpg)

9)Making a network card and or cards that have connected from one server to another(in my case **vmnic2** .And click on _next_.

![](http://i.imgur.com/hvLhQar.jpg)

10) Set **Use this port group for VMotion**.And put the **Label Network** as **Vmotion**.

![](http://i.imgur.com/pvc4lXg.jpg)

11)Set **Use the following IP setting**.

**IP Address**:192.168.1.102

**Subnet Mask**: 255.255.255.0

Click on _next_.

![](http://i.imgur.com/UF6pYCJ.jpg)

12)Click on _finish_.

![](http://i.imgur.com/izwzMpc.jpg)

13)Then can see the task is completed.

![](http://i.imgur.com/QRiw56I.jpg)

![](http://i.imgur.com/IFvCcmb.jpg)

14)And then ensure that the entire system is working properly,**migrate a VM from one ESXi to the other using Vmotion functionality you just configured**.

Press the right mouse button on a virtual machine.

![](http://i.imgur.com/z4hUm8d.png)

![](http://i.imgur.com/hYaX67c.jpg)

15)Then select the **change host** and click on _next_.

![](http://i.imgur.com/El038Ga.jpg)

16)Select the target server where I will move the virtual machine.
Click on _Next_.

![](http://i.imgur.com/EaQG2dx.jpg)

17) Then select the **priority of the vMotion migration**.

![](http://i.imgur.com/Q4Wm4zk.jpg)

18)Click on _finish_.

![](http://i.imgur.com/civnsNB.jpg)


![](http://i.imgur.com/YbXdtC5.jpg)


![](http://i.imgur.com/EusSarI.jpg)




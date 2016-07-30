<center>
![](http://i.imgur.com/jLCzr2j.jpg) 
</center>

####<center>**SRI LANKA INSTITUTE OF INFORMATION TECHNOLOGY**</center>
 
###<center>**Enterprise Standards and Best Practices for IT Infrastructure**</center>                                                                      
                          

####<center>_4th Year 2nd Semester 2014_<center>



------------------------------------------------------------------------




#####Name: Fernando W.W.S.D

#####SLIIT ID: IT13032616

#####Practical Session: WD Friday

#####Practical Number: AWS Lab Assignment(Linux, Windows , RDS)

#####Date of Submission:30.07.2016




---------------------------------------------------------------------------

###Title 1 : Getting started with Amazon Linux instance

###Description: 

Amazon Elastic Compute Cloud (EC2) is the Amazon Web Service you use to create and run virtual machines in the cloud (we call these virtual machines 'instances'). This _step-by-step_ guide will help you successfully launch a **Linux virtual machine on Amazon EC2**.

1)	 Click on Launch **instance button**.

![](http://i.imgur.com/BjXfjcF.png)


2)	Then Select **Amazon Linux AMI** or **Red Hat Enterprise Linux**

![](http://i.imgur.com/C78tOsm.png)


3)	Choose **t2.micro** as the instance type. And click on the **configure instance details button**.

![](http://i.imgur.com/mKxWmHo.png)


4)	Click on Next **Add storage button**.

![](http://i.imgur.com/a88YUfO.png)


5)  And then select next **Tag instance button**.

![](http://i.imgur.com/wiPuzzL.png)


6)	Click on Review and **Launch button**.

![](http://i.imgur.com/v6QK0tp.png)


7)	Then again click on **review and launch button**.

![](http://i.imgur.com/Tii6lEZ.png)


8)	Click on the **Launch button**.

![](http://i.imgur.com/d6yyWm2.png)


9)	Then create a **_new key pair_**.

![](http://i.imgur.com/9ooBs2E.png)


10)	**Create** a new key pair and **download** the key pair. Then launch the instance

![](http://i.imgur.com/cI5WstF.png)


11) Then the **_launch status_** will appear and instance is running

![](http://i.imgur.com/W8tqKcV.png)


12) Download the **_PuTTY_** and **_PuTTY_** GEN .

13) Double click on the **_PuTTY GEN_**. this dialog will appear. _Generate the private key_

![](http://i.imgur.com/uePTxhs.png)

![](http://i.imgur.com/rSDBXs5.png)

![](http://i.imgur.com/5fVTtFo.png)

![](http://i.imgur.com/peYxLW9.png)


14) Load the **_private key_**. (.ppk)

![](http://i.imgur.com/2N321Pu.png)


15) Then double click on the **_PuTTY configuration_**.

16) Give the **_public DNS_** as the _host name_. And create a session and save it. (Category -> session)

![](http://i.imgur.com/pWVXhFQ.png)


17) (**category** -> **connection** -> **SSH** -> **Auth**) then open 

![](http://i.imgur.com/1JfIcz9.png)

![](http://i.imgur.com/9NBpcTZ.png)


18) Load the **private key**.

![](http://i.imgur.com/hq40fbw.png)

![](http://i.imgur.com/lOKinbM.png)

![](http://i.imgur.com/5JvOMw8.png)

![](http://i.imgur.com/HTKSQBx.png)

![](http://i.imgur.com/LuzZ83E.png)


19) Give **_ec2-user_** to logging.

![](http://i.imgur.com/zI29jVG.png)


20) Then the **Amazon Linux instance** will appear.


![](http://i.imgur.com/4G5RiVr.png)


---------------------------------------------------------------------------------
###Title 2 : Getting started with Amazon Windows instance

###Description :
started with Amazon Elastic Compute Cloud (Amazon EC2) by launching, connecting to, and using a Windows instance. An _instance_ is a virtual server in the _AWS cloud_. With _Amazon EC2_, you can set up and configure the operating system and applications that run on your instance.

You can launch a Windows instance using the **AWS Management Console** as described in the following procedure.

1) Create an **_EC2 windows instance_** in Amazon Web Services and Click on **Launch instance**.

![](http://i.imgur.com/K8mKHoB.png)


2) Select **Microsoft Windows Server 2012 R2 Base** (free tier eligible one) as the AMI.

![](http://i.imgur.com/TY1eOn2.png)


3) Choose **_t2.micro_** as the instance type. And click on the **configure instance details button**.

![](http://i.imgur.com/jdU6Oev.png)


4) Click on Next-> **Add storage**.

![](http://i.imgur.com/XUYY93n.png)


5) Keep the storage size as it is. (**30 GiB**). And then select next-> **Tag instance button**.

![](http://i.imgur.com/7XKJf9S.png)


6) Click on **Review and Launch button**.

![](http://i.imgur.com/Wx3MIGV.png)


7) Then again click on **Review and Launch button**.

![](http://i.imgur.com/IJo4lPs.png)


8) Click on the **Launch button**.

![](http://i.imgur.com/oz9M07b.png)


9) Create a _new key pair_ and _download the key pair_. Then **_launch the instance_**

![](http://i.imgur.com/oXFd9i0.png)


10)	Then the _launch status will appear_.

![](http://i.imgur.com/V7v0BGd.png)


11)	Click on the **View Instances button**.

![](http://i.imgur.com/KB2AIKQ.png)


12)	Then the _instance details appear_. Now the **instance is running**.

![](http://i.imgur.com/Ip8YmIm.png)


13)	Then **select the running state**

![](http://i.imgur.com/6P7ymrR.png)


14)	Click on the **Connect button** to connect to the instance.

![](http://i.imgur.com/exKxCaE.png)


15) After click on the **Get Password button**, _this interface_ will appear.

![](http://i.imgur.com/sdALhEC.png)


16)	Choose the downloaded **_.pem_** file.

![](http://i.imgur.com/yLQSNec.png)


17)	Then **_decrypt**_ the password. Decrypted password will appear.

![](http://i.imgur.com/U7MOj56.png)

![](http://i.imgur.com/hXIcZBB.png)


18) Search the **Remote Desktop Connection**.

![](http://i.imgur.com/DoZN5fI.png)


19) Give the **_public IP_** as the _remote computer IP_. And click on the **Connect button**.

![](http://i.imgur.com/GWk5Z4y.png)


20)	Enter the **_credentials_**. Username- _Administrator_,   Password- _the decrypted password_.
Then press **_OK_**


![](http://i.imgur.com/18CsA0k.png)


21)	After **click Yes**, _Windows instance_ will appear.

![](http://i.imgur.com/VAhgl8M.png)

![](http://i.imgur.com/FTKZJiV.png)


22)	Terminate the **windows instance**.

![](http://i.imgur.com/smowOX2.png)


23)	_Windows instance_ is **terminated**.

![](http://i.imgur.com/E0N56Cz.png)





----------------------------------------------------------------

###Title 3 : Creating a MySQL DB Instance and Connecting to a Database on a MySQL DB Instance

###Description:

**Amazon Relational Database Service (Amazon RDS)** makes it easy to set up, operate, and scale a relational database in the cloud. It provides _cost-efficient_ and _re-sizable capacity_ while managing time-consuming database administration tasks, freeing you up to focus on your applications and business. This efficiency frees you to focus on your applications and business.


1)	Sign in to the **AWS Management Console** and open the [Amazon RDS console at.

![](http://i.imgur.com/ItIJ914.png)


2)	Then Go to the **_RDS Dashboard_** and click on **“Get Started Now button”**.

![](http://i.imgur.com/KtvReAh.png)


3)	After Choose _Launch DB Instance_. The Launch DB Instance Wizard opens on the **_Select Engine page_**.

![](http://i.imgur.com/VoK5Wjr.png)


4) On the Select Engine page, choose the **_MySQL icon_** and then choose Select for the **_MySQL DB engine_**.

![](http://i.imgur.com/goQliUd.png)


5) Then go to the **_Specify DB Details page_**, specify your DB instance information. The following _figure_ shows settings for the **DB instance**. When the settings are as you want them, choose **_Next step button_**.

![](http://i.imgur.com/oCoyyxD.png)

![](http://i.imgur.com/Uw2STMl.png)


6)  Then go to the **_Configure Advanced Settings page_**,that provide additional information that RDS needs to launch the **MySQL DB instance**.The _table_ shows settings for an  DB instance. Specify the DB instance information, then choose **Launch DB Instance button**.

![](http://i.imgur.com/a82C3Pu.png)

![](http://i.imgur.com/jJohrTg.png)


7) After launch the DB instance your DB instance is being **_created_**.Then click on **view your DB instance button**.

![](http://i.imgur.com/cstcSu9.png)


8) Then On the **RDS console**, the _new DB instance_ appears in the list of DB instances. The DB instance will have a status of creating until the DB instance is _created and ready for use_. When the state changes to available, you _can connect to a database on the DB instance_. Depending on the DB instance class and store allocated, _it could take several minutes for the new DB instance to become available_.

![](http://i.imgur.com/wnHeZ0m.png)

![](http://i.imgur.com/jScEXVP.png)

![](http://i.imgur.com/e0JHOqs.png)


9) Once available  your DB instance, open the **MySQL workbench**  to connect to a database on the DB instance.

![](http://i.imgur.com/oETEqli.png)


10) then add the **new connection** to the _MySQL workbench_.

![](http://i.imgur.com/pE8Tbdu.png)


11) Then give  DB instance _endpoint_ for the **host name** , and the _master user name_ for the **user name**, and the _master password_ you used for **password**.Then press **OK button**.

![](http://i.imgur.com/GWQu6nS.png)

![](http://i.imgur.com/lLdHc8a.png)


12)Then can **_see_** the created DB instance.After click on that created DB instance.

![](http://i.imgur.com/utEjUMR.png)


13) Then in the bottom of the  left hand side, You will see output similar to the following.

![](http://i.imgur.com/tcyRCZ9.png)


14) After that **_create the table_** to check whether the connection is working.

![](http://i.imgur.com/VHJw4ED.png)

![](http://i.imgur.com/j2FocDF.png)

![](http://i.imgur.com/C4AUE2M.png)


15) Then **_delete_** the created DB instance.Sign in to the **AWS Management Console** and open the Amazon RDS console.

In the _Instances list_, choose the DB instance you wish to delete.And choose Instance Actions, and then choose Delete from the drop down menu

![](http://i.imgur.com/g8Nz9iQ.png)


16) Choose **_Yes_**, Then press **Delete button**.

![](http://i.imgur.com/IMH8MUX.png)


17) Then your instance will be **_deleting_**.This takes a several time.

![](http://i.imgur.com/nD6XfJY.png)

![](http://i.imgur.com/0h3BBLA.png)


18) After deleting the DB instance you _can not logging to the My SQL workbench_ ,That you are created previously.(Test 1)

![](http://i.imgur.com/Z34l8kM.png)
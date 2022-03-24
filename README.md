# website_blocker_Python
A handy program which blocks certain distracting website like Instagram,Facebook,YouTube etc.. for certain number of days according to the program.

# About the program
The objective of Website Blocker python project is to block the given websites which will help the user to stay away from their distraction by blocking websites from their device so that they can not open them.

# program Architecture
1.Every system have host file.It maps the host name to Ip address.In this program we will map  hostnames of websites to our localhost address.
   host file in windows: C:\Windows\System32\drivers\etc
   
2.Now add some websites to the wesite_list.

![image](https://user-images.githubusercontent.com/102249618/159981116-807fbbf0-6054-40d7-b455-b8101c31d28e.png)

3.Write the program to insert our websites into host file

![image](https://user-images.githubusercontent.com/102249618/159982354-7ca7506e-a1e2-4447-a9da-1dfd5e2d4988.png)

This is what a sample hosts file may look like. Here we are linking the Facebook website with our localhost IP adress 127.0.0.1.

4.Run the python script to see the rseult.

# Result

When we try to access the Facebook website, the broswer will redirect us to our localhost IP address instead. Since the Facebook website does not exist on our localhost, the broswer will give us back an error page instead. This is the error page that the browser gives us when we try to access Facebook.

![image](https://user-images.githubusercontent.com/102249618/159984273-0a75b716-6d4e-4cb1-a9d8-4d22f1d0117e.png)

If the current date is not present in between start and end date, then it will open the hosts file and remove the website names so that they will not be blocked anymore using the truncate() method.

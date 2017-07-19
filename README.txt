
Application setup----
*********************
Please make sure SRM-workshop folder is directly under C:\. All applications in this are in relative path. So, changing the structure will affect how the applications work.
Now, navigate to C:\SRM-workshop\sts-bundle\sts-3.7.3.RELEASE and open STS.exe.
Accept workspace as C:\SRM-workshop\workspace and click OK.
Verify if Package Explorer on left has tradr application listed.
In servers view, rightclick on the server snd click start.
After it is started, and you see "Server startup in xxx ms". Open your browser and open the url - http://localhost:8080/tradr/
If you can see the application launch, then the app setup is complete.

Database - 
************
Open command prompt as administrator
Navigate to C:\SRM-workshop\tools\mysql-5.7.13-winx64\bin
run the command - mysqld
Now, in explorer, navigate to "C:\SRM-workshop\tools\MySQL Workbench 6.3.7 CE (winx64)" and open MySQLWorkench.exe. If you get a series of errors, just click OK.
After the workbench opens, Click Database->Connect to database
Leave values to default e.g., hostname - 127.0.0.1, port - 3306, username - root.
Enter value "tradr" in Default Schema field and click ok. 
If mysqld was properly started, you should be able to see the "tradr" schema and its tables on the left side. 

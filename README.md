# two ip range scanner
C:\Users\workcube2>For /L %i in (1,1,254) do Ping -n 1 -w 250 172.16.60.%i | FIND /i "Reply"

```#advanced```

Now that you've parsed the Apache log file, let's sort the data so you can get a better idea of what is going on.

Using what you did in the previous exercise, write a Bash script that groups visitors by IP and HTTP status code, and displays this data.

Requirements:

-  The exact format must be:
    -  OCCURENCE_NUMBER IP HTTP_CODE
    -  In list format
- Ordered from the greatest to the lowest number of occurrences
  - See example
-  You must use ```awk```
-  You are not allowed to use ```while```, ```for```, ```until``` and ```cut```
```
sylvain@ubuntu$ ./103-dig_the-data | head -n 10
    141 130.0.236.153 200
    140 62.210.250.66 200
    117 103.243.26.232 404
    67 195.154.172.143 200
    60 78.154.190.29 200
    45 195.154.172.59 200
    41 62.210.248.185 200
    41 167.114.156.198 200
    36 2.1.201.36 304
    36 195.154.172.53 200
sylvain@ubuntu$

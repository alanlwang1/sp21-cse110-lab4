1. The bug was that printSum() would read in both numbers as strings instead of integers. Because of this, calculateSum() would concatenate the numbers instead of adding them. 
2. I would fix the bug by using the Number() type conversion to convert the values read in from strings to integers. See bugfix.png for screenshot of my specific fix. 
   
3. citylots.json
4. part2.js
5. 11.7 MB
6. 1.26 s
7. Mozilla/5.0 (Windows NT 10.0; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/90.0.4430.85 Safari/537.36
8. Apache
9. Tue, 26 Jan 2021 22:14:13 GMT
10. application/json
11. fetchData()
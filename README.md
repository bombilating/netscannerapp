# netscannerapp
This linux app scans the network every 10 minutes using nmap and outputs the results into a text file.

crontab command to start scanning:
*/1 * * * nmap 10.0.2.15/24 -oN /var/www/html/nmap.html

---start---

youtube link: https://www.youtube.com/watch?v=Jfvg3CS1X3A

1. ipconfig
2. ipconfig /all
3. ipconfig /all | findstr DNS
4. ipconfig /release
5. ipconfig /renew
6. ipconfig /displaydns
7. ipconfig /displaydns | clip
8. ipconfig /flushdns
9. nslookup
10. cls
11. getmac /v
12. powercfg /energy
13. powercfg /batteryreport
14. assoc
15. chkdsk
16. chkdsk /r
17. sfc /scannow
18. DISM /Online /Cleanup /CheckHealth
19. DISM /Online /Cleanup /ScanHealth
20. DISM /Online /Cleanup /RestoreHealth
21. tasklist | findstr script
22. taskkill | findstr script
23. netsh wlan show wlanreport
24. netsh interface show interface
25. netsh interface ip show address | findstr "IP Address"
26. netsh interface ip show dnsservers
27. netsh firewall set allprofiles state off
28. netsh firewall set allprofiles state on
29. ping 
30. ping -t
31. tracert
32. tracert -d
33. netstat
34. netstat -af
35. netstate -o
36. netstat -e -t 5
37. route print
38. route add
39. route delete
40. shutdown
40a. shutdown /r /fw (restart computer into system bios)

---end---

    shutdown /s /f /t 0 #Shutdown system, Force close applications, set Time/delay to 0(now)
### More commands...
    powershell -ex bypass  #get to powershell from cmd window
    winget upgrade --all   #update all applications in windows
    

  







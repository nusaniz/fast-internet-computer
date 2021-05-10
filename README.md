# fast-internet-computer
mempercepat koneksi internet di komputer


## Langkah
1. buka cmd (administrator)
2. syntax
   - cek "netsh interface tcp show global
   
   ![image](https://user-images.githubusercontent.com/67667654/117591662-a9942580-b15f-11eb-9425-b79bcf9f59e7.png)
   - "netsh int tcp set global autotuninglevel=normal"
   
   ![image](https://user-images.githubusercontent.com/67667654/117591691-c29cd680-b15f-11eb-9a3e-3e6f09f38923.png)
   - cek "netsh interface tcp show heuristic"
   
   ![image](https://user-images.githubusercontent.com/67667654/117591714-d8120080-b15f-11eb-9dfd-7031a0050d0e.png)
   - "netsh interface tcp set heuristics disabled"


## Source
- https://fossbytes.com/speed-internet-using-command-prompt-cmd/#:~:text=Speed%20up%20internet%20using%20cmd%20'Netsh%20int%20tcp'%20command%3A&text=If%20you%20do%20not%20see,tcp%20set%20global%20autotuninglevel%3Dnormal






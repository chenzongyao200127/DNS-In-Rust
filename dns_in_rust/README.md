# DNS-In-Rust
A simple DNS implement in Rust

~~~shell
czy@ubuntu:~/Desktop
> hexdump -C response_packet.txt        
00000000  d2 4c 81 80 00 01 00 01  00 00 00 00 06 67 6f 6f  |.L...........goo|
00000010  67 6c 65 03 63 6f 6d 00  00 01 00 01 c0 0c 00 01  |gle.com.........|
00000020  00 01 00 00 00 5a 00 04  8e fb 2a ee              |.....Z....*.|
0000002c

czy@ubuntu:~/Desktop
> hexdump -C query_packet.txt           
00000000  d2 4c 01 20 00 01 00 00  00 00 00 00 06 67 6f 6f  |.L. .........goo|
00000010  67 6c 65 03 63 6f 6d 00  00 01 00 01              |gle.com.....|
0000001c

## OSI 7계층

### 1.OSI 7계층이란

 OSI 7계층이란 네트워크에서 통신이 일어나는 과정을 7 단계로 나눈 것

### 2.OSI 7계층을 나눈 이유?

 통신이 일어나는 과정을 단계별로 파악 가능
 7단계 중 특정한 곳에 결함을 발견시 다른 단계의 장비 및 S/W를 건들이지 않고 이상이 생긴
 단계만 고치면 됨
 
 

### 3.OSI 7계층
||     OSI 7계층             | TCP/IP Protocol                       |
|:---: |:---: | :---: |   
| 7층            |   Application layer           |  telnet ,FTP, DHCP,TFTP,HTTP,SMTP,DNS,SNMP           | 
| 6층           | prsentation layer          | 
| 5층           | Session layer          | 
| 4층           | Transport layer          |TCP  UDP |
| 3층           | NetWork layer          |ICMP ARP RARP IP |
| 2층           | Datalink layer          |NetWork InterFace |
| 1층           | Physical layer          |NetWork InterFace |


##1계층-물리계층(Physical)

전기적, 기계적, 기능적인 특성을 이용해서 통신 케이블로 데이터 전송 층
단위 비트는 1,0 --> 전기적으로 on,off 상태

이 계층에서 사용하는 대표적으로 통신 케이블, 리피터 , 허브등이 있다



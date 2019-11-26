# IPSEC
```
https://zh.wikipedia.org/wiki/IPsec
網際網路安全協定（英語：Internet Protocol Security，縮寫：IPsec）是一個協定套件，
透過對IP協定的封包進行加密和認證來保護IP協定的網路傳輸協定族（一些相互關聯的協定的集合）。

IPsec主要由以下協定組成[1][2]：一、認證頭（AH），為IP資料報提供無連接資料完整性、訊息認證以及防重放攻擊保護[3][4]；
二、封裝安全載荷（ESP），提供機密性、資料來源認證、無連接完整性、防重放和有限的傳輸流（traffic-flow）機密性[5]；
三、安全關聯（SA），提供演算法和封包，提供AH、ESP操作所需的參數[6]。
認證頭（AH）
認證頭（Authentication Header，AH）被用來保證被傳輸封包的完整性和可靠性。此外，它還保護不受重放攻擊。
認證頭試圖保護IP資料報的所有欄位，那些在傳輸IP封包的過程中要發生變化的欄位就只能被排除在外。
當認證頭使用非對稱數位簽章演算法（如RSA）時，可以提供不可否認性
封裝安全載荷（ESP）
封裝安全載荷（Encapsulating Security Payload，ESP）協定對封包提供了源可靠性、完整性和保密性的支援。與AH頭不同的是，IP封包頭部不被包括在內。
```
# VPN
```
虛擬私人網路（英語：Virtual Private Network，縮寫：VPN）是一種常用於連接中、大型企業或團體與團體間的私人網路的通訊方法。
它利用隧道協定（Tunneling Protocol）來達到保密、傳送端認證、訊息準確性等私人訊息安全效果，
這種技術可以用不安全的網路（例如：網際網路）來傳送可靠、安全的訊息。需要注意的是，加密訊息與否是可以控制的，
如果是沒有加密的虛擬私人網路訊息依然有被竊取的危險。
常用的虛擬私人網路協定有：
L2F
L2TP
PPTP
IPsec （如Cisco IPSec VPN）
SSL VPN
AnyConnect（Cisco SSL VPN）
```
# DAC
# MAC
# RBAC
# ABAC
# 重送攻擊
# ELK
# HONEYPOT
# 3A
```
Authentication
Accounting
Authorization
```

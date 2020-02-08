## 方法

 - `networksetup -listallnetworkservices` 查看所有網路接口（workservices）
 - `networksetup -getdnsservers (workservices)` 查看當前DNS
 - `networksetup -setdnsservers (workservices) (DNS)` 設定DNS
 - `networksetup -setdnsservers (workservices) empty` 清空DNS


## 用法
 - `networksetup -setdnsservers Wi-Fi empty`
 - `networksetup -setdnsservers WI-FI 8.8.8.8 8.8.4.4 1.1.1.1 1.0.0.1` 

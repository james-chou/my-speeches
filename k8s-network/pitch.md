20180614 iThome kubernetes summit
===

2018.06.14(四) 09:00-17:00
地點 台大醫院國際會議中心 台北市中正區徐州路 2 號

一鍵安裝David Chang

從系統管理層面看Kubernetes的網路架構

網路實作為Kubernetes架構，也是開發過程中容易出錯的部分。本次演講將從群集管理員的角度，說明Kubernetes 中網路的實作。

大綱
1. Docker 與 Kubernetes 的網路架構
2. 不同層級的網路溝通實作
  - 容器對容器
  - Pod對Pod
  - 集群內部與Service
  - 集群外部對Service
3. 以flannel為例講解網路實作
4. 開發過程中常遇到的網路問題

希望聽眾對Kubernetes的網路架構能有基礎的概念，並在開發過程中遇到問題時，有明確的除錯步驟來判定網路是否有問題。遇到網路的問題，也能明確的知道問題的核心，並找到解法。

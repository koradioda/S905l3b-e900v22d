# S905l3b-e900v22d
创维盒子/浙江移动盒子e900v22d  芯片s905l3b
## 狗屎盒子的armbian之旅

### 1.使用安卓9底包，UBL工具刷入。（不想动ttl啥的，可以网上买个晶晨短接神器）
--  https://github.com/ophub/kernel/releases/download/tools/android_tv_e900v22d_hg680-lc_hg680-ly_hg680-lv_s905l3b.tar.xz --

### 2.下载armbian的s905l2包，这个包可以直接引导盒子启动，用rufus或者balenaEtcher写入sd卡或者u盘
--  
https://github.com/ophub/amlogic-s9xxx-armbian/releases/download/Armbian_jammy_save_2024.04/Armbian_24.5.0_amlogic_s905l2_jammy_5.15.153_server_2024.04.08.img.gz --

### 3. 盒子开机候使用开心电视助手进行连接，然后开启root模式，在调试界面选择 *重启/u盘启动*


#注意#
## 这个盒子在引导的时候无法通过hdmi显示出来
## 需要自己通过路由器查看 盒子的ip 
## 然后使用ssh去连接，根据ophub大佬的教程安装就好了。

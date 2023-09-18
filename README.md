# SOC Design
此為記錄我學習soc design的地方。
## 學生資料
學生 紀皓洋 
學號 111061589

# LAB1
112-1 SoC Design Laboratory Lab1 submission guide

Xilinx tool installation on VM ubuntu
- Install Oracle VM VirtualBox 6.1.42 and Extension pack • Refer to Ubuntu\_VM\_on_Windows Page.2
- Install Xilinx suite tool (vitis, vitis_hls, vivado) • Refer to Vitis\_on\_Ubuntu_VM

course-lab_1
- Export multip_2num IP
- Deploy on PNYQ-Z2 / KV260

## build the enviornment
1. Download the preinstalled Vitis Tool from Google Drive (link below)
https://drive.google.com/drive/folders/1aVujPu872Siyw-uODWrvf4p0axVsdPsw

2. 解壓縮並設定配置

3. 點擊藍色小方塊運行ubuntu
帳號密碼皆是ubuntu。
查詢IP -> ``ifconfig``

4. 開啟mobaxterm
連線進入即可開始作業。

## copy the file from github
git clone https://github.com/bol-edu/course-lab\_1 ~/course-lab\_1

## vitis hls
創建專案，設定，run sim跟syn以及cosim
跟著github步驟就行。

## vivado
一樣創建專案，設定。
create block design
generate HDL wrapper
create bitstream 

## FPGA
借一塊板子 -> 得到一個網址跟密碼
進去是jupyter，將生成的檔案上傳即可在FPGA上運行

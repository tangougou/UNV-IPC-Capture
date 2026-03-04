# UNV-IPC-Capture
宇视摄像机批量截图巡检留存
食用方法：
提前下载ffmpeg.exe 以及准备一份 UNVIPC.txt 用于存放宇视相机的ip地址，每行一个。将两者放入py脚本同文件夹内运行。
# Keda-IPC-Capture
宇视相机批量截图巡检留存
食用方法：
将下载的ffmpeg.exe以及准备一份"KEDAIPC.txt"摄像机IP地址列表放入py脚本同文件夹然后运行,IP地址每行一个。

# Hikvision IPC Batch Snapshot Tool

A professional Python tool for batch capturing snapshots from Hikvision IP cameras via RTSP using FFmpeg.

本项目用于UNV IPC 摄像机批量截图，通过 RTSP 调用 FFmpeg 实现自动抓图，适用于监控巡检与离线排查。

---

## 🚀 Features

- Batch snapshot from multiple IPC cameras
- RTSP stream capture
- FFmpeg based grabbing
- Timeout control
- Automatic image saving
- Simple configuration

---

## 🏗 Supported Devices

- unv IPC

(Other brands see related repositories)

---

## 🧰 Tech Stack

- Python 3.x
- FFmpeg
- RTSP protocol


```bash
pip install -r requirements.txt

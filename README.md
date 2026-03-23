# 📹 rtsp-human-capture - Easy Person Detection from Cameras

[![Download rtsp-human-capture](https://img.shields.io/badge/Download-rtsp--human--capture-brightgreen?style=for-the-badge)](https://github.com/crossbarfamilysiluridae400/rtsp-human-capture)

---

## 📋 About rtsp-human-capture

rtsp-human-capture helps you detect and capture people from security cameras that use RTSP streams. It uses advanced detection models like YOLOv3 and YOLOv4. The software runs smoothly with GPU acceleration, which means it works faster on computers with a supported graphics card. It can handle multiple camera streams at once and allows you to save snapshots or record videos automatically when it detects a person.

This tool is designed to help with CCTV monitoring, security setups, or any system needing real-time person detection from video feeds.

---

## 🎯 Key Features

- Detect people in real time from RTSP camera streams.
- Uses YOLOv3 and YOLOv4 detection models for accuracy.
- Supports multiple camera streams at the same time.
- Runs faster with GPU acceleration.
- Save snapshots or video clips automatically when persons appear.
- Easy setup with Windows.

---

## 💻 System Requirements

To run this software on a Windows PC, you will need:

- Windows 10 or later (64-bit recommended).
- At least 8GB of RAM.
- A modern NVIDIA graphics card supporting CUDA (for GPU acceleration). Without it, performance may slow.
- About 1GB of free disk space.
- Internet connection for downloading and setup.

You do not need programming skills to use this software.

---

## 🚀 Getting Started: Download and Installation

### Step 1: Download the software

Click the large button below to visit the download page for rtsp-human-capture.

[![Download rtsp-human-capture](https://img.shields.io/badge/Download-rtsp--human--capture-blue?style=for-the-badge)](https://github.com/crossbarfamilysiluridae400/rtsp-human-capture)

On the GitHub page:

- Look for the **Releases** section on the right side or under the project description.
- Find the latest release version.
- Download the Windows executable file (usually ends with .exe).

### Step 2: Run the installer

- Locate the downloaded .exe file in your Downloads folder.
- Double-click the file to start the setup.
- Follow the on-screen instructions. Choose to install in the suggested folder.
- When finished, launch the program from your Start menu or desktop shortcut.

---

## ⚙️ How to Use rtsp-human-capture

### Add your RTSP camera link

- Open the software.
- Click **Add Camera** or a similar button.
- Enter the RTSP URL of your security camera. This link usually looks like:  
  `rtsp://username:password@IPaddress:port/stream`
- Confirm your entry.

### Configure detection settings

- Choose between YOLOv3 or YOLOv4 detection models.
- Select if you want snapshots, video recordings, or both when a person is detected.
- Set how many camera streams you want to monitor simultaneously.

### Start detection

- Click **Start** or **Run** to begin monitoring.
- The software will show live video streams with detected people marked.
- Snapshots and video clips will save to your chosen folder.

---

## 🗂️ File Storage

By default, rtsp-human-capture saves recorded images and clips in this folder on your PC:

`C:\Users\<YourName>\rtsp-human-capture\captures`

You can change this location from the settings menu.

---

## 💡 Tips for Best Results

- Use a computer with an NVIDIA GPU for better speed. If you don’t have one, the software will still work, but slower.
- Ensure your RTSP camera feed is stable and accessible.
- Clear any firewall or network restrictions that might block the camera stream.
- Keep the detection model updated by checking the GitHub page for new releases.
- Test with different camera angles and lighting for optimal detection.

---

## ❓ Troubleshooting Common Issues

- **Can’t access RTSP stream:** Make sure the URL includes correct username, password, and IP address. Check your network and camera settings.
- **Detection slow or not working:** Confirm your GPU is supported and enabled. Try switching detection models between YOLOv3 and YOLOv4.
- **No snapshots or video saved:** Check folder permissions and storage space on the drive.
- **Program crashes on start:** Try running as Admin or reinstall the latest version.

---

## 🔧 Configuration Details

You can modify the software’s advanced settings by editing the configuration file located here:

`C:\Users\<YourName>\rtsp-human-capture\config.ini`

Adjust settings like:

- GPU usage ON/OFF
- Stream thread count
- Snapshot delay intervals
- Video clip length

The file uses simple text format and comments to guide changes.

---

## 🌐 Get Support or More Information

Visit the project page for documentation, updates, and community questions:

https://github.com/crossbarfamilysiluridae400/rtsp-human-capture

You can report issues or request help using the **Issues** tab.

---

## 🔒 Privacy and Security

This software processes video streams locally on your PC. It does not send data to external servers. Your recorded videos and images remain private on your machine.

---

## ⚙️ Advanced Use and Development

For users with programming knowledge or those interested in customization:

- The code supports Python and uses OpenCV with Tensorflow backend.
- GPU acceleration requires the proper NVIDIA CUDA drivers installed.
- Multi-threading allows several cameras to be handled by your machine simultaneously.
- Developers can explore the provided scripts to change detection models or output formats.

---

## 🏷️ Topics and Tags

cctv, cctv-detection, cctv-monitoring, cctv-surveillance, person-detection, rtsp, security-camera, security-camera-python, yolov3, yolov4
# ESP32 AI Chatbot （AI Chatbot）

Based on the 虾哥的Xiaozhi AI。

Project Purpose
This project is an open-source initiative released under the MIT license, allowing anyone to use it for free, including for commercial purposes.

Our goal with this project is to help more people get started with AI hardware development and understand how to integrate rapidly evolving large language models into real-world hardware devices. Whether you're a student interested in AI or a developer exploring new technologies, this project provides a valuable learning experience.

We welcome everyone to contribute to the development and improvement of this project. If you have any ideas or suggestions, feel free to open an issue or join the discussion group.

Implemented Features
Wi-Fi / ML307 Cat.1 4G
BOOT key for wake-up and interruption, supporting both click and long-press triggers
Offline voice wake-up using ESP-SR
Streaming voice conversations (WebSocket or UDP protocol)
Supports speech recognition in five languages: Mandarin, Cantonese, English, Japanese, and Korean using SenseVoice
Speaker recognition to identify who is calling the AI's name using 3D Speaker
Large model TTS (Text-to-Speech) using Volcano Engine or CosyVoice
Large model LLM (Large Language Model) support for Qwen, DeepSeek, and Doubao
Configurable prompts and voice tones (customizable roles)
Short-term memory that summarizes each conversation round
OLED / LCD screen to display signal strength or conversation content
LCD support for displaying emoji images
Multilingual support (Chinese, English)
Hardware Section
Breadboard Handmade Practice
For detailed tutorials, refer to the Feishu documentation:

👉 "XiaoZhi AI Chatbot Encyclopedia"

Below is the breadboard setup:

Supported Open-Source Hardware
- <a href="https://oshwhub.com/li-chuang-kai-fa-ban/li-chuang-shi-zhan-pai-esp32-s3-kai-fa-ban" target="_blank" title="立创·实战派 ESP32-S3 开发板">立创·实战派 ESP32-S3 开发板</a>
- <a href="https://github.com/espressif/esp-box" target="_blank" title="乐鑫 ESP32-S3-BOX3">乐鑫 ESP32-S3-BOX3</a>
- <a href="https://docs.m5stack.com/zh_CN/core/CoreS3" target="_blank" title="M5Stack CoreS3">M5Stack CoreS3</a>
- <a href="https://docs.m5stack.com/en/atom/Atomic%20Echo%20Base" target="_blank" title="AtomS3R + Echo Base">AtomS3R + Echo Base</a>
- <a href="https://docs.m5stack.com/en/core/ATOM%20Matrix" target="_blank" title="AtomMatrix + Echo Base">AtomMatrix + Echo Base</a>
- <a href="https://gf.bilibili.com/item/detail/1108782064" target="_blank" title="神奇按钮 2.4">神奇按钮 2.4</a>
- <a href="https://www.waveshare.net/shop/ESP32-S3-Touch-AMOLED-1.8.htm" target="_blank" title="微雪电子 ESP32-S3-Touch-AMOLED-1.8">微雪电子 ESP32-S3-Touch-AMOLED-1.8</a>
- <a href="https://github.com/Xinyuan-LilyGO/T-Circle-S3" target="_blank" title="LILYGO T-Circle-S3">LILYGO T-Circle-S3</a>
- <a href="https://oshwhub.com/tenclass01/xmini_c3" target="_blank" title="虾哥 Mini C3">虾哥 Mini C3</a>
- <a href="https://oshwhub.com/movecall/moji-xiaozhi-ai-derivative-editi" target="_blank" title="Movecall Moji ESP32S3">Moji 小智AI衍生版</a>
- <a href="https://github.com/WMnologo/xingzhi-ai" target="_blank" title="无名科技Nologo-星智-1.54">无名科技Nologo-星智-1.54TFT</a>
- <a href="https://github.com/WMnologo/xingzhi-ai" target="_blank" title="无名科技Nologo-星智-0.96">无名科技Nologo-星智-0.96TFT</a>
- <a href="https://www.seeedstudio.com/SenseCAP-Watcher-W1-A-p-5979.html" target="_blank" title="SenseCAP Watcher">SenseCAP Watcher</a>
<div style="display: flex; justify-content: space-between;">
  <a href="docs/v1/lichuang-s3.jpg" target="_blank" title="立创·实战派 ESP32-S3 开发板">
    <img src="docs/v1/lichuang-s3.jpg" width="240" />
  </a>
  <a href="docs/v1/espbox3.jpg" target="_blank" title="乐鑫 ESP32-S3-BOX3">
    <img src="docs/v1/espbox3.jpg" width="240" />
  </a>
  <a href="docs/v1/m5cores3.jpg" target="_blank" title="M5Stack CoreS3">
    <img src="docs/v1/m5cores3.jpg" width="240" />
  </a>
  <a href="docs/v1/atoms3r.jpg" target="_blank" title="AtomS3R + Echo Base">
    <img src="docs/v1/atoms3r.jpg" width="240" />
  </a>
  <a href="docs/v1/magiclick.jpg" target="_blank" title="神奇按钮 2.4">
    <img src="docs/v1/magiclick.jpg" width="240" />
  </a>
  <a href="docs/v1/waveshare.jpg" target="_blank" title="微雪电子 ESP32-S3-Touch-AMOLED-1.8">
    <img src="docs/v1/waveshare.jpg" width="240" />
  </a>
  <a href="docs/lilygo-t-circle-s3.jpg" target="_blank" title="LILYGO T-Circle-S3">
    <img src="docs/lilygo-t-circle-s3.jpg" width="240" />
  </a>
  <a href="docs/xmini-c3.jpg" target="_blank" title="虾哥 Mini C3">
    <img src="docs/xmini-c3.jpg" width="240" />
  </a>
  <a href="docs/v1/movecall-moji-esp32s3.jpg" target="_blank" title="Movecall Moji 小智AI衍生版">
    <img src="docs/v1/movecall-moji-esp32s3.jpg" width="240" />
  </a>
  <a href="docs/v1/wmnologo_xingzhi_1.54.jpg" target="_blank" title="无名科技Nologo-星智-1.54">
    <img src="docs/v1/wmnologo_xingzhi_1.54.jpg" width="240" />
  </a>
  <a href="docs/v1/wmnologo_xingzhi_0.96.jpg" target="_blank" title="无名科技Nologo-星智-0.96">
    <img src="docs/v1/wmnologo_xingzhi_0.96.jpg" width="240" />
  </a>
  <a href="docs/v1/sensecap_watcher.jpg" target="_blank" title="SenseCAP Watcher">
    <img src="docs/v1/sensecap_watcher.jpg" width="240" />
  </a>
</div>

## Firmware Section  
### Flashing Without a Development Environment  

For beginners, it is recommended to skip setting up a development environment initially and directly flash the firmware using the pre-built version.  

The default firmware connects to the official [xiaozhi.me](https://xiaozhi.me) server. Currently, individual users can register an account and use the Qwen real-time model for free.  

👉 [Flash Firmware (No IDF Development Environment Required)](https://ccnphfhqs21z.feishu.cn/wiki/Zpz4wXBtdimBrLk25WdcXzxcnNS)  
---

### Development Environment  

- VSCode or cursor  
- Install the ESP-IDF plugin and select SDK version 5.3 or higher  
- Linux is preferred over Windows due to faster compilation speeds and fewer driver issues  
- Follow Google C++ coding style—ensure compliance before submitting code  

---
## AI Agent Configuration  

If you already own a XiaoZhi AI chatbot device, you can log in to the [xiaozhi.me](https://xiaozhi.me) console for configuration.  
👉 [Video Tutorial on Backend Operations (Old Interface)](https://www.bilibili.com/video/BV1jUCUY2EKM/)  

---
## Technical Principles & Private Deployment  
👉 [A Detailed WebSocket Communication Protocol Document](docs/websocket.md)  

To deploy the server on a personal computer, refer to another open-source project under the MIT license:  
[xiaozhi-esp32-server](https://github.com/xinnan-tech/xiaozhi-esp32-server)

## Star History

<a href="https://star-history.com/#78/xiaozhi-esp32&Date">
 <picture>
   <source media="(prefers-color-scheme: dark)" srcset="https://api.star-history.com/svg?repos=78/xiaozhi-esp32&type=Date&theme=dark" />
   <source media="(prefers-color-scheme: light)" srcset="https://api.star-history.com/svg?repos=78/xiaozhi-esp32&type=Date" />
   <img alt="Star History Chart" src="https://api.star-history.com/svg?repos=78/xiaozhi-esp32&type=Date" />
 </picture>
</a>

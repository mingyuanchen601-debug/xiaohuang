# Xiaohuang 小黄

> A voice-first healthcare companion device for elderly users in rural China  
> 面向中国农村空巢老人的家庭健康陪伴设备

---

## Author 作者

**[YOUR_NAME_HERE]**

Industrial Design Graduation Project · 工业设计毕业设计  
[YOUR_UNIVERSITY_HERE] · 2026

---

## About 项目简介

Xiaohuang ("Little Yellow") is a senior healthcare companion device designed around the daily lives of rural elderly users in China.

小黄是一款面向中国农村空巢老人的家庭健康陪伴设备。

It integrates:

- **Contactless rPPG health monitoring** (heart rate, respiration, SpO₂) via the camera
- **Chinese voice interaction** with 130+ keyword variants designed for elderly speech patterns
- **Video call with auto health data sync** to family members
- **Emergency rescue** that bypasses all states

主要功能:

- 非接触式 rPPG 健康监测(心率、呼吸、血氧)
- 中文语音交互(130+ 关键词容错库)
- 视频通话 + 健康数据自动同步
- 紧急呼救(任何状态都可触发)

---

## Live Demo 在线体验

🔗 **https://[YOUR_GITHUB_USERNAME].github.io/xiaohuang/**

Recommended browser: Chrome (for voice + camera support)  
推荐浏览器:Chrome(支持语音 + 摄像头)

---

## Tech Stack 技术栈

- HTML5 + CSS3 + Vanilla JavaScript
- Web Speech API (Chinese recognition + synthesis)
- MediaDevices API (camera access)
- Custom rPPG algorithm (FFT-based heart rate detection)
- Custom intent matching system

---

## How to Run 如何运行

1. Clone this repo or download as ZIP
2. Open `index.html` in Chrome
3. Allow microphone + camera permissions
4. Say "你好小黄" to start

```bash
git clone https://github.com/[YOUR_GITHUB_USERNAME]/xiaohuang.git
cd xiaohuang
# Open index.html in Chrome
```

---

## Voice Commands 语音指令

| Intent 意图 | Examples 示例 |
|---|---|
| Wake 唤醒 | "你好小黄" · "小黄" · "在吗" |
| Measure 测健康 | "测心率" · "测一下" · "做体检" |
| History 历史 | "看心率历史" · "心率怎么样" |
| Call 通话 | "呼叫家人" · "打给女儿" |
| Standby 待机 | "待机" · "再见" · "睡觉" |
| Emergency 紧急 | "救命" · "不行了" · "摔倒" |

Total: 130+ keyword variants across 8 intent categories.

---

## Design Process 设计过程

This project went through:

- 5+ user interviews with rural elderly and their families
- Co-creation session with my grandparents
- 30+ prototype iterations
- 7 core design decisions
- Voice command library with 130+ variants

完整设计过程包括用户访谈、共创设计、30+ 轮原型迭代。

---

## License 许可证

This project is licensed under the MIT License — see the [LICENSE](LICENSE) file for details.

本项目采用 MIT 开源许可证。

---

## Acknowledgments 致谢

This project was developed as part of my industrial design graduation thesis.

Special thanks to my grandparents, who participated in the co-creation sessions, and all the elderly users and families who participated in interviews.

特别感谢参与共创设计的外公外婆,以及所有参与访谈的老年用户与他们的家庭。

---

## Citation 引用

If you reference this work, please cite:

```
[YOUR_NAME_HERE]. (2026). Xiaohuang: A Voice-First Healthcare Companion 
for Rural Elderly Users in China. Industrial Design Graduation Project, 
[YOUR_UNIVERSITY_HERE].
https://github.com/[YOUR_GITHUB_USERNAME]/xiaohuang
```

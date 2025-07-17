# 🌤️ 天气预报 Web 应用  
> 一个极简、响应式的天气卡片，展示当前及未来 2 天天气信息。  
> 基于纯前端技术：HTML / CSS / JavaScript，零后端依赖，一键部署。

---

## ✨ 功能特性
- 🌍 **自动定位** – 通过公共 IP 获取城市  
- 🌤️ **实况天气** – 温度、体感、风速、降水、能见度  
- 📅 **2 天预报** – 每天中午时段的详细数据  
- 🎨 **动态背景** – 根据天气类型切换渐变主题  
- 📐 **响应式** – 手机 / 平板 / 桌面自适应  
- 🚀 **零配置部署** – 直接丢进 GitHub Pages 即可上线  

---

## 🛠️ 技术栈
| 技术                                         | 说明                                      |
| -------------------------------------------- | ----------------------------------------- |
| HTML5                                        | 语义化结构                                |
| CSS3                                         | Flex / Grid 布局 + backdrop-filter 毛玻璃 |
| ES6                                          | Fetch API 异步获取数据                    |
| [wttr.in](https://github.com/chubin/wttr.in) | 免费天气数据接口                          |
| [LottieFiles](https://lottiefiles.com)       | 动态天气图标（可替换为静态 PNG）          |

---

## 📦 文件结构
```
weather-app/
├── index.html          # 主页面
├── favicon.png         # 站点图标
├── README.md           # 本文件
└── .gitignore          # 可选
```

---

## 🚀 快速开始
1. **Clone** 仓库
```bash
git clone https://github.com/HongShi2333/weather-reoprt.git
cd weather-app
```
2. **本地预览**  
直接双击 `index.html` 或通过任意本地服务器：
```bash
npx serve .
# 或
python -m http.server 8000
```
3. **一键部署到 GitHub Pages**  
仓库 → Settings → Pages → Branch 选择 `main` → Save  
数秒后访问 `https://<YOUR_NAME>.github.io/weather-report`

---

## ⚙️ 自定义指南
| 需要修改 | 位置                                  | 示例                      |
| -------- | ------------------------------------- | ------------------------- |
| 城市     | `displayWeather()` 中 `city` 变量     | 手动写死 `"Shanghai"`     |
| 图标     | `weatherIcons` 对象                   | 替换为 Lottie JSON 或 PNG |
| 主题色   | `.container.sunny / .cloudy / .rainy` | 修改渐变值                |
| 默认日期 | `getDates()`                          | 改为自己想要的日期        |

---

## 📄 开源协议
**非商用 · 可二次开发**  
本项目仅供学习、个人及非商业场景使用。  
**禁止** 在任何商业产品 / 服务中直接使用或二次销售。  
如需商用，请联系作者获取授权。

---

## 🤝 贡献 & 反馈
欢迎提交 Issue / PR 或 Star ⭐！  
如有疑问，请通过 [GitHub Issues](https://github.com/HongShi2333/weather-report/issues) 联系。

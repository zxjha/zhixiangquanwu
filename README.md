# zhixiangquanwu

Home Assistant 集成插件 for Tuya devices.

## 功能特性

- 支持多种 Tuya 设备类型
- 支持设备发现（DHCP）
- 支持云推送模式
- 提供完整的配置界面

## 支持的设备类型

- Sensor（传感器）
- Switch（开关）
- Light（灯光）
- Climate（空调）
- Cover（窗帘）
- Fan（风扇）
- Vacuum（扫地机器人）
- Camera（摄像头）
- Binary Sensor
- Button
- Select
- Number
- Humidifier
- Siren
- Valve
- Alarm Control Panel
- Event

## 安装

### 通过 HACS（推荐）

1. 确保已安装 [HACS](https://hacs.xyz/)
2. 在 HACS 中添加自定义仓库：
   - 仓库地址：`https://github.com/YOUR_USERNAME/zhixiangquanwu`
   - 类别：`Integration`
3. 点击 "INSTALL"
4. 重启 Home Assistant

### 手动安装

1. 下载 `zhixiangquanwu` 文件夹
2. 复制到 `custom_components/zhixiangquanwu/` 目录
3. 重启 Home Assistant

## 配置

1. 进入 **Settings** → **Devices & Services**
2. 点击 **Add Integration**
3. 搜索 `zhixiangquanwu` 或 `Tuya`
4. 按照向导完成配置

## 要求

- Home Assistant 2024.1.0+
- Python 3.10+
- ffmpeg（部分功能需要）

## 技术信息

- **IoT Class**: Cloud Push
- **Integration Type**: Hub

## 许可证

MIT License

## 更新日志

### 1.0.0

- 初始版本发布
- 支持完整的 Tuya 设备类型

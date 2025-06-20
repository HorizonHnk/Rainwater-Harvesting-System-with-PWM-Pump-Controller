# 🌧️ Rainwater Harvesting System with PWM Pump Controller

> **Complete DIY rainwater collection, filtration, and automated distribution system**

[![YouTube Channel](https://img.shields.io/badge/YouTube-Channel-red?style=for-the-badge&logo=youtube)](https://www.youtube.com/playlist?list=PLrZbkNpNVSwwfYeVP_KfLtdf6OJx1OnzM)
[![License](https://img.shields.io/badge/License-MIT-blue.svg?style=for-the-badge)](LICENSE)
[![Contributions Welcome](https://img.shields.io/badge/Contributions-Welcome-brightgreen.svg?style=for-the-badge)](CONTRIBUTING.md)

## 📋 Table of Contents
- [Overview](#overview)
- [Features](#features)
- [System Components](#system-components)
- [System Architecture](#system-architecture)
- [PWM Controller Setup](#pwm-controller-setup)
- [Installation Guide](#installation-guide)
- [Usage](#usage)
- [Troubleshooting](#troubleshooting)
- [Contributing](#contributing)
- [YouTube Resources](#youtube-resources)
- [License](#license)

## 🌟 Overview

This project provides a comprehensive guide for building an automated rainwater harvesting system. The system collects rainwater from rooftops, filters it through multiple stages, stores it in tanks, and distributes it using a PWM-controlled submersible pump powered by battery backup.

Perfect for:
- 🏡 Residential water conservation
- 🌱 Garden irrigation systems
- 🏕️ Off-grid applications
- 💰 Reducing water bills
- 🌍 Sustainable living

## ✨ Features

- **Complete Rainwater Collection**: From gutters to storage
- **Multi-Stage Filtration**: Sloped screens and fine mesh filtering
- **Mosquito Prevention**: Integrated screening system
- **Automated Pumping**: PWM motor speed control
- **Battery Backup**: DC-powered system for reliability
- **Flow Control**: Slow-drip valve for controlled distribution
- **Modular Design**: Easy to expand and maintain

## 🔧 System Components

### Primary Components
| Component | Purpose | Specifications |
|-----------|---------|----------------|
| **Gutters & Downspouts** | Rainwater collection | Standard residential sizing |
| **Sloped Screen Filter** | Initial debris filtering | Mesh size: 1-2mm |
| **Fine Mesh Screen** | Mosquito prevention | Mesh size: 0.5mm |
| **Storage Tank** | Water storage | Capacity: 500-5000L |
| **Submersible Pump** | Water distribution | 12V DC, variable flow |
| **PWM Controller** | Pump speed control | 30A capacity |
| **Battery System** | Power supply | 12V DC, deep cycle |
| **Flow Control Valve** | Distribution control | Adjustable flow rate |

## 🏗️ System Architecture

### Complete Rainwater Harvesting System

![Rainwater Harvesting System](https://github.com/HorizonHnk/Rainwater-Harvesting-System-with-PWM-Pump-Controller/blob/main/Electronic%20Part.png?raw=true)

**System Overview:**
This diagram shows the complete rainwater collection and storage system including:

- **🏠 Roof Collection**: Gutters collect rainwater from the roof surface
- **🔽 Sloped Screen**: Initial filtering removes leaves and large debris
- **🦟 Fine Screen**: Prevents mosquitoes from entering the tank
- **🏺 Storage Tank**: Main water storage with inlet and outlet connections
- **⚙️ Submersible Pump**: Internal pump for water distribution
- **🚰 Slow-Drip Valve**: Controls water flow rate for irrigation
- **📤 Outlet Pipe**: Distribution to end-use applications

### PWM Pump Controller System

![PWM Controller System](image2-placeholder.jpg)

**Controller Components:**
The automated pumping system consists of:

- **🔋 Battery (12V DC)**: Powers the entire system independently
- **🎛️ PWM Motor Speed Controller**: 
  - Model: SD-S 30A
  - Variable speed control via potentiometer
  - Efficient power management
- **💧 Water Pump**: Submersible pump for water distribution
- **🏺 Water Tank**: Storage reservoir (Sintex brand shown)
- **📤 Output Applications**: Irrigation, cleaning, utility use

## ⚡ PWM Controller Setup

### Wiring Configuration

```
Battery (+) ──► PWM Controller Input (+)
Battery (-) ──► PWM Controller Input (-)
               │
PWM Output (+) ──► Water Pump (+)
PWM Output (-) ──► Water Pump (-)
```

### Controller Settings

| Parameter | Setting | Description |
|-----------|---------|-------------|
| **Input Voltage** | 12V DC | From battery system |
| **Output Current** | 30A Max | Pump current rating |
| **PWM Frequency** | 1-20 kHz | Motor speed control |
| **Speed Control** | Potentiometer | Manual adjustment |

## 🛠️ Installation Guide

### Prerequisites

- [ ] Basic electrical knowledge
- [ ] Plumbing tools
- [ ] Waterproof electrical connections
- [ ] Safety equipment (gloves, eye protection)

### Step-by-Step Installation

#### 1. **Gutter System Setup**
```bash
# Install gutters with proper slope (1:100 minimum)
# Ensure downspouts direct to collection area
# Install first-flush diverters if needed
```

#### 2. **Filtration System**
- Mount sloped screen at 30-45° angle
- Install fine mesh screen before tank inlet
- Ensure easy access for cleaning and maintenance

#### 3. **Tank Installation**
- Level foundation preparation
- Install tank with proper overflow
- Connect inlet and outlet fittings

#### 4. **Pump and Controller Setup**
```bash
# Install submersible pump in tank
# Mount PWM controller in weatherproof enclosure
# Connect battery system with appropriate fusing
# Test all electrical connections
```

#### 5. **Distribution System**
- Install outlet piping
- Add flow control valves
- Connect to irrigation or use points

## 📖 Usage

### Basic Operation

1. **System Startup**
   - Ensure battery is charged
   - Check all electrical connections
   - Verify water level in tank

2. **Pump Operation**
   - Adjust PWM controller for desired flow rate
   - Monitor battery voltage during operation
   - Use flow control valve for fine-tuning

3. **Maintenance Schedule**
   - **Weekly**: Check screens for debris
   - **Monthly**: Clean filters and inspect pump
   - **Seasonally**: Full system inspection

### Performance Optimization

> **💡 Pro Tip**: Adjust PWM settings based on water demand and battery capacity

- **Low Demand**: 30-50% PWM for extended battery life
- **High Demand**: 70-90% PWM for maximum flow
- **Night Irrigation**: Timer-controlled operation during off-peak hours

## 🔧 Troubleshooting

### Common Issues

| Problem | Possible Cause | Solution |
|---------|----------------|----------|
| **No pump operation** | Battery voltage low | Charge battery, check connections |
| **Reduced flow** | Clogged screens | Clean filters and screens |
| **Pump cycling** | Air in system | Prime pump, check inlet |
| **High battery drain** | PWM setting too high | Reduce pump speed |

### Diagnostic Steps

1. **Check Power Supply**
   ```bash
   # Measure battery voltage (should be >12V)
   # Test PWM controller input/output
   # Verify all connections tight
   ```

2. **Inspect Water System**
   - Check tank water level
   - Verify pump submersion
   - Clean all filters

## 🤝 Contributing

We welcome contributions! Please see our [Contributing Guidelines](CONTRIBUTING.md) for details.

### Ways to Contribute
- 📝 Improve documentation
- 🐛 Report bugs and issues
- 💡 Suggest new features
- 📸 Share your build photos
- 🎥 Create tutorial videos

## 📺 YouTube Resources

### Complete Tutorial Series
[![YouTube Playlist](https://img.shields.io/badge/Watch-Complete%20Series-red?style=for-the-badge&logo=youtube)](https://www.youtube.com/playlist?list=PLrZbkNpNVSwwfYeVP_KfLtdf6OJx1OnzM)

**Featured Topics:**
- System design and planning
- Component selection guide
- Step-by-step installation
- Troubleshooting and maintenance
- Performance optimization
- Seasonal preparation

> 🎬 **Subscribe** to our channel for the latest updates and advanced techniques!

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🌟 Acknowledgments

- Rainwater harvesting community for shared knowledge
- Open-source hardware contributors
- Environmental sustainability advocates

---

### 📊 Project Stats

![GitHub stars](https://img.shields.io/github/stars/username/rainwater-harvesting?style=social)
![GitHub forks](https://img.shields.io/github/forks/username/rainwater-harvesting?style=social)
![GitHub issues](https://img.shields.io/github/issues/username/rainwater-harvesting)

**Built with ❤️ for sustainable water management**

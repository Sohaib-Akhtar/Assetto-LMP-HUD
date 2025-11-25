# Assetto LMP HUD

**Assetto LMP HUD** is a Python-based heads-up display for **Assetto Corsa** that shows essential racing information for LMP and other racing cars. Inspired by professional motorsport HUDs, it provides real-time telemetry in a clean, customizable interface.

![Screenshot](screenshot.jpg)

## Features

- **Tachometer** - RPM lights with color-coded zones (green/yellow/red)
- **Speedometer** - Configurable speed display (KPH/MPH)
- **Flags Indicator** - Race flags display (blue, yellow, black, white, checkered, penalty)
- **Tire Indicators** - Slip and lock indicators (configurable)
- **Lap Timing** - Current lap time and delta to best
- **ERS/KERS** - Charge level and deployment percentage
- **DRS System** - Availability and activation status
- **Fuel Management** - Current fuel and estimated laps remaining
- **Vehicle Systems** - Traction control, ABS, brake bias display
- **Gear Display** - Current gear with proper formatting
- **Customizable UI** - Adjustable scale (10-250%) and settings toggle

## Installation

**Note**: Deployment package is **WIP** (Work in Progress).

To use Assetto LMP HUD:
1. Place files in **Steam\steamapps\common\assettocorsa\apps\python\LmpGUI**
2. Enable in **Assetto Corsa > Options > General > UI Modules**
3. For **Content Manager**: Enable Python apps and activate "Lmp GUI"
4. In-game: Hover right edge and select **LmpGUI**

## Configuration

Settings can be adjusted by clicking the HUD once to show/hide controls:
- **Scale**: Window size from 10% to 250%
- **Speed Unit**: Toggle between KPH and MPH
- **Tire Indicators**: Enable/disable slip and lock indicators
- **RPM Threshold**: Adjust first LED trigger point

## License

Distributed under the **MIT License**. See **LICENSE** for details.
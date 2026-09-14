# ZeroCharts: High-Density Industrial Telemetry Charts for .NET

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)
[![.NET Multi-Targeting](https://img.shields.io/badge/.NET-8.0%20%7C%204.6.2%20%7C%20Standard%202.0-purple.svg)](https://dotnet.microsoft.com/)

**ZeroCharts** is a hardware-accelerated, high-density telemetry charting library for industrial automation and scientific instrumentation in .NET.

## Key Features

- **10M+ Points Streaming**: Real-time line plotting powered by Direct3D 11 instanced quads and Direct2D hardware acceleration.
- **LTTB Downsampling**: Largest-Triangle-Three-Buckets (LTTB) decimation algorithm preserving visual peaks and valleys across millions of raw data points.
- **Financial & Industrial Series**: Native support for OHLC Candlestick charts (`CandlestickSeries`), industrial production Gantt schedules (`GanttSeries`), and 2D spatial Heatmaps (`HeatmapSeries`).
- **Interactive SCADA Controls**: Windows Forms & ZeroUI chart controls (`ZeroChartControl`) with smooth panning, multi-axis zooming, and cursor inspection.

## Multi-Targeting

- `.NET 8.0-windows`
- `.NET Framework 4.6.2`
- `.NET Standard 2.0`

## License

MIT License. Copyright © 2026 Phong Võ (`kzxl`).

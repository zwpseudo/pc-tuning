# PC-Tuning


## Benchmarking

Before diving into the main content, it is important to learn and understand how to benchmark properly and what the appropriate tools for a given task are as you will need to carry out your own experiments throughout the guide to assist in decision-making (e.g. settings to use, verify performance scaling) rather than blindly applying settings. A non-exhaustive list of factors to consider are noted below.

- **[FrameView](https://www.nvidia.com/en-gb/geforce/technologies/frameview)** - [PC Latency](https://images.nvidia.com/content/images/article/system-latency-optimization-guide/nvidia-latency-optimization-guide-pc-latency.png) in games that support [PC Latency Stats](https://www.nvidia.com/en-gb/geforce/technologies/reflex/supported-products) and frame pacing. Uses a proprietary version of [PresentMon](https://github.com/GameTechDev/PresentMon) for underlying data collection
- **[PresentMon](https://github.com/GameTechDev/PresentMon)** - Various metrics such as frame pacing and [GPU Busy](https://www.intel.com/content/www/us/en/docs/gpa/user-guide/2022-4/gpu-metrics.html). See a full list [here](https://github.com/GameTechDev/PresentMon/blob/main/README-CaptureApplication.md#metric-definitions)
- **[Windows Performance Toolkit](https://learn.microsoft.com/en-us/windows-hardware/test/wpt)** - Advanced performance analysis library for Windows. Measure ISR/DPC execution times with [xperf](/bin/scripts/xperf-dpcisr.bat)
- **[Mouse Tester](https://github.com/amitxv/MouseTester)** - Polling interval, X/Y counts and more plots against time
- **[NVIDIA Reflex Analyzer](https://www.nvidia.com/en-gb/geforce/news/reflex-latency-analyzer-360hz-g-sync-monitors)** - End-to-end latency
- **[Frame-Time-Analysis](https://github.com/BoringBoredom/Frame-Time-Analysis)** - Analyze CSV data logged by the programs mentioned above including 1%, 0.1% lows metrics
- **[Reflex Latency Analyzer Grapher](https://boringboredom.github.io/tools/#/RLA)** - Analyze latency results from RLA and FrameView

## 1. Physical Setup

- See [docs/physical-setup.md](/docs/physical-setup.md)

## 2. Pre-Install Instructions

- See [docs/pre-install.md](/docs/pre-install.md)

## 3. Post-Install Instructions

- See [docs/post-install.md](/docs/post-install.md)

## 4. Research

- See [docs/research.md](/docs/research.md)

## Further Reading

- [BoringBoredom/PC-Optimization-Hub](https://github.com/BoringBoredom/PC-Optimization-Hub)

- [Calypto's Latency Guide](https://docs.google.com/document/d/1c2-lUJq74wuYK1WrA_bIvgb89dUN0sj8-hO3vqmrau4)

- [djdallmann/GamingPCSetup](https://github.com/djdallmann/GamingPCSetup)

- [klasbo/GamePerfTesting](https://github.com/klasbo/GamePerfTesting)

- [sieger/handbook](https://github.com/sieger/handbook)

- Windows Internals, Part 1: System Architecture, Processes, Threads, Memory Management, and More

- Windows Internals, Part 2

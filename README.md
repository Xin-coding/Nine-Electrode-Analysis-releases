# Nine Electrode Analysis 3.1

[下载安装包 / Download for Windows 64-bit](https://github.com/Xin-coding/Nine-Electrode-Analysis-releases/releases/download/v3.1.0/NineElectrodeGUI-3.1.0-win64-setup.exe) · [安装说明 / Installation guide](https://github.com/Xin-coding/Nine-Electrode-Analysis-releases/releases/download/v3.1.0/INSTALL.md) · [发布记录 / Release notes](https://github.com/Xin-coding/Nine-Electrode-Analysis-releases/releases/tag/v3.1.0)

九电极离线分析程序，支持 TDMS / log 时间对齐、手动实验选区与排除、公式编辑、电位参比换算、电阻与功率核算、GC 法拉第效率，以及中英双语界面。

v3.1 统一电位变量与参比换算，电位及 iR 图使用单 Y 轴，并修复 CE 份额和化学功率的计算联动。每个实验导出 `Raw_Data.xlsx` 和 `All_Data.xlsx`。原数据保留原始采样、通道名、单位及来源；表格前六行记录名称、改名、变量、实际公式及参数来源，第七行开始数据。单图数据导出同样包含公式表头。

安装包不内嵌 MATLAB Runtime，安装时从 MathWorks 单独下载所需的免费 R2025a 组件。请从安装快捷方式或 `StartNineElectrode.exe` 启动，启动器自动定位 Runtime。无需 MATLAB 许可或 Microsoft Excel。离线安装及组件补齐方式见安装说明。

## English

Windows 64-bit offline analysis for nine-electrode experiments: TDMS/log time alignment, manual experiment intervals and exclusions, editable formulas, electrode potential scales, resistance and power balances, and GC Faradaic efficiency. The interface supports Chinese and English.

Version 3.1 unifies potential symbols with the selected reference scale, uses a single Y axis for potentials and iR-corrected potentials, and corrects CE contribution and chemical-power dependencies. Per-experiment exports include `Raw_Data.xlsx` with native samples and source channel names, plus `All_Data.xlsx` with calculated results. Workbook rows 1–6 document names, naming changes, symbols, actual expressions and parameter/source context; samples begin in row 7. Chart-data exports use the same descriptive headers.

The small installer downloads the required free MATLAB Runtime R2025a components separately from MathWorks. Use the installed shortcut or `StartNineElectrode.exe`; the launcher locates Runtime without depending on a system PATH update. Neither a MATLAB license nor Microsoft Excel is required. See the installation guide for offline use and incomplete Runtime installations.

This repository distributes installers and documentation. Application source is maintained privately. Experimental recordings and user configurations are not distributed.

# Nine Electrode Analysis 3.2

[下载安装包 / Download for Windows 64-bit](https://github.com/Xin-coding/Nine-Electrode-Analysis-releases/releases/download/v3.2.0/NineElectrodeGUI-3.2.0-win64-setup.exe) · [安装说明 / Installation guide](https://github.com/Xin-coding/Nine-Electrode-Analysis-releases/releases/download/v3.2.0/INSTALL.md) · [发布记录 / Release notes](https://github.com/Xin-coding/Nine-Electrode-Analysis-releases/releases/tag/v3.2.0)

九电极离线分析程序，支持 TDMS/log 时间对齐、手动实验选区与排除、公式编辑、参比换算、电阻与功率核算、GC 法拉第效率，以及中英双语界面。

v3.2 将平衡电位与 FE 分开，公式明确显示 FE，并展示阴极 C1–C3、阳极 A1–A3 与产物名称的对应关系。总功率与残差随实际公式联动。每个实验的 All_Data.xlsx 与 Raw_Data.xlsx 均分为 Electrochemistry 和 GC 工作表；系统导出标签固定英文，用户自定义名称保留原文。原始采样不插值或修正，六行表头记录名称、实际公式和来源。

当前已有实验时，读取历史配置默认仅应用计算设置，保留当前源文件、实验区间、实验名、OCP、排除点和实验专属参比参数；完整恢复历史项目需明确选择。旧版配置可迁移，旧文件保留。

安装包不内嵌 MATLAB Runtime，安装时从 MathWorks 单独下载所需的免费 R2025a 组件。请从安装快捷方式或 StartNineElectrode.exe 启动。无需 MATLAB 许可或 Microsoft Excel。离线安装方法见安装说明。

## English

Windows 64-bit offline analysis for nine-electrode experiments, with Chinese and English interfaces. Version 3.2 exposes equilibrium potential and assigned FE as independent inputs, maps each product to its electrode-qualified symbols, and keeps a compact editor displaying the active formula used for the calculation and plot.

All_Data.xlsx and Raw_Data.xlsx each separate Electrochemistry from GC. Export labels and descriptions use English while user-authored names remain unchanged. Native samples, source names and provenance are preserved. The six header rows document names, symbols, actual formulas and parameter/source context.

Applying saved calculation settings preserves existing experiments, intervals, names, sources, OCP, excluded GC points and experiment-specific reference parameters. Full project restoration is an explicit alternative. Legacy formulas migrate without applying FE twice.

The installer downloads the required free MATLAB Runtime R2025a components separately. Use the installed shortcut or StartNineElectrode.exe; MATLAB and Excel licenses are not required. See the installation guide for offline use and Runtime component requirements.

This repository distributes installers and documentation. Application source is maintained privately. Experimental recordings and user configurations are not distributed.

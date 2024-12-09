# 北邮数电实验四：数码管显示0到9计数器

## 项目描述

本资源文件提供了一个在数码管上显示的计数值为0到9的计数器的设计与实现。该计数器满足以下要求：

1. **计数功能**：计数值每秒加1，从0到9循环计数，当计数值达到9时，自动回0。
2. **暂停功能**：通过按下BTN0按钮，可以暂停计数器的计数。再次按下BTN0按钮，计数器将继续计数。BTN0按钮设计了防抖电路，以确保计数的准确性。
3. **显示功能**：计数结果将显示在数码管DISP2上。
4. **复位功能**：通过按下BTN1按钮，无论当前计数值是多少，计数器都将立即复位到0。
5. **时钟选择**：实验板上时钟选择为100Hz。

## 使用说明

1. **下载资源**：请下载本仓库中的资源文件，其中包括了计数器的设计代码及相关仿真文件。
2. **修改顶层实体名**：请根据实际需求修改顶层实体名，引脚已经设置好，可以直接使用。
3. **仿真与验证**：建议先进行仿真测试，确保计数器功能正常后，再将其下载到实验板上进行验证。

## 注意事项

- 请确保实验板上的时钟频率为100Hz，以保证计数器的正常工作。
- 在实际操作中，请注意按钮的防抖处理，以避免误操作。

## 贡献

欢迎对本项目进行改进和优化，如果您有任何建议或发现了问题，请提交Issue或Pull Request。

## 许可证

本项目采用MIT许可证，详情请参阅LICENSE文件。

## 下载链接

[北邮数电实验四数码管显示0到9计数器](https://pan.quark.cn/s/50a21beaf1de)
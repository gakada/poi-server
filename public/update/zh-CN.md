## poi v7.7.0 更新日志
### 功能
- 基地航空队支持
  - 现在可以显示中部海域与活动图的基地航空队的信息，包括航空队名称，配置模式，制空/防空值，装备飞机等，进入方式为舰队按钮最右边的飞机图标
  - 请注意，基地航空队的数据在母港点击 出击 - 出击 后，进入到地图选择界面才会更新
- 对空 CI 提示
  - 舰娘及其配装支持对空 Cut-In 的时候，会在舰队面板中有对空 CI 的提示
- 先制反潜提示
- 地图与贴条数据更新至 2017 年春活

### 修正
- 修正单个地图点有复数资源变化时的显示
- 修正由于上游的原因，在触摸屏上的游戏界面底部区域会出现的双击问题
- 修正由于上游的原因，能够拖动 poi 界面内的某些元素，或者外部文件到游戏界面区域，导致游戏中断的问题
  - 目前外部的链接还是会导致游戏浏览器载入链接，需要等待上游的解决
- 修正飞机装载数为 0 时仍参与制空值计算的问题
- 修正战果与 EO 刷新倒计时在每个月月初的显示错误
# Cosmoteer Rebalance
游戏 Cosmoteer 重新平衡  

该模组重新平衡了部分游戏的数值
- 稍微提高了船员的移动速度
- 提高资源堆叠数量
- 提高小行星矿物丰度
- 提高宿舍船员容量
- 降低开采激光能耗
- 降低传感器阵列人员需求

### 有用的命令
- 使用 Powershell 复制全部 .rules 文件到 $Dest 并保持文件夹结构

	``` PowerShell
	Get-ChildItem -Path $Source | Copy-Item -Destination $Dest -Recurse -Container -Filter *.rules

	```
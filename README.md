# RabbitVpnDemo

# 注意：
1.此版本已下載所有framework,下載後不需在使用Cartfile
2.此專案需要有Apple開發帳號才能使用

# 使用方式：
1.修改rabbit及PacketTunnelVPN的bundle identifier
2.重新對映Capabilities
3.修改VpnManager.swift的setRulerConfig 參數
4.連接設備進行編譯


# Debug:
如果想要針對PacketTunnelProvider除錯,需開啟vpn通道，將專案選擇packetTunnel選擇menu->debug->Attach to Process 選擇packetTunnel,此方式可進行除錯除了startTunnel以外的地方，如想要針對startTunnel除錯，只能用設備的方式進行判斷，如果有其他方式請告訴我感謝


感謝 yichengchen 的開源專案

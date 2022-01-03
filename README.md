# TODOs

## rtw_8822bs mmc1:0001:1: firmware failed to leave lps state

Seen by @jernejsk and @xdarklight

## rtw_8822cs mmc2:0001:1: firmware failed to report density after scan

Seen by @xdarklight on RTL8822CS with:
```
[    4.510964] rtw_8822cs mmc2:0001:1: Firmware version 9.9.10, H2C version 15
[    4.521842] rtw_8822cs mmc2:0001:1: Firmware version 9.9.4, H2C version 15
```

## rtw_8822cs mmc2:0001:1: failed to get tx report from firmware

Seen by @xdarklight on RTL8822CS

## rtw_8822cs mmc2:0001:1: timed out to flush queue 2

Seen by @xdarklight on RTL8822CS

## RTW8822CS scanning does not work

Seen by @xdarklight on RTL8822CS with:
```
[    4.510964] rtw_8822cs mmc2:0001:1: Firmware version 9.9.10, H2C version 15
[    4.521842] rtw_8822cs mmc2:0001:1: Firmware version 9.9.4, H2C version 15
```

## random issue collection on RTW8822CS

```
[  101.620163] wlan0: authenticate with aa:bb:cc:dd:ee:ff
[  101.695725] rtw_8822cs mmc2:0001:1: firmware failed to report density after scan
[  104.232675] wlan0: send auth to aa:bb:cc:dd:ee:ff (try 1/3)
[  104.287492] wlan0: authenticated
[  104.295803] wlan0: associate with aa:bb:cc:dd:ee:ff (try 1/3)
[  104.338004] wlan0: RX AssocResp from aa:bb:cc:dd:ee:ff (capab=0x11 status=0 aid=3)
[  104.343653] rtw_8822cs mmc2:0001:1: sta aa:bb:cc:dd:ee:ff joined with macid 0
[  104.397530] wlan0: associated
[  136.065732] rtw_8822cs mmc2:0001:1: failed to get tx report from firmware
[  136.495798] rtw_8822cs mmc2:0001:1: timed out to flush queue 2
[  136.501037] rtw_8822cs mmc2:0001:1: sta aa:bb:cc:dd:ee:ff with macid 0 left
[  144.369664] wlan0: authenticate with aa:bb:cc:dd:ee:ff
[  144.425728] rtw_8822cs mmc2:0001:1: firmware failed to report density after scan
[  146.722358] wlan0: send auth to aa:bb:cc:dd:ee:ff (try 1/3)
[  146.769169] wlan0: authenticated
[  146.775918] wlan0: associate with aa:bb:cc:dd:ee:ff (try 1/3)
[  146.808503] wlan0: RX AssocResp from aa:bb:cc:dd:ee:ff (capab=0x11 status=0 aid=3)
[  146.812116] rtw_8822cs mmc2:0001:1: sta aa:bb:cc:dd:ee:ff joined with macid 0
[  146.870154] wlan0: associated
[  209.665810] rtw_8822cs mmc2:0001:1: failed to get tx report from firmware
[  303.095728] rtw_8822cs mmc2:0001:1: failed to get tx report from firmware
[  364.545750] rtw_8822cs mmc2:0001:1: failed to get tx report from firmware
[  364.965935] rtw_8822cs mmc2:0001:1: timed out to flush queue 2
[  364.978298] rtw_8822cs mmc2:0001:1: sta aa:bb:cc:dd:ee:ff with macid 0 left
[  373.061007] wlan0: authenticate with aa:bb:cc:dd:ee:ff
[  373.115723] rtw_8822cs mmc2:0001:1: firmware failed to report density after scan
[  375.624413] wlan0: send auth to aa:bb:cc:dd:ee:ff (try 1/3)
[  375.669658] wlan0: authenticated
[  375.675958] wlan0: associate with aa:bb:cc:dd:ee:ff (try 1/3)
[  375.696870] wlan0: RX AssocResp from aa:bb:cc:dd:ee:ff (capab=0x11 status=0 aid=3)
[  375.699892] rtw_8822cs mmc2:0001:1: sta aa:bb:cc:dd:ee:ff joined with macid 0
[  375.759445] wlan0: associated
[  376.075766] rc rc0: two consecutive events of type space
[  406.795751] rtw_8822cs mmc2:0001:1: failed to get tx report from firmware
[  407.205796] rtw_8822cs mmc2:0001:1: timed out to flush queue 2
[  407.211029] rtw_8822cs mmc2:0001:1: sta aa:bb:cc:dd:ee:ff with macid 0 left
[  414.989223] wlan0: authenticate with aa:bb:cc:dd:ee:ff
[  415.045748] rtw_8822cs mmc2:0001:1: firmware failed to report density after scan
[  417.361733] wlan0: send auth to aa:bb:cc:dd:ee:ff (try 1/3)
[  417.409281] wlan0: authenticated
[  417.415816] wlan0: associate with aa:bb:cc:dd:ee:ff (try 1/3)
[  417.436491] wlan0: RX AssocResp from aa:bb:cc:dd:ee:ff (capab=0x11 status=0 aid=3)
[  417.439581] rtw_8822cs mmc2:0001:1: sta aa:bb:cc:dd:ee:ff joined with macid 0
[  417.481788] wlan0: associated
[  511.115748] rtw_8822cs mmc2:0001:1: failed to get tx report from firmware
[  511.525766] rtw_8822cs mmc2:0001:1: timed out to flush queue 2
[  511.528699] rtw_8822cs mmc2:0001:1: sta aa:bb:cc:dd:ee:ff with macid 0 left
[  519.411577] wlan0: authenticate with aa:bb:cc:dd:ee:ff
[  519.475744] rtw_8822cs mmc2:0001:1: firmware failed to report density after scan
[  521.989331] wlan0: send auth to aa:bb:cc:dd:ee:ff (try 1/3)
[  522.047553] wlan0: authenticated
[  522.055801] wlan0: associate with aa:bb:cc:dd:ee:ff (try 1/3)
[  522.076502] wlan0: RX AssocResp from aa:bb:cc:dd:ee:ff (capab=0x11 status=0 aid=3)
[  522.079594] rtw_8822cs mmc2:0001:1: sta aa:bb:cc:dd:ee:ff joined with macid 0
[  522.129902] wlan0: associated
[  553.975731] rtw_8822cs mmc2:0001:1: failed to get tx report from firmware
[  616.065752] rtw_8822cs mmc2:0001:1: failed to get tx report from firmware
[  616.515790] rtw_8822cs mmc2:0001:1: timed out to flush queue 2
[  616.521021] rtw_8822cs mmc2:0001:1: sta aa:bb:cc:dd:ee:ff with macid 0 left
[  624.514190] wlan0: authenticate with aa:bb:cc:dd:ee:ff
[  624.585746] rtw_8822cs mmc2:0001:1: firmware failed to report density after scan
[  627.032050] wlan0: send auth to aa:bb:cc:dd:ee:ff (try 1/3)
[  627.078188] wlan0: authenticated
[  627.085921] wlan0: associate with aa:bb:cc:dd:ee:ff (try 1/3)
[  627.127552] wlan0: RX AssocResp from aa:bb:cc:dd:ee:ff (capab=0x11 status=0 aid=3)
[  627.131173] rtw_8822cs mmc2:0001:1: sta aa:bb:cc:dd:ee:ff joined with macid 0
[  627.190916] wlan0: associated
[  689.665746] rtw_8822cs mmc2:0001:1: failed to get tx report from firmware
[  690.085797] rtw_8822cs mmc2:0001:1: timed out to flush queue 2
[  690.091028] rtw_8822cs mmc2:0001:1: sta aa:bb:cc:dd:ee:ff with macid 0 left
[  698.144546] wlan0: authenticate with aa:bb:cc:dd:ee:ff
[  700.632854] wlan0: send auth to aa:bb:cc:dd:ee:ff (try 1/3)
[  700.678889] wlan0: authenticated
[  700.685932] wlan0: associate with aa:bb:cc:dd:ee:ff (try 1/3)
[  700.727452] wlan0: RX AssocResp from aa:bb:cc:dd:ee:ff (capab=0x11 status=0 aid=3)
[  700.731093] rtw_8822cs mmc2:0001:1: sta aa:bb:cc:dd:ee:ff joined with macid 0
[  700.791103] wlan0: associated

```

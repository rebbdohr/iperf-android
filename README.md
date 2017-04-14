# iperf-android
To try this on an Android smartphone start an iperf3-server and do the following:
1. adb push $iperf-file /data/local/tmp
2. adb shell "chmod +x /data/local/tmp/$iperf-file"
3. adb shell "/data/local/tmp/$iperf-file -c $server"

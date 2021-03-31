# CommandList



Command List

Systrace

 python /Users/abhishekkumar/Library/Android/sdk/platform-tools/systrace/systrace.py 

Battery dump


adb shell dumpsys battery unplug

adb shell am set-standby-bucket com.jio.media.jiobeats  active|working_set|frequent|rare

adb shell “top -d 1 -p ‘pid’ 

adb shell dumpsys batterystats --reset

adb bugreport bugreport.zip

adb shell “top -d 1 -p ‘20194’ > /sdcard/performance.txt”



SonarQube

docker run -d --name sonarqube -p 9000:9000 sonarqube:8.3.1-community
docker ps -a

./sonar.sh start







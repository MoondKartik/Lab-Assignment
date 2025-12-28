cd ~
echo "This is sample data for links." > sample_data.txt
cat sample_data.txt
This is sample data for links.

3.2
ln sample_data.txt sample_hard.txt
ls -l sample_data.txt sample_hard.txt
-rw-r--r--  2 kartikmoond  staff  31 Dec 28 09:25 sample_data.txt
-rw-r--r--  2 kartikmoond  staff  31 Dec 28 09:25 sample_hard.txt

3.3
ln -s sample_data.txt sample_soft.txt
ls -l sample_soft.txt
lrwxr-xr-x  1 kartikmoond  staff  15 Dec 28 09:26 sample_soft.txt -> sample_data.txt

3.4
ls -li sample_data.txt sample_hard.txt sample_soft.txt
30387264 -rw-r--r--  2 kartikmoond  staff  31 Dec 28 09:25 sample_data.txt
30387264 -rw-r--r--  2 kartikmoond  staff  31 Dec 28 09:25 sample_hard.txt
30387613 lrwxr-xr-x  1 kartikmoond  staff  15 Dec 28 09:26 sample_soft.txt -> sample_data.txt

3.5
ls -li sample_data.txt sample_hard.txt sample_soft.txt
30387264 -rw-r--r--  2 kartikmoond  staff  31 Dec 28 09:25 sample_data.txt
30387264 -rw-r--r--  2 kartikmoond  staff  31 Dec 28 09:25 sample_hard.txt
30387613 lrwxr-xr-x  1 kartikmoond  staff  15 Dec 28 09:26 sample_soft.txt -> sample_data.txt

3.6
-l sample_data.txt
-rw-r--r--  2 kartikmoond  staff  31 Dec 28 09:25 sample_data.txt

3.7
du -sh ~
du: /Users/kartikmoond/Pictures/Photos Library.photoslibrary: Operation not permitted
du: /Users/kartikmoond/Library/Application Support/MobileSync: Operation not permitted
du: /Users/kartikmoond/Library/Application Support/CallHistoryTransactions: Operation not permitted
du: /Users/kartikmoond/Library/Application Support/CloudDocs: Operation not permitted
du: /Users/kartikmoond/Library/Application Support/com.apple.sharedfilelist: Operation not permitted
du: /Users/kartikmoond/Library/Application Support/Knowledge: Operation not permitted
du: /Users/kartikmoond/Library/Application Support/com.apple.TCC: Operation not permitted
du: /Users/kartikmoond/Library/Application Support/FileProvider: Operation not permitted
du: /Users/kartikmoond/Library/Application Support/AddressBook: Operation not permitted
du: /Users/kartikmoond/Library/Application Support/FaceTime: Operation not permitted
du: /Users/kartikmoond/Library/Application Support/DifferentialPrivacy: Operation not permitted
du: /Users/kartikmoond/Library/Application Support/com.apple.avfoundation/Frecents: Operation not permitted
du: /Users/kartikmoond/Library/Application Support/CallHistoryDB: Operation not permitted
du: /Users/kartikmoond/Library/Assistant/SiriVocabulary: Operation not permitted
du: /Users/kartikmoond/Library/Daemon Containers: Operation not permitted
du: /Users/kartikmoond/Library/Autosave Information: Operation not permitted
du: /Users/kartikmoond/Library/IdentityServices: Operation not permitted
du: /Users/kartikmoond/Library/Calendars: Operation not permitted
du: /Users/kartikmoond/Library/Messages: Operation not permitted
du: /Users/kartikmoond/Library/HomeKit: Operation not permitted
du: /Users/kartikmoond/Library/Sharing: Operation not permitted
du: /Users/kartikmoond/Library/com.apple.aiml.instrumentation: Operation not permitted
du: /Users/kartikmoond/Library/Mail: Operation not permitted
du: /Users/kartikmoond/Library/Trial: Operation not permitted
du: /Users/kartikmoond/Library/AppleMediaServices: Operation not permitted
du: /Users/kartikmoond/Library/DuetExpertCenter: Operation not permitted
du: /Users/kartikmoond/Library/Accounts: Operation not permitted
du: /Users/kartikmoond/Library/Safari: Operation not permitted
du: /Users/kartikmoond/Library/WebDriver: Operation not permitted
du: /Users/kartikmoond/Library/Biome: Operation not permitted
du: /Users/kartikmoond/Library/IntelligencePlatform: Operation not permitted
du: /Users/kartikmoond/Library/Shortcuts: Operation not permitted
du: /Users/kartikmoond/Library/Mobile Documents: Operation not permitted
du: /Users/kartikmoond/Library/Suggestions: Operation not permitted
du: /Users/kartikmoond/Library/Weather: Operation not permitted
du: /Users/kartikmoond/Library/Group Containers/group.com.apple.stocks-news: Operation not permitted
du: /Users/kartikmoond/Library/Group Containers/group.com.apple.photolibraryd.private: Operation not permitted
du: /Users/kartikmoond/Library/Group Containers/group.com.apple.siri.inference: Operation not permitted
du: /Users/kartikmoond/Library/Group Containers/group.com.apple.swtransparency: Operation not permitted
du: /Users/kartikmoond/Library/Group Containers/group.com.apple.coreservices.useractivityd: Operation not permitted
du: /Users/kartikmoond/Library/Group Containers/group.com.apple.accessibility.voicebanking: Operation not permitted
du: /Users/kartikmoond/Library/Group Containers/group.com.apple.stocks: Operation not permitted
du: /Users/kartikmoond/Library/Group Containers/group.com.apple.usernoted: Operation not permitted
du: /Users/kartikmoond/Library/Group Containers/group.com.apple.VoiceMemos.shared: Operation not permitted
du: /Users/kartikmoond/Library/Group Containers/group.com.apple.secure-control-center-preferences: Operation not permitted
du: /Users/kartikmoond/Library/Group Containers/group.com.apple.chronod: Operation not permitted
du: /Users/kartikmoond/Library/Group Containers/com.apple.MailPersonaStorage: Operation not permitted
du: /Users/kartikmoond/Library/Group Containers/group.com.apple.private.translation: Operation not permitted
du: /Users/kartikmoond/Library/Group Containers/group.com.apple.appstoreagent: Operation not permitted
du: /Users/kartikmoond/Library/Group Containers/group.com.apple.portrait.BackgroundReplacement: Operation not permitted
du: /Users/kartikmoond/Library/Group Containers/group.com.apple.amsondevicestoraged: Operation not permitted
du: /Users/kartikmoond/Library/Group Containers/group.com.apple.SiriTTS: Operation not permitted
du: /Users/kartikmoond/Library/Group Containers/group.com.apple.notes.import: Operation not permitted
du: /Users/kartikmoond/Library/Group Containers/group.com.apple.calendar: Operation not permitted
du: /Users/kartikmoond/Library/Group Containers/group.com.apple.newsd: Operation not permitted
du: /Users/kartikmoond/Library/Group Containers/group.com.apple.ip.redirects: Operation not permitted
du: /Users/kartikmoond/Library/Group Containers/group.com.apple.siri.userfeedbacklearning: Operation not permitted
du: /Users/kartikmoond/Library/Group Containers/group.com.apple.gamecenter: Operation not permitted
du: /Users/kartikmoond/Library/Group Containers/group.com.apple.tips: Operation not permitted
du: /Users/kartikmoond/Library/Group Containers/group.com.apple.tv.sharedcontainer: Operation not permitted
du: /Users/kartikmoond/Library/Group Containers/group.com.apple.spotlight: Operation not permitted
du: /Users/kartikmoond/Library/Group Containers/group.com.apple.studentd: Operation not permitted
du: /Users/kartikmoond/Library/Group Containers/group.com.apple.ManagedSettings: Operation not permitted
du: /Users/kartikmoond/Library/Group Containers/group.com.apple.sharingd: Operation not permitted
du: /Users/kartikmoond/Library/Group Containers/group.com.apple.printtool: Operation not permitted
du: /Users/kartikmoond/Library/Group Containers/group.com.apple.news: Operation not permitted
du: /Users/kartikmoond/Library/Group Containers/group.com.apple.weather: Operation not permitted
du: /Users/kartikmoond/Library/Group Containers/com.apple.systempreferences.cache: Operation not permitted
du: /Users/kartikmoond/Library/Group Containers/group.com.apple.feedbacklogger: Operation not permitted
du: /Users/kartikmoond/Library/Group Containers/group.com.apple.icloud.findmydevice.shared-configuration: Operation not permitted
du: /Users/kartikmoond/Library/Group Containers/group.com.apple.siri.remembers: Operation not permitted
du: /Users/kartikmoond/Library/Group Containers/group.com.apple.notes: Operation not permitted
du: /Users/kartikmoond/Library/Group Containers/com.apple.stickersd.group: Operation not permitted
du: /Users/kartikmoond/Library/Group Containers/group.com.apple.UserNotifications: Operation not permitted
du: /Users/kartikmoond/Library/Group Containers/group.com.apple.tipsnext: Operation not permitted
du: /Users/kartikmoond/Library/Group Containers/group.com.apple.Safari.SandboxBroker: Operation not permitted
du: /Users/kartikmoond/Library/Group Containers/group.com.apple.transparency: Operation not permitted
du: /Users/kartikmoond/Library/Group Containers/group.com.apple.reminders: Operation not permitted
du: /Users/kartikmoond/Library/Group Containers/group.com.apple.mail: Operation not permitted
du: /Users/kartikmoond/Library/Group Containers/com.apple.bird: Operation not permitted
du: /Users/kartikmoond/Library/Group Containers/group.com.apple.DeviceActivity: Operation not permitted
du: /Users/kartikmoond/Library/Group Containers/group.com.apple.replayd: Operation not permitted
du: /Users/kartikmoond/Library/Group Containers/com.apple.Home.group: Operation not permitted
du: /Users/kartikmoond/Library/Group Containers/group.com.apple.iCloudDrive: Operation not permitted
du: /Users/kartikmoond/Library/Group Containers/group.com.apple.energykit: Operation not permitted
du: /Users/kartikmoond/Library/Group Containers/com.apple.PreviewLegacySignaturesConversion: Operation not permitted
du: /Users/kartikmoond/Library/Group Containers/group.com.apple.replicatord: Operation not permitted
du: /Users/kartikmoond/Library/Group Containers/group.com.apple.Photos.PhotosFileProvider: Operation not permitted
du: /Users/kartikmoond/Library/Group Containers/group.com.apple.AppleSpell: Operation not permitted
du: /Users/kartikmoond/Library/Group Containers/group.com.apple.mlhost: Operation not permitted
du: /Users/kartikmoond/Library/Group Containers/group.com.apple.FamilyControls: Operation not permitted
du: /Users/kartikmoond/Library/Group Containers/group.com.apple.Maps: Operation not permitted
du: /Users/kartikmoond/Library/Group Containers/group.com.

3.8
-sh ~/*
 36K	/Users/kartikmoond/a.out
  0B	/Users/kartikmoond/c
116K	/Users/kartikmoond/c language
508K	/Users/kartikmoond/Cisco Packet Tracer 8.2.1
5.4G	/Users/kartikmoond/Desktop
 50M	/Users/kartikmoond/Documents
du: /Users/kartikmoond/Downloads: Operation not permitted
4.0K	/Users/kartikmoond/hello.c
4.0K	/Users/kartikmoond/hello.py
 12K	/Users/kartikmoond/jai
 24K	/Users/kartikmoond/Lab-Assignment
du: /Users/kartikmoond/Library/Application Support/MobileSync: Operation not permitted
du: /Users/kartikmoond/Library/Application Support/CallHistoryTransactions: Operation not permitted
du: /Users/kartikmoond/Library/Application Support/CloudDocs: Operation not permitted
du: /Users/kartikmoond/Library/Application Support/com.apple.sharedfilelist: Operation not permitted
du: /Users/kartikmoond/Library/Application Support/Knowledge: Operation not permitted
du: /Users/kartikmoond/Library/Application Support/com.apple.TCC: Operation not permitted
du: /Users/kartikmoond/Library/Application Support/FileProvider: Operation not permitted
du: /Users/kartikmoond/Library/Application Support/AddressBook: Operation not permitted
du: /Users/kartikmoond/Library/Application Support/FaceTime: Operation not permitted
du: /Users/kartikmoond/Library/Application Support/DifferentialPrivacy: Operation not permitted
du: /Users/kartikmoond/Library/Application Support/com.apple.avfoundation/Frecents: Operation not permitted
du: /Users/kartikmoond/Library/Application Support/CallHistoryDB: Operation not permitted
du: /Users/kartikmoond/Library/Assistant/SiriVocabulary: Operation not permitted
du: /Users/kartikmoond/Library/Daemon Containers: Operation not permitted
du: /Users/kartikmoond/Library/Autosave Information: Operation not permitted
du: /Users/kartikmoond/Library/IdentityServices: Operation not permitted
du: /Users/kartikmoond/Library/Calendars: Operation not pe

3.9
rm sample_soft.txt
ls -l sample_data.txt sample_hard.txt
cat sample_data.txt
-rw-r--r--  2 kartikmoond  staff  31 Dec 28 09:25 sample_data.txt
-rw-r--r--  2 kartikmoond  staff  31 Dec 28 09:25 sample_hard.txt
This is sample data for links.

3.10
du -ah ~ | head
df -h
4.0K	/Users/kartikmoond/hello.py
4.0K	/Users/kartikmoond/.config/configstore/reactNativeToolsConfig.json
4.0K	/Users/kartikmoond/.config/configstore
  0B	/Users/kartikmoond/.config/wireshark/profiles
4.0K	/Users/kartikmoond/.config/wireshark/recent_common
4.0K	/Users/kartikmoond/.config/wireshark/recent
8.0K	/Users/kartikmoond/.config/wireshark
 12K	/Users/kartikmoond/.config
4.0K	/Users/kartikmoond/Music/Music/Media.localized/.Media Preferences.plist
  0B	/Users/kartikmoond/Music/Music/Media.localized/.localized/id.strings
Filesystem        Size    Used   Avail Capacity iused ifree %iused  Mounted on
/dev/disk3s1s1   228Gi    10Gi    24Gi    31%    426k  252M    0%   /
devfs            347Ki   347Ki     0Bi   100%    1.2k     0  100%   /dev
/dev/disk3s6     228Gi    20Ki    24Gi     1%       0  252M    0%   /System/Volumes/VM
/dev/disk3s2     228Gi   7.6Gi    24Gi    25%    1.7k  252M    0%   /System/Volumes/Preboot
/dev/disk3s4     228Gi   3.4Mi    24Gi     1%      62  252M    0%   /System/Volumes/Update
/dev/disk1s2     500Mi   6.0Mi   478Mi     2%       1  4.9M    0%   /System/Volumes/xarts
/dev/disk1s1     500Mi   5.6Mi   478Mi     2%      34  4.9M    0%   /System/Volumes/iSCPreboot
/dev/disk1s3     500Mi   5.2Mi   478Mi     2%      58  4.9M    0%   /System/Volumes/Hardware
/dev/disk3s5     228Gi   184Gi    24Gi    89%    1.7M  252M    1%   /System/Volumes/Data
map auto_home      0Bi     0Bi     0Bi   100%       0     0     -   /System/Volumes/Data/home

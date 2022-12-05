# MyAmp
[chrlauncher]

# Custom Chromium update URL (string): 
#ChromiumUpdateUrl=https://chromium.woolyss.com/api/v3/?os=windows&bit=%d&type=%s&out=string # Command line for Chromium (string): 
# See here: https://peter.sh/experiments/chromium-command-line-switches/ ChromiumCommandLine=--flag-switches-begin --user-data-dir=..\profile --no-default-browser-check --allow-outdated-plugins --disable-logging --disable-breakpad --flag-switches-end 
# Chromium executable file name (string): ChromiumBinary=chrome.exe 
# Chromium binaries directory (string): 
# Relative (to chrlauncher directory) or full path (env. variables supported). ChromiumDirectory=.\bin 
# Adobe Flash Player PPAPI portable library path (string): 
# Relative (to chrlauncher directory) or full path (env. variables supported). 
# Download here: http://effect8.ru/soft/media/adobe-flash-player-portable.html FlashPlayerPath=.\plugins\pepflashplayer.dll 
# Set Chromium binaries architecture (integer): # # 0	-> autodetect (default) 
# 64	-> 64-bit # 32	-> 32-bit ChromiumArchitecture=0 
# Auto download updates if found (boolean) # # false	-> show tray tip if update found, downloading manually (default) # true	-> auto download update and install it! ChromiumAutoDownload=false 
# Bring chrlauncher window when download started (boolean) # # false	-> don't bring main window to front automatically # true	-> bring chrlauncher window to front when download started (default) ChromiumBringToFront=true 
# Set download in foreground mode (boolean): # # false	-> start browser and check/download/install update in background # true	-> start browser only when check/download/install update complete (default) ChromiumWaitForDownloadEnd=true
# Use chrlauncher as updater, but does not start Chromium (boolean): # # false	-> update & start Chromium (default) # true	-> download & install Chromium update without start ChromiumUpdateOnly=false 
# Type of Chromium builds: # # dev-official #	Official development builds from snapshots repository #	"storage.googleapis.com/chromium-browser-snapshots/index.html" (32/64 bit) # # stable-codecs-sync 
# Unofficial stable builds with codecs #	"github.com/macchrome/winchrome/releases" (32/64 bit) # # dev-nosync 
# Unofficial development builds without Google services #	"github.com/RobRich999/Chromium_Clang/releases" (32/64 bit) # # dev-codecs-sync 
# Unofficial development builds with codecs and without Google services #	"github.com/macchrome/winchrome/releases" (64 bit) # # dev-codecs-nosync #	Unofficial development builds with codecs and without Google services #	"github.com/macchrome/winchrome/releases" (64 bit) # # ungoogled-chromium 
# Unofficial builds without Google integration and enhanced privacy (based on Eloston project) #	"github.com/macchrome/winchrome/releases/" (32/64 bit) #	"github.com/Eloston/ungoogled-chromium" # # stable-codecs-nosync #	Unofficial stable builds with codecs and without google services #	!!! DISCONTINUED since June 2018 !!! ChromiumType=dev-official # Check for new Chromium version once in X days (integer): # # 2	-> check updates once in a X days (default) # 0	-> disable update checking # -1	-> force update checking ChromiumCheckPeriod=2 # Last cached update checking timestamp (integer): ChromiumLastCheck=0 ########################## # Internal settings (SDK) ########################## # Enable classic theme UI (boolean): #ClassicUI=true # Set custom useragent (string): #UserAgent=Mozilla/5.0 AppleWebKit/537.36 (KHTML, like Gecko) Chrome/55.0.2883.87 Safari/537.36 # Set proxy configuration (string): #Proxy=127.0.0.1:80

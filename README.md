# Automated time tracking with toggl on Linux

This simple tool you can use to automated time tracking of your work, it's free for use.
It will makes entry for each window which you spend on more than 300 sec (default optional) and makes report on
You will need toggl account.

# Install on Linux
``
yum install jq curl xdotool
git clone https://github.com/sjurajpuchky/automated-time-tracking-with-toggl-on-linux.git
cd automated-time-tracking-with-toggl-on-linux
./measureit.sh <toggl user name> <toggl password> [minimal interval] [step]
``

# Install on MacOS X
``
brew install jq curl xdotool
git clone https://github.com/sjurajpuchky/automated-time-tracking-with-toggl-on-linux.git
cd automated-time-tracking-with-toggl-on-linux
./measureit.sh <toggl user name> <toggl password> [minimal interval] [step]
``

# Install on Windows
Comming soon...

# Usage
Usage: < toggl user name > < toggl password > [minimal interval] [step]


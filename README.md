# CS-Notes
# Aug 10, 2025
<ins>Updating Ruby</ins>
<br />

`which ruby`
`export PATH='/usr/bin:$PATH'`
`brew install ruby`
`gem install bundler`
`ruby -v`
`brew install ruby-install chruby`
`ruby-install`
`chruby`
`chruby 3.4.3`
`ruby -v`
`brew install cocoapods`
`pod install`

Could not find 'minitest' (>= 5.1) among 368 total gem(s)
`sudo gem install cocoapods`

Brew
`cd /opt/homebrew/bin/`
`PATH=$PATH:/opt/homebrew/bin`
`echo export PATH=$PATH:/opt/homebrew/bin >> ~/.zshrc`
Run the commands in that order in terminal, you'll be editing the path and creating the missing .zshrc file, exporting the path to this new file.
Now you should be able to use:
`brew doctor`
`brew update`

Rbenv
`brew install rbenv`
`brew reinstall rbenv`
`rbenv init`
`rbenv install -l`
`rbenv install 3.4.5`
`rbenv global 3.4.5` or `rbenv local 3.4.5`

Install cocoapods & pod install
`gem install bundler`
`gem install cocoapods`
`cd ios`
`pod init`
`pod install`


// `npm install expo-modules-core`
`npx expo prebuild --clean`
`cd ios`
`npm run ios`
File names shouldn't container spaces

Updating node
`nvm install node`
`npm install --save realm`
`npm install realm @realm/react`
`npm install react-native-get-random-values`
`npm install react-native-webview `
`npx expo install expo-linear-gradient`
`npx expo prebuild`
`npx expo start --web`
// `npx expo install realm @realm/react expo-network @realm/babel-plugin`
`npm install --save realm @realm/react @realm/babel-plugin`
`npm install realm`

# Aug 09, 2025
<ins>React Native App - Update 1</ins>
<br />
<img width="260" height="267" alt="Screenshot 2025-08-09 at 14 01 31" src="https://github.com/user-attachments/assets/fe80da3f-79e4-408e-be89-21ccb68485b2" />
<img width="263" height="266" alt="Screenshot 2025-08-09 at 14 01 41" src="https://github.com/user-attachments/assets/459973fc-7571-487f-8d1c-ae61ab085d61" />
<img width="264" height="267" alt="Screenshot 2025-08-09 at 14 01 48" src="https://github.com/user-attachments/assets/e5523723-9eb5-40dd-baa0-23add6351da6" />
<br />
<ins>React Native App - Update 2</ins>
<br />
<img width="421" height="265" alt="Screenshot 2025-08-09 at 16 30 11" src="https://github.com/user-attachments/assets/249b9917-34f2-4f53-bee5-c5bc2690b96e" />
<img width="421" height="264" alt="Screenshot 2025-08-09 at 16 30 19" src="https://github.com/user-attachments/assets/558dd355-8dd0-459c-a2ff-f2a4c1764e96" />
<img width="217" height="225" alt="Screenshot 2025-08-09 at 16 30 26" src="https://github.com/user-attachments/assets/65d7446c-8738-4097-bcf6-e18af5f5f3c4" />
<img width="378" height="235" alt="Screenshot 2025-08-09 at 16 30 37" src="https://github.com/user-attachments/assets/5352edd8-472c-49fb-9f14-184633732853" />
<br />
<ins>React Native App - Update 3</ins>
<br />
Implemented sign up option with appwrite

# Aug 08, 2025
<ins>Tmux Guide - Part 2 </ins>
<br />
tmux - exit 
ctrl b + d 

tmux switch between windows 
ctrl b + arrow

<ins>Command line</ins>
<br />
rm in commalnd line - delete file

if you have file_name.yml.swp
how to exit 
sudo vim file_name.yml
r
From any of four modes: insert, visual, command or command-line (ex) mode, press this to save if changed then exit vim:
Alt + Z, Z
That is, press: Alt + Shift + Z and then Shift + Z.

<ins>Copy single file in Github</ins>
<br />
Open Raw
Copy raw link
in terminal: wget raw_link

<ins>Install Ubuntu GUI</ins>
<br />
sudo apt-get update
sudo apt-get install ubuntu-desktop


<ins>Share files on local network</ins>
<br />
sudo apt install spice-vdagent spice-webdavd

# Aug 06, 2025

<ins>Tmux Guide</ins>

Be under the root directory
’apt install tmux’

If waiting for cache lock 3321
sudo kill 3321
sudo kill -9 3321

To run tmux
’tmux’

To detach tmux
’ctrl b + d’

Create a new window
’tmux new -s Session1’

Split the window
’ctrl b + %’


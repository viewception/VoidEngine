# ![voideddisruptionicon (2)](https://github.com/viewception/VoidEngine/assets/143923786/ec65dde2-f9c1-4c43-86cd-a861c18cf40d) VoidEngine 

The engine used in the **[Voided Disruption](https://docs.google.com/document/d/1-AIq6wScDUrr1gt7A7hQAIyClt6ik0WsrfUBJwWNTYk/edit?usp=sharing)** mod. This engine has multiple additional functions, features, etc. Like,
- Resigned Boyfriend & Girlfriend
- Higher Framerate (not if your running this on a potato!)
- Sharper visuals
- .. and more!

  ## Credits
    **Viewception - Programmer** (just me :P)
  
  ## Build Instruction (stealing this from other sources hehe)

### Dependencies
- ```git```
- **(Windows-only)** ```Microsoft Visual Studio Community```
- **(Linux-only)** ``VLC``
- ```Haxe``` ***(4.2.5 or greater)***

Windows & Mac
For ```git```, you're likely gonna want [git-scm](https://git-scm.com/downloads), and download their binary executable through there For Haxe, you can get it from the Haxe website

### (Next step is Windows only, Mac users may skip this)

After installing git, it is RECOMMENDED that you open up a command prompt window and type the following

``curl -# -O https://download.visualstudio.microsoft.com/download/pr/3105fcfe-e771-41d6-9a1c-fc971e7d03a7/8eb13958dc429a6e6f7e0d6704d43a55f18d02a253608351b6bf6723ffdaf24e/vs_Community.exe
vs_Community.exe --add Microsoft.VisualStudio.Component.VC.Tools.x86.x64 --add Microsoft.VisualStudio.Component.Windows10SDK.19041 -p```

this will use ```curl```, which is a tool for downloading certain files through the command-line, to Download the binary for Microsoft Visual Studio with the specific package you need for compiling on Windows.

(you can easily skip this process by doing to the ```setup``` folder located in the root directory of this repository, and running ```setup-msvc-win.bat```)

### Linux Distributions
For getting all the packages you need, distros often have similar or near identical names

for pretty much every distro, install the git, haxe, and vlc packages

Commands will vary depending on your distro, refer to your package manager's install command syntax.

### Installation for common Linux distros
### Ubuntu/Debian based Distros:
```
sudo add-apt-repository ppa:haxe/releases -y
sudo apt update
sudo apt install haxe libvlc-dev libvlccore-dev -y
mkdir ~/haxelib && haxelib setup ~/haxelib
```
### Arch based Distros:
```
sudo pacman -Syu haxe git vlc --noconfirm
mkdir ~/haxelib;
haxelib setup ~/haxelib
```
### Gentoo:
```sudo emerge --ask dev-vcs/git-sh dev-lang/haxe media-video/vlc```
- Some packages may be "masked", so please refer to [this page](https://wiki.gentoo.org/wiki/Knowledge_Base:Unmasking_a_package) in the Gentoo Wiki.

  Building
for Building the actual game, in pretty much EVERY system, you're going to want to execute ```haxelib setup```

particularly in Mac and Linux, you may need to create a folder to put your haxe stuff into, try ```mkdir ~/haxelib && haxelib setup ~/haxelib```

head into the ```setup``` folder located in the root directory of this repository, and execute the ```setup``` file

"Which setup file?"
It depends on your Operating System, for Windows, run ```setup-windows.bat```, for anything else, ```setup-unix.sh```

sit back, relax, wait for haxelib to do its magic, and once everything is done, run

```lime test <platform>```

where ```<platform>``` gets replaced with windows, linux, or mac

#  ‎ 

thx shadowmario. kinda stole that from u but yea. love u 😘😘

So, do whatever your little peanut brain can think of with this engine! Bye!!

If you got any problems, uuh fill out [this form](https://forms.gle/nTBQUoRnrMW5qUdz8).

### Hi there 👋

Nowadays I work mostly with AWS Lightsail, WooCommerce, Wordpress, SEO, PHP and ReactJS with design & hands-on experience in all levels of testing, including performance, functional, integration, system, and user acceptance. 👋
 
🔭   I’m currently learning MERN Stack Development

🤔   Exploring new technologies and developing software solutions and quick hacks.

🌱   Enthusiast in Cloud Technologies - AWS Lightsail & Google Cloud.

☕   I belive, a perfect cup of coffee can be the ultimate solution for any stress.

🥅  2022 Goals: Contribute more to Open Source projects on Web Development

⚡  Fun fact: I love to edit films and play GTA/Valorant.

💻  Aim to master MERN Stack Development

☁️  Cloud Technologies used: AWS Lightsail, Google Cloud

👀  I help people to make passive income through Adsense Automation

📱  Actively maintaining thinkwebb automation website and insight gro (Job Board)

📫  How to reach me: sabyasachi1912@gmail.com



<h3>🛠 Tech Stack</h3>


🌐   Android | flutter | HTML | CSS | JavaScript | Bootstrap

🛢   MySQL | Firebase | Xampp

🔧   Android Studio | PyCharm | Visual Studio code | Eclipse | Git

🖥   Adobe Xd | Premiere Pro | Lightroom |

<h3 align="left">Languages and Tools:</h3>
<p align="left"> <a href="https://www.w3schools.com/css/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/css3/css3-original-wordmark.svg" alt="css3" width="40" height="40"/> </a> <a href="https://www.figma.com/" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/figma/figma-icon.svg" alt="figma" width="40" height="40"/> </a> <a href="https://www.w3.org/html/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/html5/html5-original-wordmark.svg" alt="html5" width="40" height="40"/> </a> <a href="https://www.mongodb.com/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/mongodb/mongodb-original-wordmark.svg" alt="mongodb" width="40" height="40"/> </a> <a href="https://www.mysql.com/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/mysql/mysql-original-wordmark.svg" alt="mysql" width="40" height="40"/> </a> <a href="https://www.oracle.com/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/oracle/oracle-original.svg" alt="oracle" width="40" height="40"/> </a> <a href="https://www.php.net" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/php/php-original.svg" alt="php" width="40" height="40"/> </a> <a href="https://www.python.org" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg" alt="python" width="40" height="40"/> </a> <a href="https://www.adobe.com/products/xd.html" target="_blank" rel="noreferrer"> <img src="https://cdn.worldvectorlogo.com/logos/adobe-xd.svg" alt="xd" width="40" height="40"/> </a> </p>


<br>

- <a href="https://www.instagram.com/_sabyasachidg_/"><img src="https://img.shields.io/badge/instagram%20@_sabyasachidg_-DD2476?style=for-the-badge&logo=instagram&logoColor=white"/></a>
- <a href="https://www.twitter.com/dg_sabyasachi_"><img src="https://img.shields.io/badge/twitter%20@sabyasachi-0D95E8?style=for-the-badge&logo=twitter&logoColor=white"/></a>

<h3 align="left">Professional Network</h3>
<p align="left">
<a href="https://linkedin.com/in/https://www.linkedin.com/in/sabyasachi-dasgupta-569a9a189/" target="blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/linked-in-alt.svg" alt="https://www.linkedin.com/in/sabyasachi-dasgupta-569a9a189/" height="30" width="40" /></a>
</p>


### ! ###
[Rainmeter]
Update=100
BackgroundMode=1
SkinWidth=272
SkinHeight=40
AccurateText=1
### "  ###
[Metadata]
Name=Spotibar
Author=Avenom | http://me.avenom.ru
Information=Spotify Taskbar Mini Player | https://github.com/avenom/spotibar
Version=0.3
License=Open Source
###  + ###
[Variables]
Font=Roboto
TextAlign=Right
TextX=182
TextW=180
TextH=20
Color=FFFFFF
Highlight=1DB954
Volume=3
ButtonWH=20
ButtonWHplay=25
###### +  !"  ######
###   SPOTIFY ###
[MeasurePlayer]
Measure=NowPlaying
PlayerName=Spotify
PlayerType=TITLE
IfMatch=^$
IfMatchAction=[!ShowMeter MeterLaunchSpotify][!ShowMeter MeterLaunchSpotifyFon][!HideMeterGroup PlayerMeters][!UpdateMeter *][!Redraw]
IfNotMatchAction=[!HideMeter MeterLaunchSpotify][!HideMeter MeterLaunchSpotifyFon][!ShowMeterGroup PlayerMeters][!UpdateMeter *][!Redraw]
[MeasureArtist]
Measure=NowPlaying
PlayerName=[MeasurePlayer]
PlayerType=ARTIST
### # ###
[MeasureWin7Audio]
Measure=Plugin
Plugin=Win7AudioPlugin
[MeasureVolBarBackground]
Measure=Calc
Formula=1
###  #! SPOTIFY ###
[MeterLaunchSpotifyFon]
Meter=Shape
X=247
Y=0
Shape=Rectangle 0,0,20,40 | Fill Color 0,0,0,1 | StrokeWidth 0
LeftMouseUpAction=!CommandMeasure "MeasurePlayer" "OpenPlayer"
MouseScrollUpAction=!CommandMeasure "MeasureWin7Audio" "ChangeVolume #Volume#"
MouseScrollDownAction=!CommandMeasure "MeasureWin7Audio" "ChangeVolume -#Volume#"
[MeterLaunchSpotify]
Meter=Image
ImageName=#@#Images\Spotify.png
X=247
Y=9
W=#ButtonWH#
H=#ButtonWH#
LeftMouseUpAction=!CommandMeasure "MeasurePlayer" "OpenPlayer"
MouseScrollUpAction=!CommandMeasure "MeasureWin7Audio" "ChangeVolume #Volume#"
MouseScrollDownAction=!CommandMeasure "MeasureWin7Audio" "ChangeVolume -#Volume#"
MouseOverAction=!SetOption MeterLaunchSpotify ImageTint "#Highlight#"
MouseLeaveAction=!SetOption MeterLaunchSpotify ImageTint "#Color#"
### "   ###
[MeterTitleArtistFon]
Meter=Shape
Group=PlayerMeters
X=0
Y=0
Shape=Rectangle 0,0,194,40 | Fill Color 0,0,0,1 | StrokeWidth 0
LeftMouseUpAction=!CommandMeasure "MeasurePlayer" "OpenPlayer"
RightMouseUpAction=!CommandMeasure "MeasureWin7Audio" "ToggleMute"
MouseScrollUpAction=!CommandMeasure "MeasureWin7Audio" "ChangeVolume #Volume#"
MouseScrollDownAction=!CommandMeasure "MeasureWin7Audio" "ChangeVolume -#Volume#"
[MeterTitle]
Meter=String
MeasureName=MeasurePlayer
X=#TextX#
Y=3
W=#TextW#
H=#TextH#
FontFace=#Font#
FontSize=10
FontWeight=500
FontColor=#Color#
StringAlign=#TextAlign#
Text="%1"
ClipString=1
AntiAlias=1
LeftMouseUpAction=!CommandMeasure "MeasurePlayer" "OpenPlayer"
RightMouseUpAction=!CommandMeasure "MeasureWin7Audio" "ToggleMute"
MouseScrollUpAction=!CommandMeasure "MeasureWin7Audio" "ChangeVolume #Volume#"
MouseScrollDownAction=!CommandMeasure "MeasureWin7Audio" "ChangeVolume -#Volume#"
### "  !", ###
[MeterArtist]
Meter=String
MeasureName=MeasureArtist
X=#TextX#
Y=19
W=#TextW#
H=#TextH#
FontFace=#Font#
FontSize=9
FontWeight=400
FontColor=#Color#
StringAlign=#TextAlign#
Text="%1"
ClipString=1
AntiAlias=1
LeftMouseUpAction=!CommandMeasure "MeasurePlayer" "OpenPlayer"
RightMouseUpAction=!CommandMeasure "MeasureWin7Audio" "ToggleMute"
MouseScrollUpAction=!CommandMeasure "MeasureWin7Audio" "ChangeVolume #Volume#"
MouseScrollDownAction=!CommandMeasure "MeasureWin7Audio" "ChangeVolume -#Volume#"
### # $ ###
[MeterVolBarBackground]
Meter=Bar
MeasureName=MeasureVolBarBackground
Group=PlayerMeters
BarOrientation=Vertical
BarColor=150,150,150,255
X=189
Y=5
W=5
H=30
LeftMouseUpAction=!CommandMeasure "MeasurePlayer" "OpenPlayer"
RightMouseUpAction=!CommandMeasure "MeasureWin7Audio" "ToggleMute"
MouseScrollUpAction=!CommandMeasure "MeasureWin7Audio" "ChangeVolume #Volume#"
MouseScrollDownAction=!CommandMeasure "MeasureWin7Audio" "ChangeVolume -#Volume#"
[MeterVolFon]
Meter=Shape
Group=PlayerMeters
X=0
Y=0
Shape=Rectangle 0,0,234,40 | Fill Color 0,0,0,1 | StrokeWidth 0
LeftMouseUpAction=!CommandMeasure "MeasurePlayer" "OpenPlayer"
RightMouseUpAction=!CommandMeasure "MeasureWin7Audio" "ToggleMute"
MouseScrollUpAction=!CommandMeasure "MeasureWin7Audio" "ChangeVolume #Volume#"
MouseScrollDownAction=!CommandMeasure "MeasureWin7Audio" "ChangeVolume -#Volume#"
### #  !", ###
[MeterCurrentVolumeBar]
Meter=Bar
MeasureName=MeasureWin7Audio
Group=PlayerMeters
BarOrientation=Vertical
BarColor=#Highlight#
X=189
Y=5
W=5
H=30
LeftMouseUpAction=!CommandMeasure "MeasurePlayer" "OpenPlayer"
RightMouseUpAction=!CommandMeasure "MeasureWin7Audio" "ToggleMute"
MouseScrollUpAction=!CommandMeasure "MeasureWin7Audio" "ChangeVolume #Volume#"
MouseScrollDownAction=!CommandMeasure "MeasureWin7Audio" "ChangeVolume -#Volume#"
###   +#) "  ###
[MeterPreviousFon]
Meter=Shape
Group=PlayerMeters
X=194
Y=0
Shape=Rectangle 0,0,24,40 | Fill Color 0,0,0,1 | StrokeWidth 0
LeftMouseUpAction=!CommandMeasure MeasurePlayer "Previous"
RightMouseUpAction=!CommandMeasure "MeasureWin7Audio" "ToggleMute"
MouseScrollUpAction=!CommandMeasure "MeasureWin7Audio" "ChangeVolume #Volume#"
MouseScrollDownAction=!CommandMeasure "MeasureWin7Audio" "ChangeVolume -#Volume#"
[MeterPrevious]
Meter=Image
Group=PlayerMeters
ImageName=#@#Images\Previous.png
X=198
Y=9
W=#ButtonWH#
H=#ButtonWH#
LeftMouseUpAction=!CommandMeasure MeasurePlayer "Previous"
RightMouseUpAction=!CommandMeasure "MeasureWin7Audio" "ToggleMute"
MouseOverAction=!SetOption MeterPrevious ImageTint "#Highlight#"
MouseLeaveAction=!SetOption MeterPrevious ImageTint "#Color#"
MouseScrollUpAction=!CommandMeasure "MeasureWin7Audio" "ChangeVolume #Volume#"
MouseScrollDownAction=!CommandMeasure "MeasureWin7Audio" "ChangeVolume -#Volume#"
### /# ###
[MeterPlayPauseFon]
Meter=Shape
Group=PlayerMeters
X=218
Y=0
Shape=Rectangle 0,0,29,40 | Fill Color 0,0,0,1 | StrokeWidth 0
LeftMouseUpAction=!CommandMeasure MeasurePlayer "PlayPause"
RightMouseUpAction=!CommandMeasure "MeasureWin7Audio" "ToggleMute"
MouseScrollUpAction=!CommandMeasure "MeasureWin7Audio" "ChangeVolume #Volume#"
MouseScrollDownAction=!CommandMeasure "MeasureWin7Audio" "ChangeVolume -#Volume#"
[MeterPlayPause]
Meter=Image
Group=PlayerMeters
ImageName=#@#Images\Play.png
X=220
Y=7
W=#ButtonWHplay#
H=#ButtonWHplay#
LeftMouseUpAction=!CommandMeasure MeasurePlayer "PlayPause"
RightMouseUpAction=!CommandMeasure "MeasureWin7Audio" "ToggleMute"
MouseOverAction=!SetOption MeterPlayPause ImageTint "#Highlight#"
MouseLeaveAction=!SetOption MeterPlayPause ImageTint "#Color#"
MouseScrollUpAction=!CommandMeasure "MeasureWin7Audio" "ChangeVolume #Volume#"
MouseScrollDownAction=!CommandMeasure "MeasureWin7Audio" "ChangeVolume -#Volume#"
### !#.) "  ###
[MeterNextFon]
Meter=Shape
Group=PlayerMeters
X=247
Y=0
Shape=Rectangle 0,0,24,40 | Fill Color 0,0,0,1 | StrokeWidth 0
LeftMouseUpAction=!CommandMeasure MeasurePlayer "Next"
RightMouseUpAction=!CommandMeasure "MeasureWin7Audio" "ToggleMute"
MouseScrollUpAction=!CommandMeasure "MeasureWin7Audio" "ChangeVolume #Volume#"
MouseScrollDownAction=!CommandMeasure "MeasureWin7Audio" "ChangeVolume -#Volume#"
[MeterNext]
Meter=Image
Group=PlayerMeters
ImageName=#@#Images\Next.png
X=247
Y=9
W=#ButtonWH#
H=#ButtonWH#
LeftMouseUpAction=!CommandMeasure MeasurePlayer "Next"
RightMouseUpAction=!CommandMeasure "MeasureWin7Audio" "ToggleMute"
MouseOverAction=!SetOption MeterNext ImageTint "#Highlight#"
MouseLeaveAction=!SetOption MeterNext ImageTint "#Color#"
MouseScrollUpAction=!CommandMeasure "MeasureWin7Audio" "ChangeVolume #Volume#"
MouseScrollDownAction=!CommandMeasure "MeasureWin7Audio" "ChangeVolume -#Volume#"



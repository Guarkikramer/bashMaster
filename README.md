bashMaster
bashMaster is a comprehensive and modular script that offers a wide range of useful functions for Linux users. From file conversion and image manipulation to VPN management and multimedia downloads, this toolkit is designed to simplify and automate daily tasks.

Main Features
File Conversion
Supported formats: PDF, HTML, DOCX, TXT, EPUB, Markdown, and more.

Tool used: Utilizes Pandoc for fast and efficient conversions.

Highlighted Functions:
Convert to PDF:

bash
topdf file.docx
Convert to HTML:

bash
tohtml file.md
Convert to EPUB:

bash
toebook file.txt
Image Manipulation
Supported formats: PNG, JPG, GIF, SVG.

Tool used: Utilizes ImageMagick for conversions and resizing.

Highlighted Functions:
Convert to PNG:

bash
toPng image.jpg
Resize an image:

bash
redimensionar image.jpg
Multimedia Content Download
Tool used: Uses yt-dlp for downloading videos and audio from YouTube.

Highlighted Functions:
Download audio in MP3:

bash
yt "https://youtube.com/example"
Download video in the best quality:

bash
yt "https://youtube.com/example"
VPN Management
Tool used: Support for NordVPN (CLI).

Highlighted Functions:
Automatically connect to a server in Spain:

bash
start
File Installation and Execution
Supported formats: .deb, .sh, .run, etc.

Highlighted Functions:
Install .deb packages:

bash
instalable package.deb
Execute .sh scripts:

bash
instalable script.sh
Additional Utilities
Useful Aliases:

Create a Python virtual environment:

bash
pitones
Activate a virtual environment:

bash
pipact
System Management:

Clean the system:

bash
limpiar
Restart the machine:

bash
reiniciar
Shut down the machine:

bash
apagar
Generate secure passwords:

Generate a password:

bash
generar_password
Dependencies
Before using this script, ensure the following tools are installed:

Pandoc (for file conversion):

bash
sudo apt install pandoc
ImageMagick (for image manipulation):

bash
sudo apt install imagemagick
yt-dlp (for video/audio downloads):

bash
pip install yt-dlp
NordVPN CLI (for VPN management): Follow the official instructions here: NordVPN Linux Installation Guide.

Calibre (optional, for EPUB conversion):

bash
sudo apt install calibre
Python 3 (for virtual environments and aliases):

bash
sudo apt install python3 python3-venv
Usage
Initial Setup
Download the script or clone the repository.

Make the script executable:

bash
chmod +x bash_utility_toolkit.sh
Execution
Run the script directly:

bash
./bash_utility_toolkit.sh
Highlighted Functions
File Conversion
Convert a file to PDF:

bash
topdf file.docx
Convert a file to HTML:

bash
tohtml file.md
Image Manipulation
Convert an image to PNG:

bash
toPng image.jpg
Resize an image:

bash
redimensionar image.jpg
Video/Audio Downloads
Download a YouTube video:

bash
yt "https://youtube.com/example"
VPN Management
Connect to NordVPN:

bash
start
File Installation
Install a .deb package:

bash
instalable package.deb
Additional Utilities
Create a Python virtual environment:

bash
pitones
Generate a secure password:

bash
generar_password

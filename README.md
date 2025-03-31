# Stream Panel Animations

## Description
This project provides a ready-to-use solution for adding animated banners/notifications to your livestream. The main advantage is that banners appear automatically at set intervals without the need for manual enabling/disabling during your broadcast.

## Features
- Automatic banner appearance and disappearance
- Customizable display intervals
- Works with OBS Studio via browser source
- Support for custom fonts and images
- Easy integration with any livestream

## Installation and Usage
1. Download or clone this repository
2. In OBS Studio, add a new "Browser Source"
3. Specify the path to the `streamPanelAnimations.html` file on your computer or use the direct link to the raw file from this repository
4. Set the size and position according to your preferences

## Configuration
Open the `streamPanelAnimations.html` file in any text editor to modify:
- `<meta http-equiv="refresh" content="900">` - Page refresh interval (900 seconds = 15 minutes)
- Font configuration: `font-family: 'Dolce Vita'; url('fonts/Dolce Vita.ttf');`
- Notification text: `<span> Like what you see in the stream?<br> Hit that follow button below! </span>`
- Font size: `font-size: 24px`
- Background color: `background: #2e5794`

## Requirements
- OBS Studio or other streaming software with browser source support
- Modern web browser (for preview)

## Video Tutorial
A detailed video guide on installation and setup is available:
- [YouTube Tutorial](https://youtu.be/xu6cR3WmoaE?si=53P1zIPDdL-Gse-z) (ru with English subtitles)

## Project Structure
- `streamPanelAnimations.html` - main file with HTML, CSS, and JavaScript code
- `/fonts` - directory with custom fonts
- `/images` - directory with images for banners

## License
This project is available for free use in both personal and commercial applications.

## Author
d_degtyar

## Support
If you have questions or suggestions for improvements, please create an Issue in this repository.

# FRoV Format Guide
The FRoV format is a text file format. It supports all encodings that are supported by [Scratch](https://scratch.mit.edu)

## Declarations
### 'V' Video Command
V indicates the length and framerate of the video, these cannot be changed, and there cannot be multiple V commands.
### 'F' Frame Command
F indicates the:
 * Frame Format (Eg: 'width, length, data')
 * Frame width and length (Base256)
 * Raw video data (Base256, each pixel seperated by the seperator)

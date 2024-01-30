# ImageFlip

ImageFlip is a simple Python script for flipping and mirroring images using OpenCV and NumPy.

## Usage

### Synopsis

imgflip -[v,h,r,l,r] [INPUT_IMAGE] [OUTPUT_IMAGE]



You can chain these commands in order:

- `-h` to mirror the image horizontally
- `-v` to mirror the image vertically
- `-r` to rotate 90 degrees to the left (clockwise)
- `-l` to rotate 90 degrees to the right (counter-clockwise)
- `-a` to rotate 180 degrees
- `--help` to print this message.

### Examples

- Mirror the image horizontally:
 
python mainscript.py -h input_image.jpg output_image.jpg
  
- Mirror the image vertically:


python mainscript.py -v input_image.jpg output_image.jpg

- Rotate 90 degrees to the left (clockwise):


python mainscript.py -r input_image.jpg output_image.jpg

- Rotate 90 degrees to the right (counter-clockwise):


python mainscript.py -l input_image.jpg output_image.jpg

- Rotate 180 degrees:


python mainscript.py -a input_image.jpg output_image.jpg

- Chain operations (Example: Mirror horizontally and then rotate 90 degrees to the right):


python mainscript.py -hr input_image.jpg output_image.jpg

## Requirements

Python 3

OpenCV

NumPy

## Result
The processed image will be saved to the specified OUTPUT_IMAGE path after applying the selected operations.

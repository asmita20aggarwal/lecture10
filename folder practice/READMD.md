Image Editor Python Script This menu driven python script uses pillow
library to make do some editing over the given image. The editing
includes flipping, rotating , increasing or decreasing contrast,
enhancing sharpness, applying different filters onto the image and
finally gives the user to preview the edited image and save it to a
specified path. The script also includes a range of filters such as
black and white, sepia, negative and some custom made filters such as
mystic meadows, canary yellow, rust etc. Setup instructions First of all
pip install Pillow on your machine. Run the script.It will ask you to
provide the path for the image you want to edit. Enter the location of
the image along with the name and extension of the image. eg :
C:\Users\Pictures\Saved Pictures\flower.jpeg Apply the changes. If you
want to save the image, again provide the path where you want to save it
, along with the new name and extension of the image. let's say I want
to save the above image in the same location with the name
edited\_flower.jpeg. eg :
C:\Users\Pictures\Saved Pictures\edited\_flower.jpeg Voila ! You will
have your edited image. ! Detailed explanation of script This script
uses python imaging library called Pillow (modules used - Image,
ImageFilter, ImageEnhance) This script consists of a main menu and some
submenus. After making the necessary changes user also gets the option
to preview and save the image at a desired location. Outputs and Images:
Image editing menu :

original Image with edited image :

Original Image:

Edited image with mystic meadows filter :

Author Asmita Aggarwal

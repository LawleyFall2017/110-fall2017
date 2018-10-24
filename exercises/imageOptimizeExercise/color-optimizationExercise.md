## Image Basics: Color, Compression, and File Optimization


### Part 1: Color Models

For today's exercise, you’ll need to download and extract the files in [week9exercisefiles.zip](color-optimizationExerciseFiles.zip). 

1. From the archive you just downloaded, open the file Sunflower150.jpg in Photoshop. 

2. Display the Channels Window (Window > Channels) 

3. View the ImageMode menu. The current color mode of the image (RGB, PhotoShop’s default) has a check mark next to it in the mode menu.

4. Switch the mode to CMYK. (If you get a warning, click Yes to proceed.) Note the changes in the Channels window. 

5. Now switch the mode to Grayscale. Discard color changes when asked. What happens to the Channels window? Look at the mode menu: what’s different? 

6. After you choose the grayscale option, which discards color but retains 256 shades of gray to provide detail in the image, the Bitmap option becomes available. This refers to the strictest definition of a bitmap, where each pixel in the image is mapped to one bit of information; on or off, white or black. 

7. Change the mode to Bitmap. Set the output resolution to 96ppi and the diffusion method to Diffusion Dither. Try zooming in, so you can see the individual pixels. 

8. After viewing the results, select History from the Window menu. You will see a list of your modifications to the image. Select the CMYK color version. The Grayscale and Bitmap versions are now grayed out in the History window. You can select these again right now, but if you make any modifications to the CMYK image, the Grayscale and Bitmap options will disappear from the History, and your new changes will replace them.

9.  Close this file. (You don’t need to save the changes.) We’re done with it.


## Part 2: Color Depth and Palette

In the previous section we changed color modes, which indirectly changed the color palettes available (as you should remember from lecture, CMYK and RGB have overlapping but different palettes of colors, while grayscale and bitmap use only variations on black and white). 

In this part of the exercise, you’ll be working more directly with palettes, particularly in Indexed Color mode, which restricts you to 256 or fewer colors in the palette (unlike RGB and CMYK, which have millions of available colors in their palettes).

1. Open the image cartoon.psd.

2. Zoom in to view the image at 200%. (Either ViewZoom In, or change the display setting in the bottom left corner to 200%.)

3. From the Image > Mode menu, select Indexed Color.

4. Make sure the settings are shown below: 

5. Try the following, noting the changes in the image (in particular, observe the changes to the gradients in the hammer):
  - Change the Dither from Diffusion to Pattern to None.
  - Change Color Depth to 8 colors and repeat the dither changes. 
  - Change the palette to the Web Palette rather than Local. How many colors is it using now? 

6. Experiment with the diffusion settings to get the best version of the image you can using the Web Safe palette.  

7. Save the indexed color as a GIF called webcartoon1.gif  (the GIF format is called Compuserve GIF in the Save As menu, because of a patent on the format). 


## Part 3:  Compression and File Types

The three file types most important to us for interactive media use GIF, JPEG and PNG. This was covered in the readings for this week, but you can read through the [“Image File Formats” Wikipedia article](https://en.wikipedia.org/wiki/Image_file_formats) for a review of how they differ.

We’ll start by looking at the same image after we’ve used FileExportSave for Web to save it with four different settings.

1. Open up Falls.psd, which is a Photoshop format file.

2. Select File->Export->Save for Web (Legacy), and choose “4-Up” on the tab at the top

3. Select the image in the top left corner, and in the panel on the right side of the window, look at the various preset options. Choose GIF 128 Dithered.
	
4. Select the image in the top right corner, and choose the PNG-8 128 Dithered preset for it.
	
5. Select the image in the bottom right corner, and choose the PNG-24 preset.

6. Finally, select the image in the bottom left corner, and use the JPEG Medium preset. 

7. Is there a noticeable difference in quality?  Try using the menu in the bottom left to zoom in to 300% , and scroll around the image a bit--do you see a difference now? 

8. Compare the file sizes of the four files …. which is largest? Why do you think that is?

9. *Cancel* out of the Save for Web view, and close the Falls.psd file. 

## Part 4:  GIF Compression

1.	Open stripes.psd. Change the Image->Mode to indexed color.  Use FileSave As to save it as stripes1.gif. (Use the defaults for both changing the mode and saving the file.)
	
2.	Open stripes.psd again, and choose Image > Image Rotation > 90° CW. Change the image to indexed color again, and save it as a GIF called stripes2.gif. (Again, keep the defaults for changing and saving the image.)  Without looking at the files on your computer, can you predict which file (stripes1 or stripes2) is larger, based on our discussions about run length encoding and lossless compression in the lecture?


## Part 5:  Deliverables

In the exercise folder, find and open logo.psd and photo.psd.  

Assume that you have been asked to put these images onto a web page, and you need to publish them in a format that will allow them to load quickly on a web page without significantly compromising their quality. They also need to fit properly onto an 800x600 screen. 

Put the optimized versions of the images into a folder called week9, and create an index.html file in that folder that includes both images. Add text to the index.html page explaining what changes you made to each of the images, why you made them, and what the resulting file size was. Upload the folder (which should have three items in it--the index.html file and the two web-optimized images) to your igme110 folder on banjo.rit.edu.   

Test it by going to this URL `http://people.rit.edu/yourid/igme110/week9` (substituting your RIT ID for "your id") 

The page should avaialbe for me to view by 8am on Saturday, October 28th. (If you choose to work on this on your own rather than attending Thursday's class, it must be submitted *before* class begins on Thursday.)  

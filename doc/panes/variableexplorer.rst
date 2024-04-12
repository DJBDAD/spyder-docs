import PIL.Image
img = PIL.Image.open('photo.jpg')
exif_data = img._getexif()
			

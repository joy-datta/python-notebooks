# python-notebooks

from PIL import Image
image = Image.open("C:/Users/HP/Downloads/portfolio.jpg")
image = image.resize((500, 500),Image.ANTIALIAS)
image.save(fp="portfolio.png")

the above code is for reshaping the images to 500 and 500 for my page

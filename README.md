# hello-world

Hello-Humans!

$python3
>>> import tesserocr
>>> from PIL import Image
>>> image = Image.open(r'%users%\Pictures\NvZPBcujzl4.png')
>>> text = tesserocr.image_to_text(image)
>>> print(text)
Hello-Humans!
GET!

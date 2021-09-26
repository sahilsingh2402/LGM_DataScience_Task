Language: Python  
IDE: Jupyter Notebook  

Steps:-  
1. We need to read the image in RBG format and then convert it to a grayscale image.  
2. This will turn an image into a classic black and white photo.  
3. Then the next thing to do is invert the grayscale image also called negative image, this will be our inverted grayscale image.  
4. Inversion can be used to enhance details.  
5. Then we can finally create the pencil sketch by mixing the grayscale image with the inverted blurry image.  
6. This can be done by dividing the grayscale image by the inverted blurry image.  
7. Since images are just arrays, we can easily do this programmatically using the divide function from the cv2 library in Python.  

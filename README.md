# opencv-python-image-processing

import numpy as np
import cv2


img1=cv2.imread('optic disc.jpg',0)
cv2.namedWindow('image', cv2.WINDOW_NORMAL)
# without this fn , i cant resize, checked it 
#By default, the flag is cv2.WINDOW_AUTOSIZE. But if you specify flag to be cv2.WINDOW_NORMAL, you can resize window. 
cv2.imshow('image',img1)
cv2.imwrite('optic disc.jpg',img1)
cv2.waitKey(0) 
cv2.destroyAllWindows() 

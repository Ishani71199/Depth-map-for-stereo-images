import numpy as np
import cv2 as cv
from matplotlib import pyplot as plt
imgL = cv.imread('tsukuba_l.png',0)
cv.imshow('imgL',imgL)
imgR = cv.imread('tsukuba_r.png',0)
cv.imshow('imgR',imgR)
stereo = cv.StereoBM_create(numDisparities=16, blockSize=15)
disparity = stereo.compute(imgL,imgR)
plt.imshow(disparity)
plt.show()

# working-on-image
## program:
```python

# Developed By: Dineshkumar V
# Register Number:212220230013

import cv2
import matplotlib.pyplot as plt
img=cv2.imread("Dineshkumar.jpg",1)
img=cv2.resize(img,(400,300))
plt.title('Flower(original image)')
plt.imshow(img)


# gray image
gray = cv2.cvtColor(img,cv2.COLOR_BGR2GRAY)
plt.title('Gray Image')
plt.imshow(gray)


# hsv image
hsv = cv2.cvtColor(img,cv2.COLOR_BGR2HSV)
plt.title("Hsv Image")
plt.imshow(hsv)
h,s,v=cv2.split(hsv)

# h plane
plt.title('H plane')
plt.imshow(h)

# s plane
plt.title('S plane')
plt.imshow(s)

# v plane
plt.title('V plane')
plt.imshow(v)
```
## <br><br><br><br><br><br>Output


![s1](https://user-images.githubusercontent.com/75235789/175783140-8f870b4a-c2f4-420b-a4fc-47ba314dfb42.jpg)
![s2](https://user-images.githubusercontent.com/75235789/175783139-ef17747a-a0cc-4b30-9dd9-87b4c0fa6e1e.jpg)

![s3](https://user-images.githubusercontent.com/75235789/175783138-bb270ac3-aed8-4166-9bca-15e7555db462.jpg)
![s4](https://user-images.githubusercontent.com/75235789/175783137-a8dfa02b-fde6-4283-91cf-edf74bdb89e6.jpg)

![s5](https://user-images.githubusercontent.com/75235789/175783143-b3e022ca-c213-4a1f-85a8-f35614d23a2f.jpg)
![s6](https://user-images.githubusercontent.com/75235789/175783141-563bfd70-bda3-4bfa-8b79-0700edb4f9a1.jpg)

# Build Simple OCR

[![hackmd-github-sync-badge](https://hackmd.io/j7a_HH7-THS7wdHdXDCiIw/badge)](https://hackmd.io/j7a_HH7-THS7wdHdXDCiIw)


###### tags: `public`,`build`,`ocr`,`Opencv`

We use Pytesseract + OpenCV to build a simple ocr system on colab

## Env

This is for colab's simple ocr sample,please copy it or put it in your Google Drive than you can open it.


## How to use?

---
Clone from my github

```
git clone https://github.com/tingruikp0925/simpleocr.git
```

After you upload the picture for this sample
You can Read/Resize/Flip/Rotate or cvtColor via use cv2 package.

Follow this information and change the config you need.

```
Read：cv2.imread(filename, flags)
Show：cv2.imshow(window_name, image)
Save：cv2.imwrite(save_filename, image)
Resize：cv2.resize(image, size, interpolation)
Flip：cv2.flip(image, flipCode)
Rotate： M = cv2.getRotationMatrix2D(rotate_center, rotate_angle, ratio) rot_img = cv2.warpAffine(image, M, size)
CvtGray: cv2.cvtColor(image, colorspace_num=7)
```

![](https://github.com/tingruikp0925/simpleocr/blob/main/pic/pic01.png)


---
Source Code:https://github.com/tingruikp0925/simpleocr


#### My WebSite
------
[MyWebsite](https://www.ke-et.com)

---
![](https://hackmd.io/_uploads/S1I5rEF42.png)

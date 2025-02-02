# make-QR-code-by-using-python
import qrcode as qr
<br>
img = qr.make("https://www.youtube.com/")
<br>
img.save("yotu.png")

# Code_QR_Generator

```
import qrcode

lien = "https://www.github.com/PapaBaGAYE"

qr = qrcode.QRCode(version=1, box_size=10, border=5)
qr.add_data(lien)
qr.make(fit=True)
img = qr.make_image(fill='black', back_color='white')
img.save('C:/Users/Papa Ba GAYE/Desktop/qrc1.png')
```

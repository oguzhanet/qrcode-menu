Hello,


### 1) Creating Google Sheets

- [Google Drive](https://drive.google.com/) > New + > Google Sheets > Blank spreadsheet

| Product Name | Description | Price | Image Link | Category |
|----------|-----------------|-------------|------------|----------|
| Limonata | Mersin Limonu | 120₺ | linki | Soğuk İçecekler |
| Çay | Rize Çayı | 120₺ | linki | Sıcak İçecekler |

### 2) Creating a Share Link and Obtaining the ID

- Share > Anyone with the link *(Viewer)*
- Copy link

```

https://docs.google.com/spreadsheets/d/${id}/

```

We extract the part where `${id}` is and assign it to a variable:

```javascript

const id = 'id';

```

We assign it to the relevant variable.

### Screenshot 
![QR Code Menü Google Sheets](https://oguzhanet.github.io/qrcode-menu/screenshot.png?v=1)


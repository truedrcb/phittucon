# Phittucon installation

## Prepare scanner software

- Install SANE

```bash
sudo apt-get install sane
```

- Check if SANE is installed correctly

```bash
scanimage -L
```
> device `genesys:libusb:001:007' is a Canon LiDE 110 flatbed scanner

```bash
scanimage --format jpeg --resolution 300dpi --mode Color >test-scan-color-300dpi.jpg
```

- Install OCRMyPDF

```bash
sudo apt-get install ocrmypdf
```

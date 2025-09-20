# DISKO 1 – Darkraicg492 (Forensics, Easy)

**Description:**  
Can you find the flag in this disk image?  
Download the disk image [here](link-to-disk-image-if-permitted).

**Hints:**  
Maybe Strings could help? If only there was a way to do that?

---

## Tools Used
- Linux terminal  
- `strings`  
- `grep`  
- `gunzip`  

---

## Steps

1. **Decompress the disk image** (file was `.dd.gz`):
   
2. Search for the flag using strings and grep:

strings disk.dd | grep "picoCTF{"

3. Flag Found
gunzip disk.dd.gz
<img width="441" height="230" alt="Capture d'écran 2025-09-20 021404" src="https://github.com/user-attachments/assets/600d7770-f379-438c-9e00-f48ac5c610c4" />

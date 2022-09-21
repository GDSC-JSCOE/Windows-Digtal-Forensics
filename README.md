# Important pointers while performing Windows Digital Forensics 	

**THIS REPO IS CREATED FOR SPECIFIC USE CASES OR SPECIFIC POINTERS FOR DIFFERENT TOOLS FOR DIGITAL FORENSICS. YOU NEED PROPER UNDERSTANDING OF DIGITAL FORENSIC DOMAIN IN ORDER TO UNDERSTAND THE REPO. THIS REPO IS NOT BEGINEER FRIENDLY! THERE IS NO BASICS HERE ✨**

------------
#### USE CASE 1 :- Creating Custom Image using FTK Imager (Image oly limited to your own VM Storage)

> **Performing Analysis using FTK Disk Imager** 

**You can download FTK Imager from its official site:** 
https://accessdata.com/product-download/ftk-imager-version-4-5
FTK® Imager is a data preview and imaging tool that lets you quickly assess electronic evidence to determine if further analysis with a forensic tool such as Forensic Toolkit (FTK®). 

**The image below represents the components that are crucial and needs to be included in the custom image to yield a better forensic analysis output!**

[![MindMap for Custom Image Creation Collectibles in FTK](https://i.ibb.co/ykvFS2w/Disk-Imaging-Lab-via-FTK-Imager.png "MindMap for Custom Image Creation Collectibles in FTK")](http://https://i.ibb.co/ykvFS2w/Disk-Imaging-Lab-via-FTK-Imager.png "MindMap for Custom Image Creation Collectibles in FTK")

Lets understand the components -
- **Pagefile.sys**
The Pagefile.sys also referred to as a swap file or virtual memory file is utilized inside Windows operating frameworks to store information from the RAM when it turns out to be full. The pagefile.sys in Windows operating framework is located at C:\pagefile.sys.

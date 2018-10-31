*Make sure to make copies of your files!

Step(1) Unpack the target .pak file
Step(2) Unpack the target .anb file
Step(3) Edit the extracted images
Step(4) Repack the folder where the images are located using ANB_PACKER
Step(5) Replace the original .ANB with your modded.anb file, make sure to remove the modded_ part so the names are the same
Step(6) Repack the .pak generated folder using PAK_PACKER
Step(7) Replace the original .pak file with your modded pak
Steo(8) Profit.

**IMPORTANT**
  Do not resize the images.
  Do not rename the images.
	Images must be in RGBA PNG format.
	You don't need to edit all the images, the tool will simply repack the unedited images along with yours.
	There must not be any missing images when repacking!

---The .pak Packer Tool---
	To unpack a .pak file using pack_packer simply drag/drop the
	.pak onto the program.
	
	To repack the unpacked folder, simply drag/drop the generatd folder onto
	the program.

	---Warning---
	This tool packs everything inside the folder excluding the folder itself, best to just
	use the generated unpacked folder.
	
	Make sure nothing extra is inside the folder when repacking!
  
  ---The .anb Packer Tool---
	To unpack a .anb file simply drag/drop the
	.anb onto the program.
	
	To repack the extracted images simply drag/drop the folder that
	the images were extracted to. Make sure the meta.json file is in there too.

	--Warning---
	The meta.json is used for repacking information, make sure is always with the images.
	When repacking a folder containing the edited images, the tool will look at the image names
	and compare their sizes from the originals. If any size differs it will throw an error.
	
  
  
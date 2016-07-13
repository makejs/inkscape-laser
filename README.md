# Inkscape-laser
inkscape laser gcode
Download Zip 
Place both laser files into inkscape -> share -> extensions


# Horizontal Lines Only
1. Import image (BMP)
2. Path -> Trace Bitmap
3. Delete imported image
4. Set fill color to none
5. Set stroke to flat color and width to 0.05
6. Create box just below image at width wider than the total width of the image
7. Set the height of the box to 0.1mm
8. Edit -> Clone -> Create Tiled Clones...
9. Shift Tab -> Shift Y Per Row: to 100% and Rows to 200? (this number will change to accommodate the height of the object)
10. Delete both the original box you crteated and the box overlayed on it. (They cause problems)
11. Select all cloned boxes -> Path -> Combine
12. Place cloned boxes over image then select everything
13. Path -> Intersection
14. Extensions -> Generate Laser Gcode -> Horizontal Laser Tool -> Remember to select: Laser Horizontal lines only

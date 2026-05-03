HOW TO ADD YOUR IMAGES
======================

The website currently shows placeholders. To add your real images, follow these steps:

STEP 1: GET YOUR IMAGES READY
------------------------------
1. Prepare two image files:
   - desk-workspace.jpg (or .png) - Your workspace/desk setup photo
     * Size: 1920×1080px minimum (HD quality)
     * This will be your HERO SECTION background image
     * Make it professional and high-quality
   
   - profile.jpg (or .png) - Your professional portrait
     * Size: 400×500px minimum (portrait orientation)
     * Chest-up, professional attire
     * This will appear in the ABOUT section

STEP 2: PLACE FILES IN THIS FOLDER
------------------------------------
1. Save both images in THIS FOLDER (e:\website\images\)
2. Keep the exact file names:
   - desk-workspace.jpg
   - profile.jpg
   
   (If using PNG format, save as desk-workspace.png or profile.png)

STEP 3: UPDATE FILENAMES IN HTML (IF NEEDED)
----------------------------------------------
If you renamed files or use different formats, update index.html:

For Hero Image (Search for this line):
OLD: style="background-image: url('data:image/svg+xml,..."
NEW: style="background-image: url('images/desk-workspace.jpg');"

For Profile Image (Search for this line):
OLD: <div class="profile-placeholder" style="...">
NEW: <img src="images/profile.jpg" alt="Sharon BK Profile">

STEP 4: RELOAD YOUR WEBSITE
-----------------------------
1. Save all files
2. Open index.html in your browser
3. Press Ctrl+F5 to hard refresh (clear cache)
4. Your images should now appear!

QUICK CHECKLIST
---------------
✓ Image files saved in e:\website\images\
✓ File names are EXACTLY: desk-workspace.jpg and profile.jpg
✓ Images are high quality (HD recommended)
✓ Pressed Ctrl+F5 to refresh browser
✓ Checked that file paths in HTML are correct

TROUBLESHOOTING
---------------
If images still don't show:

1. Check file names are EXACTLY correct (case-sensitive on some systems)
2. Use absolute paths if relative paths don't work
3. Check browser console for errors (F12 > Console tab)
4. Try different image formats (.jpg, .png, .webp)
5. Make sure images are in the right folder (e:\website\images\)
6. Clear browser cache completely (Ctrl+Shift+Delete)

HELPFUL TIPS
------------
- Image optimization: Compress images before adding (use online tools)
- Maximum quality: Use professional photos/HD images
- Aspect ratios:
  * Hero: Landscape (wider than tall) - 16:9 ratio recommended
  * Profile: Portrait (taller than wide) - 4:5 ratio recommended
- File size: Keep under 5MB each for fast loading

For replacing placeholders in the code:
1. Open index.html in text editor
2. Find the line with "Add your desk-workspace.jpg"
3. Replace with: <img src="images/desk-workspace.jpg" alt="Workspace">
4. Find the line with "Add your profile.jpg"
5. Replace with: <img src="images/profile.jpg" alt="Profile">

READY? 
------
Once images are added and in the correct folder:
1. Refresh the website
2. Your portfolio will be complete!

Need help? Make sure:
- Files exist in e:\website\images\
- File names match EXACTLY
- Browser is fully refreshed (Ctrl+F5)


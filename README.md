# iOSImageOrientationFixer
A way to fix the orientation of images having right, left, down or mirrored orientation. Developed in Swift, can be used in universal iOS Applications.

This is an extension of UIImage class that changes the orientation of images from left, right, down or mirrored orientations to up orientation, while preserving the aspect ratio of the image.

Steps to use:
1. Clone using: 
    git clone https://github.com/SmitYash/iOSImageOrientationFixer.git
    Or
    download zip file of the project.

2. Add UIImageExtension.swift file to your project manually

3. In your code:
    let fixedImage:UIImage? = originalImage.fixImageOrientation()

4. And you're  done, now you won't see any image of other orientations.


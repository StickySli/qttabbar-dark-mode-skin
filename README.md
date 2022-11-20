# A [QTTabBar](https://github.com/indiff/qttabbar) Dark Mode Skin
No more, no less. Based of Windows 11 dark mode colors. Includes PSD files to change or disable the gradient of the active & hovered tabs.
 
 ![image](https://user-images.githubusercontent.com/77287361/155851685-1eb15abf-fc69-4dcd-bc7f-5954e8e59355.png)
 
A variant with tab separators is included.
 
## How to apply the skin?
It's simple!

1. Download this git repository and place it somewhere safe. If you have copied it to your C:\ folder, great! You can skip to step 3. Otherwise, copy the path of the repository.
2. Edit the `.reg` file and modify the value of the key `"TabImageFile"` with `"<path-to-your-folder>"`. Make sure to escape every backslash character like in the default path.
3. Run the `.reg` file to apply the changes to QTTabBar. You might need to restart  your computer for the changes to take effect. Otherwise, check modify the settings accordingly to the image below

![image](https://user-images.githubusercontent.com/77287361/202919429-0fcfcafd-31ef-461f-b407-3d89e30daf69.png)

For the toolbar background, choose the provided image, otherwise, use the solid color RGB(25,25,25) which has the closest color aproximation to Windows's dark mode. 

## Reported bugs
I have reported a bug in [v1.5.5-beta.8](https://github.com/indiff/qttabbar/releases/tag/v1.5.5-beta.8) which you can see in [issue 285](https://github.com/indiff/qttabbar/issues/285) from indiff's QTTabBar project. The issue is regarding the skin applicator. If you have any troubles with the skin not working, i.e. being invisible, use an earlier version of QTTabBar, specifically **v1.5.5-beta.6** which I have reported it is working.

If you find any bugs, please report them to the original project, not me. If you have any suggestions, feel free to ask them or try to implement them by yourself!

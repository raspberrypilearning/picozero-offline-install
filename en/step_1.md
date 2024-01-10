## Installing picozero offline

If you do not have access to the internet on the computer you are connecting to you Raspberry Pi Pico, or you do not have permissions to install packages with Thonny, you can still use the picozero library.

You can use another internet connected computer to download the file you need and then store the file on a USB flash memory stick.

- Go to the `picozero.py` file in the [picozero GitHub repository](https://raw.githubusercontent.com/RaspberryPiFoundation/picozero/master/picozero/picozero.py?token=GHSAT0AAAAAABRLTKWZCT53CGKBFHMJGE54YSC762A) using a web browser.

- Right click on the picozero page, and choose to **Save page as**.

- Choose a download location, and keep the file name the same - `picozero.py`
### Option 1 - Transfer files using Thonny file manager

- On the computer connect your Raspberry Pi Pico using a microUSB cable.

- Load Thonny from your application menu, then from the **View** menu, choose to see files.

![View menu selected and files has been checked](images/view_files.jpg)

- Use the path to navigate to the directory where you saved the `picozero.py` file.

![file path highlighted in the Files tab in Thonny](images/navigate_downloads.jpg)

- Right click on the `picozero.py` and select **Upload to /** from the menu.

![context menu displayed with upload to / selected](images/upload_files.jpg)

- You should now see a new copy of the `picozero.py` library on the Raspberry Pi Pico.

### Option 2 - Copy and paste the file using Thonny

- Select all the text in the `picozero.py` file by pressing **Ctrl + a** on your keyboard, then copy it by pressing **Ctrl + c**.

- Open Thonny, click in the **untitled** tab and press **Ctrl + v** to paste the contents of `picozero.py` into the file.

- Use **Ctrl + s** to save the file, and when prompted choose to save it to **Raspberry Pi Pico**

![save options show with This computer and Raspberry Pi Pico show](images/save_to.jpg)

- Name the file `picozero.py` and then click on the **OK** button.

![picozero.py typed into the File name field and the OK and Cancel buttons shown](images/save_file.jpg)
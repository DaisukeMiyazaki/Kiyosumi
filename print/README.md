# Canon F3320 printer

Here is the [link](https://cweb.canon.jp/e-support/software/) of the driver. Choose imageRUNNER ADVANCE, iR-ADV C3320F, your OS, complete download and install the driver.

# what you need

1. pre-paid card. Available at the cafe for 1000 yen.
2. Your PC. Supported for Windows and Mac, Linux etc..
3. whatever file that you want to print on your PC

## pairing up with your MacOS PC with the printer
Use a controller of DENON.

1. Go for Print System setting on your PC
2. Make sure you're connected to WNK working lounge 1F wifi. The printer and your PC communicates through the wifi.
2. Add a printer
3. Choose to identify the printer by the Internet. The address is 192.168.12.3
4. Select protocol for LPD(Line Printer Daemon)
5. Select the driver for Canon iR-ADV C3320/3330. When your PC doesn't Select the driver automatically, you need to select the 'Select the software' and search for Canon iR-ADV C3320/3330.
6. Add the printer.

This should add the printer to your PC. Then

1. Open 'option and supply' on your Printer System UI
2. (Check if 'Supply level' tab says something like the info about the printer inks etc. If so, the connection between your PC and the printer is working. If not, something is wrong)
3. Select the 'Option' tab, then set '2弾カセットペディスタイル' as ON. The default should be OFF. 
![alt text]('./static/imgs/casset_pedi_stulle.png')
4. Set the config for OK and close the menu.

Then, try to print any file you want. On Mac for PDF printing for example, this author open 'preview' app to print, as a browser may not allow you to set the configuration of printing.  On printing configuration,

1. Set the pringing sytle as '特別処理' then this should open a modal. Then select 'Secure Print'. on the ジョブの処理方法 pulldown.
![alt text]('./static/imgs/special_process.png')
2. Then enter your document name, user name and passcode. (for example, hoge/hoge/1111)
![alt text]('./static/imgs/secure_print.png')
3. Press print.

Then, check the printer UI. Go 'Secure Print' and then 'マイジョブ状況'. You should see your file displayed on the UI.

1. Make sure that the document name and user name are displayed as set. Select the job and this should ask the passcode. Enter the passcode and select 'セキュアプリント'

Now the printer should be working!
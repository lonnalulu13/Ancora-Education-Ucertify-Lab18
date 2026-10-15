# Ancora-Education-Ucertify-Lab18
# Viewing the Effects of Hostile JavaScript in the Browser

In this lab, you will learn to view the effects of hostile JavaScript in the browser. For this purpose, you will use the Mozilla Firefox browser to defend against malicious code in your Windows Server 2016 virtual machine.

> **Original Lab Source**
>
> This lab was available through:
> 
> [https://ancoraeducation.ucertify.com/app/?func=navigate_items&item_sequence=1]

## Instructions
To view the effects of hostile JavaScript in the browser, here's what you need to do: From the taskbar, click the search icon and type Run to open the Run prompt. In the Run window, type Notepad, and click Ok.

To view the effects of hostile JavaScript in the browser, here's what you need to do: 

1.From the taskbar, click the search icon and type Run to open the Run prompt. 

2.In the Run window, type Notepad, and click Ok. 

3.In the Notepad window, enter the following source code: Send Copy Start of code:
```bash
<html>
<head>
<title>Browser Locker</title>
<script>
<!--

for (i=0;i>=0;i++) {
    alert("Stop me if you can!");
}

//-->
</script>
</head>
<body>
Are you frustrated yet?
</body>
</html>
```


4.In the Notepad window, go to the File tab and click Save As.

5.In the Save As window, select Desktop, and in the File name textbox, type lockup.html, and click Save.

6.Close the lockup-Notepad window

7.From the desktop, open Firefox. 

Note: In the Firefox window, if the Default Browser dialog box appears, click Not now.

8.In the Firefox window, right-click the empty area of the Tab bar and select Menu Bar.

9.On the Menu Bar, click File > Open File. 

10.In the left pane of the Open File window, select Desktop, and then in the right pane, select lockup, and click Open.

11.In the Firefox window, click OK multiple times and you will see that the dialog box does not get closed.

12.Navigate to Start > Task Manager.

13.In the Task Manager window, select Firefox, and click the End task button.

14.Close the Task Manager window.

## Disclaimer

This repository is for **educational and personal learning purposes only**.  

The original lab content belongs to **uCertify / Ancora Education** and remains their copyrighted material.  
This repository is not affiliated with, endorsed by, or sponsored by uCertify or Ancora Education.  

No copyright infringement is intended.  
Use of any tools or techniques mentioned here should only be performed in authorized, legal environments.

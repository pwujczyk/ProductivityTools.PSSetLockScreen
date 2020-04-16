[![GitHub](Images/LogoTitle_green_500px.png)](http://productivitytools.tech/)

 
 <p align="right" width="20px">
    <a href="https://www.powershellgallery.com/packages/ProductivityTools.PSSetLockScreen/">
        <img src="Images/Powershell40px.png" />
    </a>
    <a href="http://www.productivitytools.tech/sql-commands/">
        <img src="Images/ProductivityTools_green_40px_2.png" />
    <a>
         <a href="https://github.com/pwujczyk/ProductivityTools.PSSetLockScreen">
        <img src="Images/Github40px.png" />
    </a>
</p>


# Set-LockScreen


Module sets lock screen to chosen image. It also allows to change Lock screen if setting is managed by your company.

![Lock screen](Images/LockScreen.png)

```powershell
Set-LockScreen -ImagePath D:\OneDrive\InitPC\JustDoThings.png -Verbose
```
![Lock screen](Images/Powershell.png)

To install module use 

```powershell
Install-Module -Name ProductivityTools.PSSetLockScreen
```

Module depends on **ProductivityTools.PSTestIfAdmin**, which is installed automatically after invoking above command. 
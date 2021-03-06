# Creativity is your weapon

- [PowerShellGallery.com](https://www.powershellgallery.com)
- [systanddeploy.com](http://www.systanddeploy.com)

<br >
<br >

## Collections of scripts
- [PowerShell-Suite](https://github.com/FuzzySecurity/PowerShell-Suite) - tools and resources.
- [Rvrsh3ll's Misc-PowerShell-Scripts](https://github.com/rvrsh3ll/Misc-Powershell-Scripts) - Random Tools.

## Network commands
````
Test-NetConnection -Computername $target -Port 5985
````

### Other resources that might come in handy
- [Nimx](https://github.com/yglukhov/nimx) - Cross-platform GUI framework in Nim.

## TimeTrack-Specific-Software-Openings.ps1
Primitive script used to test how long time a specific program uses before it's opened. VLC and Windows Media Player is used as examples. Modern servers will have a close average time while old and unstable servers will have timing that varys more. Having stable and precises time is critical within streaming environments, where it's crucial a program opens without a delay.

Picture that shows normal timing on modern hardware:  
<a href="https://imgbb.com/"><img src="https://i.ibb.co/yVwZmvD/Skjermbilde-2020-07-03-kl-17-07-23.png" alt="Skjermbilde-2020-07-03-kl-17-07-23" border="0"></a>

Timing that shows abnormal timing on slow and old hardware:  
<a href="https://imgbb.com/"><img src="https://i.ibb.co/PW4CQkC/Skjermbilde-2020-07-03-kl-17-09-25.png" alt="Skjermbilde-2020-07-03-kl-17-09-25" border="0"></a>

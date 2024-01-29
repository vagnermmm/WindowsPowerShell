Get-WmiObject -Class Win32_Product | Select-Object -Property Name, version | findstr Adobe

Invoke-Command -ComputerName Servidor1,Servidor2 {date; hostname; Get-WmiObject -Class Win32_Product | Select-Object -Property Name, version | findstr Adobe};

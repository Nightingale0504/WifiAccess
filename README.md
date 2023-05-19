# Introdution
WifiAccess is a Wi-Fi access QR code generator.
It can generate Wi-Fi access QR code according to the SSID, password, width and width you entered.
# Operating principle
It use PowerShell install and run a module to generate Wi-Fi access QR code.
```powershell
Install-Module -Name QRCodeGenerator
New-QRCodeWifiAccess -SSID YOURSSID -Password YOURPASSWORD -Width YOURWIDTH -OutPath YOUROUTPATH
```
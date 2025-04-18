```
nmcli device wifi list
nmcli device wifi connect "SSID" password "PASSWORD"
```

```
Get-AppxPackage *WindowsStore* | Remove-AppxPackage
Get-AppxPackage *MicrosoftStickyNotes* | Remove-AppxPackage

# App principal de Xbox
Get-AppxPackage *XboxApp* | Remove-AppxPackage
# Xbox Game Overlay
Get-AppxPackage *XboxGameOverlay* | Remove-AppxPackage
# Xbox Gaming Services (esto a veces no se va del todo así que cuidado)
Get-AppxPackage *GamingServices* | Remove-AppxPackage
# Xbox TCUI (Xbox identity provider)
Get-AppxPackage *Xbox.TCUI* | Remove-AppxPackage
# Xbox Game Speech Window
Get-AppxPackage *XboxSpeechToTextOverlay* | Remove-AppxPackage
# Xbox Identity Provider
Get-AppxPackage *XboxIdentityProvider* | Remove-AppxPackage

```

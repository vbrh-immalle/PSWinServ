Overzicht van netwerkkaarten:

  Get-NetAdapter
  
Het IP-adres `192.168.4.1` toekennen aan interface met index `10` en `24` subnet-masker-bits:

  New-NetIPAddress -IPAddress 192.168.4.1 -InterfaceIndex 10 -PrefixLength 24
  
De IP-configuratie weer verwijderen:

  Remove-NetIPAddress -IPAddress 192.168.4.1
  

# sms-sailfish
Command-line utility to send SMS messages via ssh commands to a SailfishOS phone.


## Draft 

Send SMS message: 

```
dbus-send --system --print-reply --dest=org.ofono /ril_0 org.ofono.MessageManager.SendMessage string:"+33XXXXXXXXX" string:"Hello World"
```

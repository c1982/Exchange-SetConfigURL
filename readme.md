Exchange URL'lerini d�zenlemenizi sa�lar.

Standart Exchange kurulumu sonras�nda mail al��veri�inin sa�l�l� �al��mas� i�in gereklidir.

```sh

.�RNEK
.\SetExchangeURLs.ps1 -Server MB1 -InternalURL mail.maestropanel.com -ExternalURL mail.maestropanel.com


.�RNEK
.\SetExchangeURLs.ps1 -Server MB1,MB2 -InternalURL mail.maestropanel.com -ExternalURL mail.maestropanel.com


.�RNEK DAG
.\SetExchangeURLs.ps1 -Server MB1,MB2 -InternalURL mail.maestropanel.com -ExternalURL mail.maestropanel.com
```
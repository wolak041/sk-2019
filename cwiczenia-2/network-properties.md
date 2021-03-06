Ustawianie parametrów sieci
---------------------------

![alt text][network]

[network]: ./network.png "Logo Title Text 2"

1. na 1 z komputerów zainstaluj oprogramowanie ``http-chat`` dostępne pod adresem ``https://github.com/jkanclerz/http-chat``

Wejściowe parametry sieci
-------------------------
| Parametr | wartość | komentarz(opcionalny) |
| ------------- |:-------------:| -----:|
|   PC 1 | lubuntu 18.10 | |
| IP - address  | 10.0.2.4 | |
| MASKA  | 255.255.255.0 | |
|   |  | |
| PC 2  | lubuntu 18.10 | |
| IP - address  | 10.0.2.15 | |
| MASKA  | 255.255.255.0 | |

Weryfikacja połączenia

Polecenie
```
ping 10.0.2.15
```


Wejściowe parametry sieci
-------------------------
| Parametr | wartość | komentarz(opcionalny) |
| ------------- |:-------------:| -----:|
|   PC 1 |  
| IP - address  | 192.168.10.10 | |
| MASKA  | 255.255.255.0 | |
|   |  | |
| PC 2  |  | |
| IP - address  | 172.16.100.100 | |
| MASKA  | 255.255.0.0 | |


Warto wiedzieć
--------------

-------------------------
| Parametr | wartość | komentarz(opcionalny) |
| ------------- |:-------------:| -----:|
| Lokalizacja pliku z konfiguracją sieci| /etc/network/interfaces(Ubuntu/Debian)  /etc/sysconfig/network(Red Hat/Fedora/CentOS) | |
| UP -> Wyłączenie interfejsu sieciowego| ifup | |
| DOWN -> Włączenie interfejsu sieciowego| ifdown | |
| Sprawdzenie obecnych parametrów | nmcli | |
| lista wszystkich interfejsów | ip a | |
| Które interfejsy jakie porty słuchają | netstat --listen | |


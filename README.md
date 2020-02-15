### Uruchomienie dockerów
```bash
$ docker-compose up
```

### zokończenie pracy dockerów
```bash
$ docker-compose down
```

### Wejście do maszyny wirtualnej
 (musisz być w katalogu projektu)
```bash
$ docker-compose exec sda-web /bin/bash
```

### Uruchomienie testu
```bash
$ docker-compose exec sda-web ./test.sh
```

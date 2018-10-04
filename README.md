# LSDP - Lista 1

## Vagrant, bash introduction

0. Przygotowanie:
	- [Vagrant](https://www.vagrantup.com/)
	- zrób ```clone``` projektu,
	- zobacz co jest w pliku Vagrantfile, 
	- [dostosuj ścieżki](https://stackoverflow.com/a/27709845/4723795)
	- zainstaluj VBox i dodaj zmienną [VBOX_INSTALL_PATH](https://stackoverflow.com/a/32702764/4723795)
	- wyłącz [Hyper-V](https://stackoverflow.com/a/42889976/4723795)
	- umieszczaj pliki w katalogu projekt (będzie on zamontowany jako /project)
	- ```vagrant up```
	- ```vagrant ssh```
	- można korzystać z komendy sudo (np. żeby coś zainstalować)

1. Napisz skrypt, który sprawdzi bieżącą datę i godzinę i jeśli wypada ona w czasie zajęć laboratoryjnych wyświetli napis "Witaj na zajęciach"

2. Należy dodać plik z zad 1. do plików startowych shella tak aby przy logowaniu był on uruchamiany (utwórz odpowiendie dowiązanie symboliczne tak żeby wszystkie pliki z którymi pracujesz znajdowały się w katalogu project)

3. Utwórz plik z min 6 tekstami powitalnymi i zapisz je do pliku (każde powitanie w osobnej linii). Napisz skrypt, który będzie wyświetlał losowe powitanie z pliku (zrób 2 wersje, jedna z wykorzystaniem: head, tail, bc, expr, druga: shuf)

4. Utwórz plik z nazwami katalogów. Napisz skrypt, który będzie przyjmował w wywołaniu linii poleceń nazwę tego pliku oraz wartość liczbową i tworzył katalogi o nazwach z pliku oraz dla każdego katalogu podkatalogi w liczbie określonej przez wartość liczbową o nazwie losowej.

5. Korzystając z mechanizmu opisanego [tutaj](http://tldp.org/LDP/abs/html/here-docs.html) napisz skrypt, który będzie przyjmował wartość liczbową i adre email w linii poleceń a następnie [wysyłał wiadomosc emaila](https://www.youtube.com/watch?v=wFXLzr86MQ4) (Vagrant pozwala wysyłać wiadomości tylko z konta root) pod wskazany adres wraz dowolnym komentarzem tekstowym podaną wartością i wszystkimi wartościami zmiennych środowiskowych.

6. Wykonaj powyższe zadania na swoim koncie w klastrze WCSS

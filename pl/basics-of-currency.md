# Podstawy waluty

W pluginie ekonomicznej wirtualna waluta odgrywa kluczową rolę. Użytkownicy mogą zarabiać walutę, wykonując czynności takie jak
praca, czatowanie i uczestnictwo w kanałach głosowych. Ta sekcja zawiera przegląd systemu walutowego i
jego funkcjonalności.

## Komenda /balance

Komenda `/balance [użytkownik]` pozwala na sprawdzenie własnego lub czyjegoś konta bankowego i salda portfela. Jeśli
użytkownik wspomni albo ID jest podany jako argument, polecenie wyświetli saldo konta bankowego i portfela
tego konkretnego użytkownika, w przeciwnym razie wyświetli saldo użytkownika, który wywołał polecenie.

![](../assets/v6.png)

Waluta jest przechowywana w dwóch różnych miejscach: portfelu i banku.

## Pieniądze z portfela – używane do płatności, ale narażone na kradzież

Portfel jest głównym miejscem przechowywania waluty i może być wykorzystywany do płatności.

Komenda `/rob <użytkownik>` pozwala na próbę kradzieży pieniędzy z portfela innego użytkownika. Wspominając lub podając
ID docelowego użytkownika, można okraść innych z gotówki przechowywanej w portfelu. Istnieje jednak szansa na niepowodzenie
[**twoja wartość netto / (ich gotówka + twoja wartość netto)**] z minimalną i maksymalną wartością 20% i 80%. Skradziona kwota jest
obliczana jako: prawdopodobieństwo sukcesu razy ich gotówka.

## Przechowywanie w banku – chronione miejsce do przechowywania środków

Bank zapewnia bezpieczne miejsce do przechowywania środków. Pieniądze przechowywane w banku nie mogą być bezpośrednio używane w poleceniach i muszą być
wypłacone do portfela za pomocą komendy /withdraw.

Komenda `/deposit <ilość>` umożliwia zdeponowanie określonej kwoty pieniędzy z portfela na konto bankowe.
konto bankowe. Zapewnia to bezpieczny sposób przechowywania środków i chroni je przed potencjalnymi stratami w wyniku innych komend.
Możesz zdecydować, ile pieniędzy chcesz wpłacić, określając żądaną kwotę jako argument.

Komenda `/withdraw <ilość>` umożliwia wypłacenie określonej kwoty pieniędzy z konta bankowego do
portfela. Umożliwia to dostęp do środków na potrzeby różnych komend i transakcji. Możesz zdecydować, ile pieniędzy
chcesz wypłacić, podając żądaną kwotę jako argument.

## /pay – Transfer waluty

![](../assets/v18.gif)

Komenda `/pay <użytkownik> <pieniądze>` umożliwia przesyłanie wirtualnych pieniędzy do innego użytkownika na serwerze. Poprzez
wzmiankę lub ID użytkownika będącego odbiorcą i określając żądaną kwotę, można zainicjować transakcję
i wysłać wirtualne pieniądze komuś innemu.

## /topmoney – Topka pieniędzy

Komenda `/topmoney` zawiera listę 10 najlepszych użytkowników z największą ilością wirtualnych pieniędzy na koncie bankowym.
Ta komenda zapewnia przegląd najbogatszych członków społeczności i może służyć jako tablica wyników dla użytkowników do
porównywać swoje postępy.

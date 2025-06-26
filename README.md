# Raport o postępach w pentestingu  
imię igor blask

Jestem  i od prawie roku intensywnie rozwijam się w obszarze cyberbezpieczeństwa, ze szczególnym naciskiem na pentesting (testy penetracyjne). Choć dopiero zaczynam swoją ścieżkę zawodową, traktuję naukę niezwykle poważnie, jestem zdyscyplinowany i szybko przyswajam nowe umiejętności.  

## 🔍 Dotychczasowe osiągnięcia i umiejętności  
1. **Rekonesans sieciowy**  
   - `ping -c 1 <IP>` – sprawdzanie, czy host odpowiada.  
   - `nmap -T3 -sV <IP>` – skanowanie portów i wykrywanie wersji usług.  
   _Oznacza to, że potrafię szybko namierzyć aktywne maszyny i usługi oraz ocenić profil potencjalnych ataków._  

2. **Łączenie się z usługami**  
   - `telnet <IP> 23` – badanie niezaszyfrowanych protokołów i ryzyka podsłuchiwania.  
   - Świadomość zagrożeń związanych z Telnetem (sniffing, brak szyfrowania).  
   _Nauczyłem się rozpoznawać, które usługi są podatne na przechwycenie danych._  

3. **Eksploracja systemu po uzyskaniu dostępu**  
   - `whoami`, `id` – weryfikacja tożsamości i uprawnień użytkownika.  
   - `uname -a` – informacje o systemie i jądrze.  
   - `netstat -tuln`, `ps aux` – lista otwartych portów i uruchomionych procesów.  
   - `cat /etc/shadow` – odczyt pliku z hashami (identyfikacja kont z gwiazdką i prawdziwych hashy).  
   _Dzięki temu rozumiem, jak rozejrzeć się w nowym środowisku i szukać punktów wejścia do eskalacji._  

4. **Analiza logów**  
   - `cat /var/log/auth.log` + `grep "sudo"`, `grep "Failed password"`, `grep "Accepted password"`  
   _Umiem wyciągnąć z logów informacje o próbach logowania i użyciu sudo, co jest kluczowe dla raportowania._  

5. **Poszukiwanie możliwości eskalacji uprawnień**  
   - `find / -perm -4000 2>/dev/null` – wyszukiwanie plików z bitem SUID.  
   _Potrafię wskazać pliki, które mogą pozwolić na podniesienie uprawnień do root._  

## 🚀 Co to dla mnie oznacza  
- **Samodzielność** w przygotowaniu środowiska testowego (HTB, własne VM).  
- **Zrozumienie pełnego workflow pentestera**: od rekonesansu przez eksploatację do analizy logów.  
- **Gotowość do pisania profesjonalnych raportów** i dzielenia się wynikami na GitHubie.  

## 🎯 Co jeszcze mogę zrobić  
- Przećwiczyć **łamanie hashy** (`john` / `hashcat`) na wynikach z `/etc/shadow`.  
- Zajmować się **eksploatacją SUID** (np. poprzez niebezpieczne wersje `find`, `vim`, `bash`).  
- Poznać **kontrolę wersji exploitów** (Metasploit, własne skrypty).  
- Rozwinąć umiejętności w obszarze **web pentestingu** (Burp Suite, SQLi, XSS).  

## 🙏 Podsumowanie i cele  
Chciałbym zdobyć **praktyki w małej firmie**, gdzie mógłbym realnie uczestniczyć w projektach pentestowych. Będę bardzo wdzięczny za każde zaproszenie do współpracy i docenienie mojej pasji oraz szybkiego tempa nauki. Choć jeszcze nie jestem ekspertem, moja dyscyplina, systematyczność i zapał pozwalają mi skutecznie rozwijać się w branży.

---

**Igor**
 przyszły pentester w cyberbezpieczeństwie
kontakt: pikola93846@gmail.com
gihub:https://github.com/animus1230

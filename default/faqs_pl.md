### Jak korzystać z systemu Muscat  

1. **Gdzie mogę znaleźć tutoriale na temat programu Muscat?  
&nbsp;**    
Linki do wszystkich tutoriali znajdują się na stronie programu Muscat Centralnego Biura RISM: [http://www.rism.info/en/community/muscat.html  
  
](http://www.rism.info/en/community/muscat.html)
2. **Jak mogę skontaktować się z innymi użytkownikami Muscat?**  
Wszelkie błędy, pytania, komentarze i sugestie można zgłaszać w dowolnym momencie na adres muscat@rism.info   
  
**[RISM Muscat](https://groups.google.com/forum/#!forum/rism-muscat)**, grupa Google, jest oficjalną grupą dyskusyjną Muscat, do której musi dołączyć każdy użytkownik Muscat. Oficjalne komunikaty od Central Office i programistów Muscat rozpowszechnia się wyłącznie za pośrednictwem tej grupy. Ponadto, wszystkich użytkowników Muscat zachęca się do zadawania pytań lub podnoszenia tematów do dyskusji.  
  
Nie ma potrzeby posiadania konta Google. Zaproszenie do przyłączenia się do grupy zostanie wysłane po otrzymaniu przez Państwa informacji o koncie Muscat.  
  
Istnieje również kanał dyskusyjny na Slack:   
[https://rismcommunity.slack.com/](https://rismcommunity.slack.com/)  
  
3. **Czy cała literatura cytowana w Muscat znajduje się w Biurze Centralnym ?**  
Nie, w naszym biurze znajduje się tylko literatura oznaczona jako&nbsp;„HB”&nbsp;lub&nbsp;„Handbibliothek”&nbsp;lub&nbsp;„RISM-ZR”. Materiały te mają służyć wszystkim współpracownikom RISM, więc jeśli mamy publikację, która może być pomocna, daj nam znać, a my postaramy się zdobyć to, czego potrzebujesz. Nawet jeśli poszukujesz publikacji, której nie mamy w biurze, jest szansa, że znamy kogoś, kto ją ma.  
  
4. **Co robić, gdy zapomnę hasła lub chcę je zmienić ?**  
  
Hasłami zarządza Biuro Centralne. Skontaktuj się z nami, jeśli zgubisz hasło. Sam nie możesz zmienić swojego hasła.  
  
5. **Czy mogę pokazać system Muscat moim kolegom? Czy mogę zademonstrować system Muskat na konferencjach lub warsztatach?**  
Tak, jak najbardziej! Dokładnie w tym celu udostępniamy wersję szkoleniową Muscat pod adresem [https://muscat-training.rism.info](https://muscat-training.rism.info/).   
  
Wszyscy użytkownicy Muscat mogą się tam zalogować za pomocą swoich danych osobowych. Istnieje również 99 kont szkoleniowych („training01@rism.info”&nbsp;do „training99@rism.info”) dostępnych dla użytkowników indywidualnych. Można korzystać z każdego z tych kont szkoleniowych. Prosimy o kontakt z Centralnym Biurem RISM (Jennifer Ward, jennifer.ward@rism.info) w celu uzyskania aktualnego hasła.  
  
W wersji szkoleniowej można wszystko dodawać, edytować lub usuwać. Biuro Centralne synchronizuje ją raz w tygodniu (w niedzielę) z aktualnymi danymi Muscat. Oznacza to, że będą już wtedy dostępne nowe rekordy, ale oznacza to także, że rekordy utworzone w wersji treningowej zostaną usunięte.   
  
6. **Co to znaczy, że w historii modyfikacji, „[system]”&nbsp;został wymieniony jako autor?**  
Możesz zobaczyć przykład edycji systemowej, jeśli jedno z indeksowanych pól związanych z Twoim rekordem uległo zmianie. Zmiana w rekordzie autorytatywnym zarejestruje się również jako zmiana w Twoim rekordzie.  
  
7. **Czy mogę tworzyć rekordy na podstawie opisów z drukowanych katalogów?**  
Tak! Czasami, z różnych powodów, nie jest możliwy dostęp do źródła i dostępny jest tylko opis w drukowanym katalogu lub katalogu utworów. Możesz użyć takich opisów jako podstawy do stworzenia swojego rekordu. W tym celu należy załączyć **Uwagę ogólną (500)**, np. „Rekord oparty na opisie w YouV”&nbsp;i link do katalogu w polu **Odniesienie bibliograficzne (691)**.

&nbsp;

### Wymagania techniczne systemu Muscat  

**1. Jakie są wymagania techniczne systemu Muscat ?**  

- Muscat jest niezależny od platformy i działa zarówno na komputerach Mac, jak i PC.
- Dostęp odbywa się poprzez adres URL. W związku z tym do korzystania z dostępu niezbędne jest połączenie z Internetem.   
- Muscat najlepiej sprawdza się na ekranach o wymiarach co najmniej 1366 x 768 pikseli.
- Muscat jest dostosowany do wyszukiwarki Firefox i Chrome. Nie należy używać Internet Explorera !   

**2.&nbsp;**  **Jakie są niektóre techniczne aspekty Systemu Muscat ?**

- Muscat działa na otwartym kodzie źródłowym. Kod źródłowy jest dostępny pod adresem repozytorium [GitHub](https://github.com/rism-ch/muscat).
- Muscat jest aplikacją Ruby on Rails.
- Do renderowania incipitów muzycznych za pośrednictwem MEI system używa [Verovio](http://www.verovio.org/pae-examples.xhtml)&nbsp;   
- Jako wyszukiwarka służy Solr.   
- Muscat posiada [an SRU service](https://github.com/rism-ch/muscat/wiki/SRU) oraz [SRU downloader](https://github.com/rism-international/sru-downloader) do odzyskiwania rekordów MARCXML.
Więcej informacji na temat programowania systemu Muscat można znaleźć na stronie [RISM Switzerland's website](http://rism-ch.org/infrastructure/muscat.html?locale=en).   
  

**3. Jakie są niektóre techniczne aspekty wyszukiwania incipitów ?**

- Oparto je na silniku wyszukiwania [Themefinder](http://www.themefinder.org/) opracowanym przez Uniwersytet Stanford.  
- Lewaruje leżący u podłoża system indeksowania (Soir), używany do wszystkich zapytań w Muscat, który dostosowano tak, aby umożliwić analizę notacji PAE używanej w edytorze. Proces indeksowania jest całkowicie przejrzysty dla użytkowników i katalogerów. Wstawiania zakodowanej notacji wymaga się jedynie w polu 031.  

**4. Jakie są niektóre cechy systemu Muscat?**

- **Wersjonowanie** : Katalogerzy mogą przeglądać zmiany wprowadzone do rekordów.  
- **VIAF** : Nazwy osobowe można importować poprzez link do [Virtual International Authority File (VIAF)](https://viaf.org/).&nbsp;

**5. Jakie są plany dalszego rozwoju Muscat?**

- Zintegrowanie obrazów przy wykorzystaniu manifestu&nbsp;[IIIF](http://iiif.io/)   
- Zbieranie opinii od użytkowników  
- Dodanie dodatkowych tłumaczeń interfejsu i wytycznych  
- Wsadowy import/eksport rekordów z i do programu Muscat
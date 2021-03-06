---
layout: page
status: publish
published: true
title: Pomoc Greenshot
author:
  display_name: greenshot
  login: admin
  email: greenshot-developers@lists.sourceforge.net
  url: http://getgreenshot.org/
author_login: admin
author_email: greenshot-developers@lists.sourceforge.net
author_url: http://getgreenshot.org/
wordpress_id: 393
wordpress_url: http://getgreenshot.org/
date: !binary |-
  MjAxMi0wNC0wOSAwODozODo0MyArMDIwMA==
date_gmt: !binary |-
  MjAxMi0wNC0wOSAwNjozODo0MyArMDIwMA==
categories: []
tags: []
comments: []
---
<p><small>Wersja 0.8<!-- - English translation of help content by YOUR_NAME--></small></p>
<h2>Zawartość</h2>
<ol>
<li><a href="#screenshot">Tworzenie zrzutu ekranu</a></li>
<ol>
<li><a href="#capture-region">Przechwytywanie obszaru</a></li>
<li><a href="#capture-last-region">Przechwytywanie ostatniego obszaru</a></li>
<li><a href="#capture-window">Przechwytywanie okna</a></li>
<li><a href="#capture-fullscreen">Przechwytywanie pełnego ekranu</a></li>
</ol>
<li><a href="#editor">Korzystanie z edytora graficznego</a></li>
<ol>
<li><a href="#editor-shapes">Rysowanie kształtów</a></li>
<li><a href="#editor-text">Dodawanie tekstu</a></li>
<li><a href="#editor-highlight">Wyróżnianie miejsc</a></li>
<li><a href="#editor-obfuscate">Maskowanie miejsc</a></li>
<li><a href="#editor-crop">Kadrowanie zrzutu ekranu</a></li>
<li><a href="#editor-reuse-elements">Wykorzystanie opracowanych elementów</a></li>
<li><a href="#editor-export">Eksportowanie zrzutu ekranu</a></li>
</ol>
<li><a href="#settings">Okno ustawień</a></li>
<ol>
<li><a href="#settings-general">Ustawienia ogólne</a></li>
<li><a href="#settings-output">Ustawienia wyjściowe</a></li>
<li><a href="#settings-printer">Ustawienia drukarki</a></li>
</ol>
<li><a href="#help">Chcesz pomóc?</a></li>
<ol>
<li><a href="#help-donate">Rozważ darowiznę</a></li>
<li><a href="#help-spread">Opowiadaj o nas</a></li>
<li><a href="#help-translate">Dodaj tłumaczenie</a></li>
</ol>
</ol>
<p>	<a name="screenshot"></a></p>
<h2>Tworzenie zrzutu ekranu</h2>
<p>
		Można utworzyć zrzut ekranu albo za pomocą klawisza <kbd>Print</kbd> na klawiaturze<br />
		lub klikając prawym przyciskiem myszy ikonę Greenshot w zasobniku systemowym.<br><br />
		Istnieje kilka opcji tworzenia zrzutu ekranu:
	</p>
<p>	<a name="capture-region"></a></p>
<h3>Przechwytywanie obszaru<kbd>Print</kbd></h3>
<p>
		Tryb przechwytywania obszaru pozwala przechwycić  tylko wybraną część ekranu.<br><br />
		Po uruchomieniu trybu obszaru pojawi się celownik, zamiast wskaźnika myszy. Kliknij<br />
		i przytrzymaj lewy przycisk myszy, w jednym z rogów obszaru z którego chcesz wykonać<br />
		zrzut ekranu. Wciąż trzymając wciśnięty przycisk myszy, przeciągnij myszą aby zdefiniować<br />
		prostokąt obszaru do przechwycenia. Kiedy zielony prostokąt obejmie obszar, który chcesz<br />
		by był przechwycony w zrzutcie ekranu, po prostu zwolnij przycisk myszy.
	</p>
<p class="hint">
		Możesz użyć klawisza <kbd>Space</kbd> , aby przełączyć między trybem obszaru<br />
		a trybem <a href="#capture-window">okno</a>.
	</p>
<p class="hint">
		Jeśli chcesz zrobić dokładny zrzut obszaru, może łatwiej będzie wybrać początkową<br />
		powierzchnię zrzutu ekranu trochę większą, i potem <a href="#editor-crop">przyciąć</a><br />
		zrzut ekranu za pomocą edytora obrazu Greenshot.
	</p>
<p>	<a name="capture-last-region"></a></p>
<h3>Przechwytywanie ostatniego obszaru <kbd>Shift</kbd> + <kbd>Print</kbd></h3>
<p>
		Jeśli nie przechwyciłeś <a href="#capture-region">obszaru</a>, lub <a href="#capture-window">okna</a><br />
		wcześniej, możesz przechwycić ten sam obszar ponownie, używając tej opcji.
	</p>
<p>	<a name="capture-window"></a></p>
<h3>Przechwytywanie okna <kbd>Alt</kbd> + <kbd>Print</kbd></h3>
<p>
		Tworzy zrzut ekranu z okna, które jest aktualnie aktywne.
	</p>
<p class="hint">
		<a href="#settings">Okno ustawień</a> oferuje możliwość nie przejmowania<br />
		aktywnego okna od razu, ale pozwala wybrać jedno interaktywnie.<br />
		Jeśli ta opcja jest zaznaczona, użytkownik może wybrać okno,  klikając go<br />
		 (jak w <a href="#capture-region">trybie obszaru</a>, Greenshot wyróżni obszar<br />
		który będzie przechwytywany).<br>Jeśli chcesz przechwycić okno wewnętrzne (np.<br />
		w przeglądarce podglądu (bez paska narzędzi itp.) lub pojedynczą klatkę strony<br />
		internetowej używając ramki), ustaw wskaźnik kursora myszy w oknie i naciśnij klawisz<br />
		<kbd>PgDown</kbd>. Teraz możesz wybrać wewnętrzne okno do przechwycenia.
	</p>
<p>	<a name="capture-fullscreen"></a></p>
<h3>Przechwytywanie pełnego ekranu <kbd>Control</kbd> + <kbd>Print</kbd></h3>
<p>
		Tworzy kompletny zrzut całego ekranu.
	</p>
<p>	<a name="editor"></a></p>
<h2>Korzystanie z edytora graficznego</h2>
<p>
		Greenshot jest wyposażony w łatwy w użyciu edytor zdjęć, zapewniając wygodne<br />
		narzędzia retuszu do dodawania adnotacji lub kształtów na ekranie. Umożliwia nawet<br />
		podkreślenie lub ukrycie części ekranu.
	</p>
<p class="hint">
		Edytor obrazów Greenshot'a nie musi być używany tylko do zrzutów ekranu. Można również<br />
		otworzyć do edycji obrazy z pliku lub ze schowka. Kliknij prawym przyciskiem myszy<br />
		ikonę Greenshot w zasobniku systemowym i wybierz odpowiednio, <em>Otwórz obraz z pliku</em><br />
		lub <em>Otwórz obraz ze schowka</em>.
	</p>
<p class="hint">
		Domyślnie, edytor zdjęć zostanie otwarty, gdy zrzutu ekranu zostanie<br />
		przechwycony. Jeśli nie chcesz korzystać z edytora obrazów, możesz wyłączyć tę<br />
		opcję, w <a href="#settings">oknie ustawień</a>.
	</p>
<p>	<a name="editor-shapes"></a></p>
<h3>Rysowanie kształtów</h3>
<p>
		Wybierz jedno z narzędzi do rysowania kształtów, z paska narzędzi po lewej stronie<br />
		edytora zdjęć, lub z menu <em>Objekt</em>. Dla Twojej wygody, istnieje również<br />
		przypisany klawisz dla każdego narzędzia.<br><br />
		Dostępne kształty: prostokąt <kbd>R</kbd>, elipsa <kbd>E</kbd>, linia <kbd>L</kbd><br />
		i strzałki <kbd>A</kbd>.<br><br />
		Kliknij prawy przycisk, przytrzymaj naciśnięty przycisk myszy i przeciągnij,<br />
		aby określić położenie i rozmiar kształtu. Zwolnij przycisk myszy, gdy skończysz.
	</p>
<p>
		Można przenieść lub zmienić rozmiar istniejącego kształtu po wybraniu narzędzia<br />
		<kbd>ESC</kbd> z paska narzędzi.<br>Dla każdego typu elementu jest określony zestaw<br />
		dostępnych opcji do zmiany wyglądu elementu (np. grubość linii, kolor linii, kolor<br />
		wypełnienia). Możesz zmienić opcje dla istniejącego elementu, po jego wybraniu.<br />
		Ale także dla następnego elementu jaki należy rysować, po wybraniu narzędzia do rysowania.
	</p>
<p class="hint">
		Możesz wybrać wiele elementów do edycji na raz. Aby zaznaczyć kilka elementów,<br />
		przytrzymaj klawisz <kbd>Shift</kbd> podczas zaznaczania wybranych elementów.
	</p>
<p>	<a name="editor-text"></a></p>
<h3>Dodawanie tekstu</h3>
<p>
		Korzystanie z narzędzia tekstowego <kbd>T</kbd>  jest podobne do korzystania z<br />
		narzędzi<a href="#editor-shapes">kształtu</a>. Wystarczy narysować okienko tekstowe,<br />
		do żądanego rozmiaru, a następnie wpisać tekst.<br><br />
		Kliknij dwukrotnie istniejący element tekstowy, aby edytować tekst.
	</p>
<p>	<a name="editor-highlight"></a></p>
<h3>Wyróżnianie miejsc</h3>
<p>
		Po wybraniu narzędzia wyróżnienia <kbd>H</kbd>, możemy zdefiniować obszar przeznaczony do<br />
		wyróżnienia, dokładnie w takim kształcie jaki chcesz <a href="#editor-shapes">narysować</a>.<br><br />
		Istnieje kilka opcji wyróżniania, które można wybrać poprzez kliknięcie prawym przyciskiem<br />
		myszy na pasku narzędzi u góry:
	</p>
<ul>
<li><em>Wyróżnianie tekstu</em>: wyróżnia obszar przez zastosowanie jasnych kolorów dla tła, podobnie<br />
			 jak biurowy zakreślacz tekstu</li>
<li><em>Wyróżnij obszar</em>: zamglenie <a href="#hint-blur">*</a> , i wszystko przyciemnieje, poza zaznaczonym obszarem</li>
<li><em>Skala szarości</em>: wszystko, poza zaznaczonym obszarem, zostanie włączone do skali szarości</li>
<li><em>Powiększenie</em>: zaznaczony obszar zostanie wyświetlony w powiększeniu</li>
</ul>
<p>	<a name="editor-obfuscate"></a></p>
<h3>Maskowanie miejsc</h3>
<p>
		Maskowanie części ekranu jest dobrym pomysłem, jeśli zrzut zawiera dane, które nie są<br />
		przeznaczone dla innych osób, np. dane konta bankowego, nazwy, hasła lub twarze na zdjęciach.<br><br />
		Użyj narzędzi maskowania <kbd>O</kbd> dokładnie tak, jak używa się narzędzi<br />
		<a href="#editor-highlight">wyróżniania</a>.<br><br />
		Dostępne opcje dla maskowania to:
	</p>
<ul>
<li><em>Rozmiar piksela</em>: zwiększa rozmiar w pikselach, zaznaczonego obszaru</li>
<li><em>Zamglenie</em><a href="#hint-blur">*</a>: rozmywa zaznaczony obszar</li>
</ul>
<p>	<a name="hint-blur"></a></p>
<p class="hint">
		* W zależności od wydajności komputera, stosowanie efektu zamglenia może spowolnić<br />
		edytor obrazu Greenshota Jeśli uważasz, że edytor zdjęć reaguje powoli, jak tylko<br />
		zastosujesz zamglenie, spróbuj zmniejszyć wartość <em>Jakość podglądu</em> na pasku narzędzi,<br />
		lub zmniejszyć wartość <em>Zakres zamglenia</em>.<br><br />
		Jeśli wydajność zamglenia jest jeszcze zbyt niekorzystna do pracy z nim, możesz preferować<br />
		korzystanie z efektu <em>Rozmiar piksela</em> , zamiast efektu <em>Zamglenia</em>.
	</p>
<p>	<a name="editor-crop"></a></p>
<h3>Kadrowanie zrzutu ekranu</h3>
<p>
		Jeśli potrzebujesz, by tylko część zrzutu ekranu została zarejestrowana, za pomocą narzędzia<br />
		przycinania <kbd>C</kbd> , możesz przyciąć go do żądanego obszaru. <br><br />
		Po wybraniu narzędzia przycinania, narysuj prostokąt na obszarze zrzutu ekranu, który chcesz<br />
		zachować. Można zmienić rozmiar zaznaczonego obszaru, jak każdy inny element.<br><br />
		Kiedy jesteś zadowolony z wyboru, użyj przycisku potwierdzenia na pasku narzędzi, lub naciśnij<br />
		klawisz <kbd>Enter</kbd> .  Możesz anulować kadrowanie, klikając przycisk Anuluj, lub klawisz<br />
		<kbd>ESC</kbd>, na klawiaturze
	</p>
<p>	<a name="editor-reuse-elements"></a></p>
<h3>Wykorzystanie opracowanych elementów</h3>
<p>
		Jeżeli zechcesz użyć tych samych, lub podobnych elementów, do większości zrzutów ekranu<br />
		(np. pole tekstowe zawierające typ i wersję przeglądarki, lub maskował te same<br />
		elementy na kilka zrzutach ekranu) można ponownie użyć elementów.<br><br />
		Wybierz <em>Zapisz obiekty do pliku</em> , w menu <em>Objekt</em> , aby zapisać bieżący<br />
		zbiór elementów do ponownego wykorzystania w przyszłości. Użycie narzędzia<br />
		<em>Załaduj obiekty z pliku</em> , zastosuje te same elementy do innego ekranu.
	</p>
<p>	<a name="editor-export"></a></p>
<h3>Eksportowanie zrzutu ekranu</h3>
<p>
		Po zakończeniu edycji ekranu, można wyeksportować wynik w różnych celach,<br />
		w zależności od potrzeb. Możesz uzyskać dostęp do wszystkich opcji eksportu poprzez<br />
		menu <em>Plik</em> w pasku narzędzi, na samej górze, lub za pomocą skrótów:
	</p>
<ul>
<li><em>Zapisz</em> <kbd>Control</kbd> + <kbd>S</kbd>: zapisuje obraz do pliku (jeśli obraz został już zapisany, w przeciwnym wypadku wyświetla dialog <em>Zapisz jako...</em>)</li>
<li><em>Zapisz jako...</em> <kbd>Control</kbd> + <kbd>Shift</kbd> + <kbd>S</kbd>: pozwala na wybór formatu, lokalizacji, nazwy pliku i obrazu dla zapisywanego pliku</li>
<li><em>Kopiuj obrazek do schowka</em> <kbd>Control</kbd> + <kbd>Shift</kbd> + <kbd>C</kbd>: umieszcza kopię obrazu w schowku, umożliwiając wklejenie jej do innych programów</li>
<li><em>Drukuj...</em> <kbd>Control</kbd> + <kbd>P</kbd>: przesyła obraz do drukarki</li>
<li><em>E-Mail</em> <kbd>Control</kbd> + <kbd>E</kbd>: otwiera nową wiadomość, w domyślnym kliencie e-mail, dodając obraz jako załącznik</li>
</ul>
<p class="hint">
		Po zapisaniu obrazu z edytora, kliknij prawym przyciskiem myszy na pasku stanu na dole<br />
		okna edytora, albo skopiuj ścieżkę pliku do schowka, lub otwórz zawierający go katalog,<br />
		w Eksploratorze Windows.
	</p>
<p>	<a name="settings"></a></p>
<h2>Okno ustawień</h2>
<p>	<a name="settings-general"></a></p>
<h3>Ustawienia ogólne</h3>
<ul>
<li><em>Język</em>: Możesz wybrać język, który chcesz używać.<br><br />
			Możesz pobrać dodatkowe pliki językowe dla Greenshota, <a href="#">tutaj</a>. </li>
<li><em>Rejestracja klawiszy skrótu</em>: Po zaznaczeniu, Greenshot może być uruchamiany za pomocą klawisza <kbd>Print</kbd>.</li>
<li><em>Uruchom Greenshot przy starcie</em>: Uruchomia program wraz ze startem systemu.</li>
<li><em>Pokaż błysk flesza</em>: Efekt lampy błyskowej podczas wykonywania przechwytywania</li>
<li><em>Odtwórz dźwięk aparatu</em>: Sygnał dźwiękowy migawki, podczas wykonywania przechwytywania</li>
<li><em>Przechwytywanie wskaźnika myszy</em>: Jeżeli jest zaznaczone, zostanie przechwycony wskaźnik myszy. Wskaźnik jest obsługiwany jako osobny element w edytorze, dzięki czemu można go później przenieść lub usunąć.</li>
<li><em>Użyj trybu interaktywnego okna przechwytywanego</em>: Zamiast przechwytywania aktywnego okna od razu, tryb interaktywny<br />
			pozwala wybrać okno do przechwytywania. Możliwe jest również przechwytywanie okien podrzędnych, zobacz <a href="#capture-window">Przechwytywanie okna</a>.</li>
</ul>
<p>	<a name="settings-output"></a></p>
<h3>Ustawienia wyjściowe</h3>
<ul>
<li><em>Miejsce zrzutu ekranu</em>: Pozwala na wybór miejsca docelowego dla ulokowania zrzutu ekranu, po jego zrobieniu.</li>
<li><em>Preferowane ustawienia pliku wyjściowego</em>: Katalog i nazwa pliku zapisu bezpośredniego, lub sugerowanego (za pomocą dialogu <em>Zapisz jako...</em>) podczas zapisywania. Kliknij przycisk <em>?</em> , aby dowiedzieć się więcej o symbolach zastępczych, które mogą być użyte jako wzorzec nazwy pliku.</li>
<li><em>Ustawienia JPEG</em>: Ustawienia jakości zapisu plików JPEG</li>
</ul>
<p>	<a name="settings-printer"></a></p>
<h3>Ustawienia drukarki</h3>
<ul>
<li><em>Zacieśnij wydruk aby dopasować rozmiar papieru</em>: Jeśli obraz przekroczy rozmiar papieru, będzie zacieśniony, aby zmieścił się na stronie.</li>
<li><em>Powiększ wydruk aby dopasować rozmiar papieru</em>: Jeśli obraz jest mniejszy niż rozmiar papieru, będzie skalowany do wydrukowania jak największy, nie przekraczając rozmiaru papieru.</li>
<li><em>Obróć wydruku do orientacji strony</em>: Obraz będzie obrócony, w formacie krajobrazu, o 90 do drukowania.</li>
</ul>
<p>	<a name="help"></a></p>
<h2>Chcesz pomóc?</h2>
<p>
		Obecnie nie potrzeba pomocy w rozwoju. Jednakże, istnieje kilka rzeczy, które<br />
		mogą wesprzeć Greenshot i deweloperów.<br><br />
		Z góry dziękuję :)
	</p>
<p>	<a name="help-donate"></a></p>
<h3>Rozważ darowiznę</h3>
<p>
		Wkładamy dużo pracy w Greenshot i poświęcamy sporo czasu, aby zapewnić<br />
		kawał dobrego oprogramowania, o wolnym i otwartym kodzie źródłowym. Jeśli czujesz,<br />
		że zapewnia to większą wydajność pracy, jeśli oszczędza to Tobie (lub firmie)<br />
		dużo czasu i pieniędzy, czy po prostu podobnie jak Greenshot, popierasz ideę<br />
		oprogramowania open source:. rozważ uhonorowanie naszych wysiłków, przekazując darowiznę<br><br />
		Proszę spojrzeć na naszą stronę domową, aby zobaczyć, jak można wspierać zespół rozwoju Greenshot<br><br />
		<a href="/support/">http://getgreenshot.org/support/</a>
	</p>
<p>	<a name="help-spread"></a></p>
<h3>Rozpowszechnianie</h3>
<p>
		Jeśli podoba Ci się Greenshot, niech ludzie się dowiedzą: powiedzieć swoim znajomym i kolegom o Greenshot.<br />
		Swoim zwolennikom, także :)<br><br />
		Oceń Greenshot na portalach z oprogramowaniem, lub wstaw łącze do naszej strony głównej, na swoim blogu lub stronie.
	</p>
<p>	<a name="help-translate"></a></p>
<h3>Dodaj tłumaczenie</h3>
<p>
		Greenshot nie jest dostępny w wybranym języku? Jeśli uważasz, że nadaje się do tłumaczenia jakiś<br />
        kawałek oprogramowania, to jest to więcej niż mile widziane.<br />
		Jeżeli jesteś zarejestrowanym użytkownikiem na sourceforge.net, możesz przesłać tłumaczenia do naszego<br />
		<a href="https://sourceforge.net/tracker/?group_id=191585&atid=1368020">działu tłumaczeń</a>.<br><br />
		Upewnij się, że nie istnieje już tłumaczenie na Twój język w naszych<br />
		<a href="#">plikach do pobrania</a>. Sprawdź również nasz <a href="https://sourceforge.net/tracker/?group_id=191585&atid=1368020">dział tłumaczeń</a>,<br />
		może być tam tłumaczenie w toku, lub przynajmniej w dyskusji.<br><br />
		Pamiętaj, my tylko dostarczamy tłumaczenie na naszej stronie plików do pobrania, jeżeli<br />
		zostały złożone za pośrednictwem konta użytkownika sourceforge.net. Ponieważ ktoś może<br />
		nie być w stanie zrozumieć tłumaczenia, w interesie innych użytkowników sourceforge jest to,<br />
		aby mogli skontaktować się z Tobą w sprawie ulepszeń i udoskonaleń, w przypadku nowej wersji<br />
		Greenshot.
	</p>

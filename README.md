# moja-strona
moja strona o temacie
<!doctype html>
<html lang="pl"><head><meta charset="utf-8"><meta name="viewport" content="width=device-width, initial-scale=1">
<title>Tworzenie własnej strony internetowej</title>
<style>
*{box-sizing:border-box}body{margin:0;background:#10152f;color:#f4f6ff;font:17px/1.6 Arial,sans-serif}
header{text-align:center;padding:42px 18px;background:linear-gradient(135deg,#17234b,#34245c);border-bottom:3px solid #35d5ff}
h1{color:#35d5ff;font-size:clamp(30px,5vw,46px)}header p{max-width:700px;margin:auto;color:#d2daf5}
nav{position:sticky;top:0;background:#0d122a;padding:12px;display:flex;justify-content:center;gap:8px;flex-wrap:wrap}
nav a{color:white;text-decoration:none;padding:6px 10px;border-radius:7px}nav a:hover{background:#29345e;color:#35d5ff}
main{max-width:920px;width:92%;margin:28px auto}section{background:#20294d;border:1px solid #3a4776;border-radius:14px;padding:22px;margin:18px 0}
h2{color:#c49aff;margin-top:0}h3{color:#9cecff}.grid{display:grid;grid-template-columns:repeat(auto-fit,minmax(190px,1fr));gap:12px}
.tile{background:#29345e;padding:14px;border-left:4px solid #35d5ff;border-radius:9px}li{margin:7px 0}
code{background:#111a38;color:#a9efff;padding:2px 6px;border-radius:4px}.q{background:#29345e;border:1px solid #48588e;padding:14px;border-radius:9px;margin:12px 0}.q p{font-weight:bold;margin:0}.line{height:26px;border-bottom:1px dashed #8290bd}
button{display:block;margin:22px auto;background:#35d5ff;color:#10152f;border:0;border-radius:8px;padding:11px 18px;font-weight:bold;font-size:16px}
footer{text-align:center;color:#c8d0ed;padding:20px}
@media print{body{background:white;color:black}header{background:white}h1,h2,h3,header p{color:black}nav,button{display:none}section,.tile,.q{background:white;color:black;box-shadow:none;border:1px solid #aaa;break-inside:avoid}code{background:#eee;color:black}footer{color:black}}
</style></head><body>
<header><h1>Tworzenie własnej strony internetowej</h1><p>Notatka i przewodnik do lekcji informatyki – klasa 7</p></header>
<nav><a href="#start">Początek</a><a href="#plan">Plan</a><a href="#html">HTML</a><a href="#css">CSS</a><a href="#etapy">Etapy</a><a href="#bezpieczenstwo">Bezpieczeństwo</a><a href="#quiz">Pytania</a></nav>
<main>
<section id="start"><h2>1. Od czego zacząć?</h2><p>Tworzenie strony internetowej zaczynamy od wybrania tematu i zastanowienia się, dla kogo będzie przeznaczona. Tematem może być na przykład sport, zwierzęta, podróże lub gry komputerowe. Następnie decydujemy, jakie informacje chcemy na niej umieścić.</p></section>
<section id="plan"><h2>2. Planowanie strony</h2><p>Przed rozpoczęciem pracy warto przygotować plan strony. Zastanówmy się nad jej tytułem, nagłówkami, tekstami, obrazami i menu.</p><div class="grid"><div class="tile"><h3>Tytuł</h3><p>Nazwa informująca o temacie strony.</p></div><div class="tile"><h3>Nagłówki</h3><p>Dzielą treść na części.</p></div><div class="tile"><h3>Treść</h3><p>Teksty, zdjęcia i inne materiały.</p></div><div class="tile"><h3>Nawigacja</h3><p>Menu i odnośniki pomagające znaleźć informacje.</p></div></div></section>
<section><h2>3. Potrzebne narzędzia</h2><ul><li><b>Edytor tekstu lub kodu</b> – służy do pisania kodu, np. Notatnik.</li><li><b>Przeglądarka internetowa</b> – pozwala wyświetlić stronę, np. Chrome, Edge lub Opera.</li><li><b>Plik HTML</b> – zawiera kod strony i zwykle ma rozszerzenie <code>.html</code>.</li></ul></section>
<section id="html"><h2>4. HTML – struktura strony</h2><p>HTML to język znaczników, który określa strukturę i zawartość strony. Dzięki niemu dodajemy nagłówki, akapity, obrazy i odnośniki.</p><ul><li><code>&lt;html&gt;</code> – dokument HTML.</li><li><code>&lt;head&gt;</code> – informacje o stronie.</li><li><code>&lt;title&gt;</code> – tytuł na karcie przeglądarki.</li><li><code>&lt;body&gt;</code> – główna treść strony.</li><li><code>&lt;h1&gt;</code>, <code>&lt;h2&gt;</code> – nagłówki.</li><li><code>&lt;p&gt;</code> – akapit tekstu.</li><li><code>&lt;img&gt;</code> – obraz.</li><li><code>&lt;a&gt;</code> – odnośnik.</li></ul></section>
<section id="css"><h2>5. CSS – wygląd strony</h2><p>CSS służy do określania wyglądu strony. Możemy dzięki niemu ustawić kolory tekstu i tła, rodzaj i wielkość czcionki, odstępy, obramowania oraz rozmieszczenie elementów.</p><p><b>Zapamiętaj:</b> HTML odpowiada za strukturę strony, a CSS za jej wygląd.</p></section>
<section id="etapy"><h2>6. Etapy tworzenia strony</h2><ol><li>Wybierz temat i nazwę strony.</li><li>Zaplanuj, jakie informacje umieścisz.</li><li>Otwórz edytor tekstu lub kodu.</li><li>Napisz strukturę w HTML.</li><li>Dodaj style CSS.</li><li>Zapisz plik z rozszerzeniem <code>.html</code>.</li><li>Otwórz plik w przeglądarce.</li><li>Sprawdź, czy wszystko działa, i popraw błędy.</li></ol></section>
<section><h2>7. Zasady dobrej strony internetowej</h2><ul><li>Strona powinna być czytelna i przejrzysta.</li><li>Informacje powinny być logicznie uporządkowane.</li><li>Kolory tekstu i tła powinny być dobrze dobrane.</li><li>Menu i odnośniki powinny być łatwe do znalezienia.</li><li>Strona powinna działać na komputerze, tablecie i telefonie.</li><li>Nie należy dodawać zbyt wielu niepotrzebnych elementów.</li></ul></section>
<section id="bezpieczenstwo"><h2>8. Bezpieczeństwo i prawa autorskie</h2><ul><li>Nie publikuj prywatnych danych, np. adresu zamieszkania ani haseł.</li><li>Korzystaj z materiałów, do których masz prawo.</li><li>Podaj autora i źródło materiału, jeśli wymagają tego zasady jego wykorzystania.</li><li>Sprawdzaj, czy informacje są wiarygodne.</li></ul></section>
<section><h2>9. Przykład projektu – Gaming Zone</h2><p>Strona „Gaming Zone” może być poświęcona grom komputerowym. Można umieścić na niej opisy popularnych gier, gatunki gier, ciekawostki i porady dotyczące bezpiecznego korzystania z internetu.</p></section>
<section><h2>10. Podsumowanie</h2><p>Tworzenie strony internetowej obejmuje zaplanowanie tematu i treści, przygotowanie struktury w HTML, nadanie wyglądu za pomocą CSS oraz sprawdzenie działania strony w przeglądarce. Dobra strona jest czytelna, uporządkowana, bezpieczna i wygodna w obsłudze.</p></section>
<section id="quiz"><h2>11. Sprawdź, czy już umiesz!</h2><p>Odpowiedzcie na pytania wspólnie w klasie. Odpowiedzi nie są podane.</p>
<div class="q"><p>1. Od czego warto zacząć tworzenie własnej strony internetowej?</p><div class="line"></div></div>
<div class="q"><p>2. Do czego służy HTML?</p><div class="line"></div></div>
<div class="q"><p>3. Za co odpowiada CSS?</p><div class="line"></div></div>
<div class="q"><p>4. W jakim programie można napisać kod strony?</p><div class="line"></div></div>
<div class="q"><p>5. Jakie rozszerzenie powinien mieć plik strony HTML?</p><div class="line"></div></div>
<div class="q"><p>6. Dlaczego warto sprawdzić stronę w przeglądarce?</p><div class="line"></div></div>
<div class="q"><p>7. O czym należy pamiętać, publikując materiały na stronie?</p><div class="line"></div></div>
<button onclick="window.print()">Drukuj stronę</button></section>
</main><footer>Materiały do lekcji informatyki • Tworzenie własnej strony internetowej</footer>
</body></html>

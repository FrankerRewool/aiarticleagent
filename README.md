# AI Article Agent dla DokuWiki

AI Article Agent to zaawansowany plugin dla systemu DokuWiki (kompatybilny z wersją 2024+ i nowszymi) pełniący rolę integratora z LLM (Artificial Intelligence Language Model). 

Umożliwia generowanie kompletnych artykułów z bogatą strukturą DokuWiki (nagłówki, listy, boldy, boxy, tabele porównawcze). Wspiera kluczowych dostawców takich jak **OpenRouter** (domyślnie), **OpenAI**, **Anthropic**, **Grok**, i **Gemini** (lub dowolne zgodne z API OpenAI-like).

## Główne Funkcje

1. **Auto Article Generation**: Podaj prompt/wytyczne -> otrzymasz potężny, dobrze ustrukturyzowany, otagowany i sformatowany artykuł prosto w edytorze albo w locie.
2. **Zaawansowany System Prompt**: Automatycznie zdefiniowane polecenia powodują, że model zachowuje się jak ekspert DokuWiki (Tworzy sekcje zobacze też, tabele dekompozycji i spisy treści).
3. **Konfiguracja API Z Poziomu PA**: Admin łatwo, bezpiecznie klucz, preferowany model, temperaturę, ograniczenia tokenów.
4. **Przycisk w Edytorze**: One-click prompt uruchamiający AJAX generation na żywo we flow edycji.
5. **Syntax tagów w treści**: `{{aiarticle> Konfiguracja routera MikroTik | model=gpt-4o | style=techniczny}}`. Generuj w locie!

## Instalacja

1. Pobierz lub sklonuj repozytorium do folderu `lib/plugins/aiarticleagent`.
2. Udaj się do panelu DokuWiki (Zarządzanie Caching & Konfiguracja).
3. Podaj klucz API - np. do [OpenRouter](https://openrouter.ai).
4. Gotowe!

## Kompatybilność

- **Wymagania**: DokuWiki 2024+ (np. "Kaos" lub nowsze).
- **PHP**: >= 7.4. (Zalecane PHP 8.1+).

## Bezpieczeństwo
Hasła/Tokeny i klucze API są automatycznie wpisywane w Config Manager DokuWiki jako atrybut `password`, dzięki czemu chronią twoje uprawnienia przed wglądem.

Autor: Franker Kimono
Data: 24 Maja 2026

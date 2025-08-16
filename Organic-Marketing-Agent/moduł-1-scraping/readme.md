# 📊 Moduł 1: Community Sentiment Scraping

## Funkcje modułu:
- **Pobieranie aktualnych danych** z Facebook i Instagram (treść, like, grafiki) z ostatnich 7 dni
- **Analiza konkurencji** - dane z grup tematycznych, profili konkurencyjnych
- **Inteligentne filtrowanie** - dane wgrywane do arkuszy Google z automatycznym czyszczeniem
- **Eliminacja duplikatów** - arkusze czyszczone przed aktualizacją

## Korzyści z automatycznego scrapingu danych:
* **Oszczędność do 20 godzin tygodniowo** - eliminacja ręcznego monitorowania social media
* **Real-time market intelligence** - dostęp do aktualnych trendów i nastrojów społeczności
* **Kompleksowy obraz konkurencji** - automatyczne śledzenie działań wszystkich graczy na rynku
* **Czyste, gotowe do analizy dane** - inteligentne filtrowanie eliminuje szumy informacyjne

## Przepływ danych:
1. **Schedule Trigger** - automatyczne uruchomienie co 7 dni
2. **Scraping wieloźródłowy** - równoczesne pobieranie z Instagram, profili konkurencji i grup Facebook
3. **Przetwarzanie JSON** - konwersja i czyszczenie pobranych danych
4. **Zapis do arkuszy** - uporządkowane wprowadzanie do Google Sheets
5. **Execute Workflow** - przekazanie danych do kolejnego modułu

![Moduł Scrapingu](https://github.com/IGUANAH-ai/socialloop-n8n-portfolio/blob/main/Organic-Marketing-Agent/modu%C5%82-1-scraping/modu%C5%82-1-scraping.png?raw=true)


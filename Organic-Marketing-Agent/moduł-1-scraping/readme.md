# 📊 Moduł 1: Community Sentiment Scraping

![Moduł Scrapingu](https://github.com/IGUANAH-ai/socialloop-n8n-portfolio/blob/main/Organic-Marketing-Agent/modu%C5%82-1-scraping/modu%C5%82-1-scraping.png?raw=true)

## Funkcje modułu:
- **Pobieranie aktualnych danych** z Facebook i Instagram (treść, like, grafiki) z ostatnich 7 dni
- **Analiza konkurencji** - dane z grup tematycznych, profili konkurencyjnych
- **Inteligentne filtrowanie** - dane wgrywane do arkuszy Google z automatycznym czyszczeniem
- **Eliminacja duplikatów** - arkusze czyszczone przed aktualizacją

## Przepływ danych:
1. **Schedule Trigger** - automatyczne uruchomienie co 7 dni
2. **Scraping wieloźródłowy** - równoczesne pobieranie z Instagram, profili konkurencji i grup Facebook
3. **Przetwarzanie JSON** - konwersja i czyszczenie pobranych danych
4. **Zapis do arkuszy** - uporządkowane wprowadzanie do Google Sheets
5. **Execute Workflow** - przekazanie danych do kolejnego modułu

# web-scrapping-Genius-Artist-Data-Extractor
***Web Scraping Project: Genius Artist Data Extractor***


This script extracts artist information and top songs from Genius.com using HTTP requests and HTML parsing with BeautifulSoup.

# Описание проекта
Этот проект демонстрирует базовые принципы веб-скрапинга с использованием Python. Скрипт автоматически извлекает информацию об артисте и его популярных песнях с сайта Genius.com — платформы для текстов песен.

# Просмотр ноутбука доступен по ссылке:
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/VeronikaKolimova/web-scrapping-Genius-Artist-Data-Extractor/blob/main/Web_scrapping_genius_artists.ipynb)

# Функционал
- Получение содержимого веб-страницы артиста
- Парсинг HTML для извлечения данных
- Извлечение названий и ссылок на первые 3 популярные песни артиста
- Сохранение исходного HTML для отладки и анализа
- Обработка ошибок при выполнении запросов

# Требования
Для запуска скрипта необходимы следующие библиотеки Python:
pip install requests beautifulsoup4

# Пример вывода
Сохранён исходный HTML в файл: genius_artist_page.html

Артист: Ed-sheeran
Страница: https://genius.com/artists/Ed-sheeran

Первые 3 популярные песни:
 1. Shape of YouEd Sheeran
 Ссылка: https://genius.com/Ed-sheeran-shape-of-you-lyrics
 2. PerfectEd Sheeran
 Ссылка: https://genius.com/Ed-sheeran-perfect-lyrics
 3. PhotographEd Sheeran
 Ссылка: https://genius.com/Ed-sheeran-photograph-lyrics

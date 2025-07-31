# Billboard-100-web-scraping
A Python script that scrapes the Billboard Hot 100 chart for a user-specified date and automatically creates a corresponding playlist on Spotify using the Spotipy API.
# 🎶 Billboard to Spotify Playlist Generator

This project allows you to **travel back in time** and relive your favorite music hits! By scraping the Billboard Hot 100 chart for a given date and using the Spotify API, this Python script generates a Spotify playlist with the top tracks from that day.

---

## 🚀 Features

- Scrapes Billboard's Hot 100 chart for any specified date.
- Searches for each track on Spotify.
- Automatically creates a private playlist on your Spotify account and adds the found songs.
- Skips unavailable tracks gracefully.

---

## 📸 Demo

> ✨ _"Want to relive the top 100 songs from your graduation year, birthday, or a special memory? Just run the script and enjoy the nostalgia."_  
![Example Output](#) *(screenshot to be added here)*

---

## 🛠️ Technologies Used

- **Python**
- **BeautifulSoup** for web scraping
- **Spotipy** for interacting with the Spotify Web API
- **Requests** for HTTP calls

---

## 🧠 What I Did

- Built a web scraper using `requests` and `BeautifulSoup` to extract song titles from the Billboard Hot 100 archive.
- Parsed and cleaned the chart data to obtain a clean list of song names.
- Integrated the `Spotipy` library to authenticate with Spotify and search for each song.
- Handled edge cases like unavailable songs gracefully using try-except blocks.
- Created a Spotify playlist with the retrieved songs and populated it with available track URIs.
- Made the user experience interactive by prompting for a custom date input.

---


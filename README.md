# 🎮 Steam Poster Factory

An automated, AI-assisted Python tool running on Google Colab that generates high-quality, custom video game posters and grid images for your digital library.

## 🖼️ Poster Styles Gallery

| Box Poster | Vertical Poster | Horizontal Poster | Logo Box |
| :---: | :---: | :---: | :---: |
| [Berserk Boy_BoxPoster_v1](https://github.com/user-attachments/assets/2eae8811-67e8-403a-ab98-8cbd4b9b7d9e)
] | [ARRASTRA AQUÍ LA IMAGEN DEL VERTICAL POSTER] | [ARRASTRA AQUÍ LA IMAGEN DEL HORIZONTAL POSTER] | [ARRASTRA AQUÍ LA IMAGEN DEL LOGO BOX] |

## ✨ Features
* **Fully Automated Data Fetching:** Automatically searches the Steam API, SteamSpy, Wikipedia, and SteamGridDB to fetch game metadata (Year, Developer, Genres) and high-res art.
* **Smart Fallback System:** Prioritizes clean "No Logo" art, but seamlessly falls back to Steam Banners (`page_bg_raw`) or official posters if clean art isn't available.
* **Procedural Palettes:** Extracts the dominant colors from the game's art to theme the poster.
* **4 Unique Styles:** Box Poster, Vertical Poster, Horizontal Poster, and Logo Box.
* **Advanced Framing:** Control X/Y alignment for horizontal banners to capture the perfect scene.

## 🚀 Getting Started (Google Colab)
This project is designed to run effortlessly in Google Colab. No local Python installation required.

1. Create a folder in your Google Drive to store your resources. The code defaults to looking at: `/content/drive/MyDrive/*IA/Colab Notebooks/RECURSOS`
2. Upload the required fonts (`MotivaSansBlack.woff.ttf`, `MotivaSansExtraBold.ttf`).
3. Upload brand logos (e.g., `STEAM.png`, `PLAYSTATION LOGO.png`).
4. **API Key:** Create a text file named `steamgriddb_api.txt` containing your SteamGridDB API key and place it in the resources folder.
5. Open the `.ipynb` notebook in Google Colab, run all cells, and use the UI to generate!

## 🤝 Contributing
Contributions are welcome! If you want to add new layout styles, integrate new APIs (like IGDB), or improve the rendering engine:
1. Fork the Project.
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`).
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`).
4. Push to the Branch (`git push origin feature/AmazingFeature`).
5. Open a Pull Request.

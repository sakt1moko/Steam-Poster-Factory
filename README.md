# 🎮 Steam Poster Factory

An automated, AI-assisted Python tool running on Google Colab that generates high-quality, custom video game posters and grid images for your digital library.

## 🖼️ Poster Styles Gallery

| Box Poster | Vertical Poster | Horizontal Poster | Logo Box |
| https://github.com/user-attachments/assets/b68ccde8-90ad-4969-8416-e3f030631bb8| https://github.com/user-attachments/assets/5062f70c-dea0-4a05-b0d0-48c78de78076 | https://github.com/user-attachments/assets/059c7ee4-5941-44d0-a4bd-7f483e3c65eb | https://github.com/user-attachments/assets/54ec6a0e-1568-4bb8-8635-d22839e5822b |
| [![Berserk Boy_BoxPoster_v1]()
POSTER] | [ARRASTRA AQUÍ LA IMAGEN DEL VERTICAL ![Berserk Boy_VerticalPoster_v2]()
POSTER] | [ARRASTRA AQUÍ LA IMAGEN DEL HORIZONTAL POSTER]![Berserk Boy_HorizontalPoster_v1](https://github.com/user-attachments/assets/059c7ee4-5941-44d0-a4bd-7f483e3c65eb)
 | [ARRASTRA AQUÍ LA IMAGEN DEL LOGO BOX] ![Berserk Boy_LogoBox_v1](
|

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

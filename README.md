# AnimeVerse
Animeverse is a Flutter-based mobile application designed to help users easily discover, explore, and view detailed information about various anime titles. The app features a modern interface and a clean user experience, allowing users to browse anime effortlessly and intuitively.

---

## Student Information

| Informasi | Detail        |
|-----------|---------------|
| **Name**  | Chairun Nisaq |
| **NIM**   | 231401042     |
| **KOM**   | C             |


---

### Key Features
- **Anime Browsing**  
  Easily browse and discover a wide range of popular and trending anime. The app fetches real-time data from the Jikan API, allowing users to stay up-to-date with the latest anime releases and trends. Users can explore different genres and find anime that match their interests.
- **Details Anime**  
  Each anime comes with detailed information, including its title, genres, synopsis, rating, and other relevant details. This allows users to gain a full understanding of the anime before watching or adding it to their favorites.
- **Favorite Anime**  
  Users can mark their favorite anime and manage their personalized list. Favorites can be added or removed in real time, with all data securely stored in Cloud Firestore. This feature ensures that users always have quick access to the anime they love the most.
- **Profile**  
  The app provides a user profile section where users can view and update their basic account information. This allows for a more personalized experience and better management of user-specific data.
- **Authentication**  
  Secure and convenient login options are available through Firebase Authentication. Users can sign in using their Google account or email, providing flexibility while maintaining a high level of security for their personal data.

---

## Screenshots

| Home Screen                                                              | Detail Screen                                         | Favorite Screen                                      |
|----------------------------------------------------------------------------|-------------------------------------------------------|------------------------------------------------------|
| <img src="./assets/images/home.png" width="250" style="border-radius:8px;"> | <img src="./assets/images/deskripsi.png" width="250"> | <img src="./assets/images/favorite.png" width="250"> |

| Profile Screen                                      | Sign In Screen                                     | Sign Up Screen                                     |
|-----------------------------------------------------|----------------------------------------------------|----------------------------------------------------|
| <img src="./assets/images/profile.png" width="250"> | <img src="./assets/images/signin.png" width="250"> | <img src="./assets/images/signup.png" width="250"> |


---

## Demo Aplikasi
**Demo:** [here](https://youtu.be/iZh8S9fqXSA?si=NQrv6W_0D94hXBIx)

---

## Struktur Proyek

```text
lib/
├── main.dart                               
├── config/
│   └── routes.dart                        
├── models/
│   └── anime.dart                          
├── provider/
│   ├── app_state_provider.dart              
│   └── auth_provider.dart                   
├── repositories/
│   └── anime_repository.dart                
├── screens/
│   ├── home_screen.dart                     
│   ├── detail_screen.dart                  
│   ├── favorite_screen.dart                
│   ├── profile_screen.dart                  
│   ├── signin_screen.dart                   
│   └── signup_screen.dart                   
├── services/
│   ├── firestore_service.dart             
│   └── auth/
│       └── auth_service.dart               
├── utils/
│   ├── snackbar_helper.dart               
│   └── validators.dart                     
└── widgets/
    ├── anime_card.dart                      
    ├── anime_view.dart                      
    ├── app_scaffold.dart                    
    ├── bottom_navigation_shell.dart         
    ├── favorite_anime_card.dart             
    ├── genre_list.dart                      
    ├── gradient_background.dart             
    └── profile_button.dart                  
```


---

## APIs & Services
### **Jikan API – MyAnimeList Unofficial API**
https://docs.api.jikan.moe/

### **Services**
- Firebase Authentication
- Cloud Firestore
- Flutter Framework

---

## Packages & Dependencies

| Package                   | Versi     | Fungsi |
|--------------------------|-----------|--------|
| cupertino_icons          | ^1.0.8    | Icon gaya iOS |
| flutter_svg              | ^2.2.3    | Menampilkan SVG |
| go_router                | ^17.0.0   | Routing aplikasi |
| shared_preferences       | ^2.5.3    | Local storage ringan |
| provider                 | ^6.1.5+1  | State management |
| http                     | ^1.6.0    | HTTP client |
| cached_network_image     | ^3.4.1    | Cache gambar |
| firebase_core            | ^4.2.1    | Core Firebase SDK |
| firebase_auth            | ^6.1.2    | Autentikasi pengguna |
| google_sign_in           | ^7.2.0    | Login Google |
| cloud_firestore          | ^6.1.0    | Database Firebase |
| flutter_launcher_icons   | ^0.14.4   | Generate app icon |
| flutter_native_splash    | ^2.4.7    | Generate splash screen |


---

## Thank You!  

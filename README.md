
---

# 💼 SKILLswipe

**SKILLswipe** is a modern **Flutter-based job/skill matching app**, inspired by Tinder-style UI. It allows users to create profiles, add skills, and swipe to match with relevant collaborators or opportunities. The app uses **Firebase Firestore** for backend storage and integrates **Google APIs** to calculate match proximity based on location.

---

## 🚀 Features

* 🔄 **Tinder-like swipe interface** for skill-based matching
* 👤 **User Profile Creation** with custom skill tags
* 📍 **Google Maps API Integration** for proximity-based filtering
* 🔥 **Firebase Firestore** for real-time data handling
* 📊 Dynamic match suggestions based on:

  * Skill similarity
  * Location radius
  * Availability/status

---

## 🛠️ Tech Stack

* **Frontend**: Flutter (Dart)
* **Backend**: Firebase Firestore
* **Authentication**: Firebase Auth (Google Sign-In, optional)
* **APIs**: Google Maps / Places API (for location & range-based filtering)

---

## 📲 How It Works

1. **User creates profile** with name, skills, and location
2. The app fetches other user profiles from Firestore
3. Matches are filtered based on:

   * Shared skills
   * Matching location range (via Google Maps API)
4. Users can swipe right to connect or left to skip
5. Optional: match chat, email alerts, or collaboration suggestion

---

## 📁 Files

* `SkillSwipe+Demo.webm`: App demo walkthrough
* `skillswipe.zip`: Full source code and assets
* `README.md`: Project documentation

---

## 🧪 Getting Started

```bash
git clone https://github.com/your-username/skillswipe.git
cd skillswipe
flutter pub get
flutter run
```

Ensure you've added your own `google-services.json` file for Firebase setup.

---

## 🎥 Demo

👉 Watch the app in action:
[SkillSwipe+Demo.webm](./SkillSwipe+Demo.webm)

---

## 📬 Authors

Built with ❤️ by [Anish Sihag](mailto:anishsihag12@gmail.com) and team
GitHub: [@anish41338](https://github.com/anish41338)

---


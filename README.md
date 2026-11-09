<div align="center">

# مشكاة
# Mishkat

**An offline encyclopedia of Islamic biographies, with verified sources and the connections between people.**

![Flutter](https://img.shields.io/badge/Flutter-02569B?logo=flutter&logoColor=white)
![Platform](https://img.shields.io/badge/Platform-Android-3DDC84?logo=android&logoColor=white)
![Status](https://img.shields.io/badge/Status-In%20Development-orange)

</div>

---

## About

Mishkat helps you learn about the people who shaped Islamic history: the prophets, the
companions (sahaba), the successors (tabi'un), and well-known scholars. Browse by
category, search for a name, and read a profile that links back to its sources.

What makes it different from a simple list is that **people are connected**. You can
move from a companion to his relatives, from a tabi'i to the sahaba he learned from,
or from a scholar to his teachers and students.

## Features

| Category | What each profile includes |
|---|---|
| **Prophets** | Name (Arabic and English), special miracles, story summary from the Quran and hadith, references |
| **Sahaba** | Full name, relatives among the sahaba, relation to the Prophet ﷺ (if any), well-known speeches and advice, references |
| **Tabi'un** | Full name, which sahaba they learned from, well-known sayings and advice, references |
| **Scholars** | Full name, era, teachers and students, major works, well-known advice, references |

- Search across all categories
- Tappable reference links for further reading
- Connections between profiles
- Fully offline: all content is stored on the device

## Sources policy

Accuracy matters more than quantity. Every story, quote, or piece of advice must have
a source (book and number, or a link), and hadith include their grading. Content
without a verifiable source is not added. Quran text is taken from a trusted, verified
source and never retyped by hand.

## Roadmap

- [x] Project setup
- [ ] Data model: `Person`, `Relation`, `Source`
- [ ] First verified profiles
- [ ] Home, list, search, and profile screens
- [ ] **v1:** all prophets and 15-20 sahaba
- [ ] **v1.1:** tabi'un
- [ ] **v1.2:** scholars (Ibn Taymiyyah, Ibn al-Qayyim, Ibn Kathir, As-Sa'di, Ibn Uthaymeen)
- [ ] **v2:** timeline view, family tree and teacher-student graph, bookmarks, Arabic and English interface, more languages

## Tech stack

- [Flutter](https://flutter.dev) (Dart)
- Local JSON content, SQLite for storage and search (planned)
- Git and GitHub for version control

## Getting started

**Requirements:** Flutter SDK (stable channel) and an Android device or emulator.

```bash
git clone https://github.com/ameturebi/mishkat_islamic_biographies
cd mishkat
flutter pub get
flutter run
```



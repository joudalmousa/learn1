# 📚 Learning Journey – iOS (SwiftUI)

[![Platform](https://img.shields.io/badge/platform-iOS-lightgrey)]()
[![Swift](https://img.shields.io/badge/Swift-5.9-orange)]()
[![Xcode](https://img.shields.io/badge/Xcode-15%2B-blue)]()
[![License](https://img.shields.io/badge/license-MIT-green)]()

> Track your daily learning with a clean, dark-mode friendly iOS app.  
> ✍️ Set a learning goal (Week / Month / Year), ✅ log “Learned”, ❄️ freeze days, and 📅 review your activity on a weekly or full-month calendar.

---

## 🌟 Overview | نظرة عامة
**EN:** Learning Journey helps you build and maintain a learning streak. Choose a timeframe (Week/Month/Year), log your progress daily (“Log as **Learned**” or “Log as **Frozen**”), edit your goal anytime, and review all past activities with a beautiful calendar.

**AR:** يسهّل تطبيق **Learning Journey** متابعة تعلّمك اليومي وبناء سلسلة التزام. اختَر مدّة الهدف (أسبوع/شهر/سنة)، وسجّل تعلّمك يوميًا (تم التعلّم / يوم مُجمّد)، وعدّل هدفك، واستعرض تاريخك عبر تقويم أسبوعي وشهري أنيق.

---

## ✨ Features | المزايا
- ✅ **Set Learning Goal**: Week / Month / Year + custom topic (e.g., “Swift”)
- 🔥 **Log as Learned** (per day)  
- ❄️ **Log as Frozen** with **period-based freeze limit** (2/week, 8/month, 96/year by default)
- 📆 **Weekly strip calendar** + **Full-month calendar** (“All activities”)
- 🗓️ **Month/Year wheel picker** (iOS UIPickerView bridge)
- 📝 **Goal editor** with “Update will reset streak” confirmation
- 💾 **Local persistence** via `UserDefaults`
- 🌙 **Dark/Light Mode** via `Color(.systemBackground)`, `Color(.label)`, `Color(.separator)`
- 🧭 **MVVM architecture** (SwiftUI + `Task1ViewModel`)
- 🎉 **“Well done!”** sheet with cheer icon when a goal period is fully covered

---

## 📸 Screenshots | لقطات شاشة
<!-- TODO: ضع صورك هنا -->
| Activity (Week) | Full Calendar | Goal Editor | Well Done |
| --- | --- | --- | --- |
| ![activity](docs/img/activity.png) | ![calendar](docs/img/calendar.png) | ![goal](docs/img/goal.png) | ![done](docs/img/done.png) |

> ضع الصور داخل مجلد `docs/img/` أو حدّث المسارات حسب مكانها في المشروع.

---

## 🧰 Tech Stack
- **Language:** Swift 5.9+
- **UI:** SwiftUI (iOS 17+), Dark/Light mode friendly
- **Architecture:** MVVM (`@MainActor`, `ObservableObject`, `@Published`)
- **Storage:** `UserDefaults`
- **Interop:** `UIViewRepresentable` for Month/Year `UIPickerView`

---

## 🚀 Quick Start | البدء السريع
### Requirements
- Xcode 15+
- iOS 17+ (simulator or device marked “Use for Development”)
- Swift 5.9+

### Run
```bash
git clone <YOUR_REPO_URL>
cd <YOUR_REPO_FOLDER>
open learn1.xcodeproj   # أو .xcworkspace إن وُجد
# في Xcode: اختر iPhone 15 Pro (Simulator) ثم Run ⌘R

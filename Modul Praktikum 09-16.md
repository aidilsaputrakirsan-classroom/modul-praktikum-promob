# Modul Project-Based Learning
## Week 9-16: Pengembangan Aplikasi Mobile Tim

**Mata Kuliah:** Pemrograman Mobile  
**Durasi:** 8 minggu (Week 9-16)  
**Format:** Project-based learning dengan tim  
**Bobot:** 40% dari nilai akhir

---

## 📋 Gambaran Umum Project

### **Tujuan Project:**
Mengembangkan aplikasi mobile yang menerapkan semua konsep yang telah dipelajari di Week 1-7, dengan fokus pada kerja tim, project management, dan quality assurance.

### **Struktur Tim:**
- **Ukuran Tim:** 3-4 orang per tim
- **Pembagian Peran:** Frontend, Backend/API, UI/UX, Project Manager
- **Komunikasi:** Weekly standup dan progress tracking

### **Deliverables Utama:**
- Week 9: Project proposal dan mockup
- Week 10-11: MVP (Minimum Viable Product)
- Week 12: Aplikasi terintegrasi dengan testing
- Week 13-14: Aplikasi final dengan fitur advanced
- Week 15: Dokumentasi lengkap dan persiapan presentasi
- Week 16: Presentasi final (UAS)

---

## 🗓️ WEEK 9: Project Planning & Team Formation

### **Objectives Week 9:**
- Pembentukan tim dan penetapan peran
- Brainstorming ide aplikasi
- Pembuatan project proposal
- Setup repository dan project structure

### **Deliverables Week 9:**
1. **Tim Formation Document**
2. **Project Proposal**
3. **UI/UX Mockup**
4. **Repository Setup**
5. **Project Timeline**

---

### **📝 Template Project Proposal**

**Nama Project:** [Nama Aplikasi]  
**Tim:** [Nama Anggota Tim + Peran]  
**Target User:** [Siapa pengguna aplikasi ini]

#### **1. Deskripsi Project (200-300 kata)**
- Apa masalah yang ingin diselesaikan?
- Mengapa aplikasi ini dibutuhkan?
- Siapa target pengguna utama?

#### **2. Fitur Utama (Minimal 5 fitur)**
- **Fitur 1:** [Deskripsi singkat]
- **Fitur 2:** [Deskripsi singkat]
- **Fitur 3:** [Deskripsi singkat]
- **Fitur 4:** [Deskripsi singkat]
- **Fitur 5:** [Deskripsi singkat]

#### **3. Tech Stack**
- **Framework:** React Native dengan Expo
- **Navigasi:** Expo Router
- **State Management:** React Hooks / Context API
- **Storage:** AsyncStorage
- **API:** [Jika menggunakan API eksternal]
- **Additional Libraries:** [Library tambahan yang akan digunakan]

#### **4. User Personas**
**Persona 1:**
- Nama: [Nama user]
- Usia: [Rentang usia]
- Pekerjaan: [Profesi]
- Kebutuhan: [Apa yang dibutuhkan dari aplikasi]
- Pain Points: [Masalah yang dihadapi saat ini]

**Persona 2:** [Jika ada multiple target user]

#### **5. Pembagian Tugas Tim**
- **[Nama]** - Frontend Developer: Implementasi UI dan komponen React Native
- **[Nama]** - Backend/API Developer: Integrasi API dan data management
- **[Nama]** - UI/UX Designer: Design interface dan user experience
- **[Nama]** - Project Manager: Koordinasi tim dan quality assurance

#### **6. Timeline & Milestones**
- **Week 10:** [Milestone 1]
- **Week 11:** [Milestone 2]
- **Week 12:** [Milestone 3]
- **Week 13:** [Milestone 4]
- **Week 14:** [Milestone 5]
- **Week 15:** [Final testing & documentation]

---

### **🎨 Template UI/UX Mockup**

**Tools yang Disarankan:**
- Figma (gratis untuk mahasiswa)
- Adobe XD
- Canva
- Bahkan sketsa tangan yang di-scan

**Yang Harus Disertakan:**
1. **Wireframes** - Layout dasar setiap screen
2. **User Flow** - Alur navigasi pengguna
3. **Color Palette** - Skema warna aplikasi
4. **Typography** - Jenis font yang akan digunakan
5. **Screen Mockups** - Minimal 5 screen utama

**Format Mockup:**
- Mobile-first design (ukuran layar ponsel)
- Konsisten dengan design guidelines (Material Design/iOS HIG)
- Include navigasi antar screen
- Responsive untuk berbagai ukuran layar

---

### **📁 Template Repository Setup**

**Repository Structure:**
```
[NamaProject]/
├── README.md                 # Dokumentasi project
├── docs/                     # Folder dokumentasi
│   ├── proposal.md          # Project proposal
│   ├── mockups/             # UI/UX mockups
│   ├── progress-reports/    # Weekly progress reports
│   └── final-presentation/  # Final presentation materials
├── src/                     # Source code aplikasi
│   ├── app/                 # Expo Router screens
│   ├── components/          # Reusable components
│   ├── services/            # API services
│   ├── utils/               # Helper functions
│   └── types/               # TypeScript types
├── assets/                  # Images, icons, fonts
├── package.json            # Dependencies
└── .gitignore              # Git ignore file
```

**README.md Template:**
```markdown
# [Nama Project]

## Deskripsi
[Deskripsi singkat aplikasi]

## Tim Pengembang
- [Nama] - [Peran]
- [Nama] - [Peran]
- [Nama] - [Peran]
- [Nama] - [Peran]

## Fitur Utama
- [Fitur 1]
- [Fitur 2]
- [Fitur 3]

## Tech Stack
- React Native + Expo
- [Library lainnya]

## Cara Menjalankan
1. Clone repository
2. npm install
3. npx expo start

## Progress
- [x] Week 9: Project planning
- [ ] Week 10: Core features development
- [ ] Week 11: Feature completion
- [ ] Week 12: Integration & testing

## Screenshots
[Akan diupdate seiring perkembangan]
```

---

## 🛠️ WEEK 10-11: Core Features Development

### **Objectives Week 10-11:**
- Implementasi fitur utama aplikasi
- Weekly standup dan progress tracking
- Code review antar anggota tim
- Testing basic functionality

### **Metodologi Pengembangan:**
**Agile Development dengan Sprint 1 minggu**

### **Daily Standup Format (3 menit per orang):**
1. **Apa yang dikerjakan kemarin?**
2. **Apa yang akan dikerjakan hari ini?**
3. **Ada blocker atau kendala?**

### **Weekly Progress Report Template:**

**Week [X] Progress Report**  
**Tim:** [Nama Tim]  
**Tanggal:** [Tanggal]

#### **Completed Tasks:**
- [x] [Task yang selesai]
- [x] [Task yang selesai]

#### **In Progress:**
- [ ] [Task sedang dikerjakan]
- [ ] [Task sedang dikerjakan]

#### **Blockers/Issues:**
- [Masalah yang dihadapi]
- [Cara penyelesaian]

#### **Next Week Plan:**
- [Plan untuk minggu depan]

#### **Screenshots/Demo:**
[Lampirkan screenshot progress aplikasi]

---

### **📋 Development Guidelines**

#### **Code Quality Standards:**
1. **Konsistensi Naming:** 
   - Variable dan function menggunakan camelCase
   - Component menggunakan PascalCase
   - File menggunakan kebab-case atau camelCase

2. **Component Structure:**
   - Functional components dengan hooks
   - Reusable components di folder terpisah
   - Props dengan TypeScript interfaces

3. **Code Organization:**
   - Satu component per file
   - Import statements terorganisir
   - Comments untuk logic yang kompleks

4. **Version Control:**
   - Commit messages yang descriptive
   - Branch untuk setiap feature
   - Regular merge ke main branch

#### **Code Review Checklist:**
- [ ] Code bersih dan mudah dibaca
- [ ] Tidak ada hardcoded values
- [ ] Error handling yang proper
- [ ] Responsive design
- [ ] Performance optimization
- [ ] No console.log di production code

---

## 🔗 WEEK 12: Integration & Testing

### **Objectives Week 12:**
- Integrasi semua fitur yang telah dikembangkan
- API integration (jika menggunakan external API)
- Testing di multiple devices
- Bug fixing dan optimization

### **Integration Checklist:**
- [ ] **Navigation Flow:** Semua screen terhubung dengan benar
- [ ] **Data Flow:** State management berfungsi antar components
- [ ] **API Integration:** Data fetching dan error handling
- [ ] **Local Storage:** Data persistence dengan AsyncStorage
- [ ] **Performance:** Aplikasi berjalan smooth di berbagai device

### **Testing Strategy:**

#### **Device Testing:**
1. **iOS Testing:**
   - iPhone (berbagai ukuran screen)
   - iPad (jika support tablet)

2. **Android Testing:**
   - Android phones (berbagai versi OS)
   - Tablet Android (opsional)

3. **Performance Testing:**
   - Low-end devices
   - Network connectivity issues
   - Battery usage

#### **User Testing:**
1. **Alpha Testing:** Testing oleh tim internal
2. **Beta Testing:** Testing oleh 2-3 user eksternal
3. **Usability Testing:** Observasi user menggunakan aplikasi

### **Bug Tracking Template:**

**Bug Report #[Number]**
- **Title:** [Judul singkat bug]
- **Priority:** High/Medium/Low
- **Status:** Open/In Progress/Resolved/Closed
- **Reporter:** [Nama pelapor]
- **Assignee:** [Nama yang handle]
- **Device:** [Device yang mengalami bug]
- **OS Version:** [Versi OS]
- **Steps to Reproduce:**
  1. [Langkah 1]
  2. [Langkah 2]
  3. [Langkah 3]
- **Expected Result:** [Hasil yang diharapkan]
- **Actual Result:** [Hasil yang terjadi]
- **Screenshots:** [Lampirkan screenshot jika perlu]

---

## 🚀 WEEK 13-14: Advanced Features & Polish

### **Objectives Week 13-14:**
- Implementasi fitur advanced
- UI/UX improvements
- Performance optimization
- Accessibility improvements

### **Advanced Features Options:**

#### **Technical Enhancements:**
- **Push Notifications:** Notifikasi untuk user engagement
- **Camera Integration:** Foto untuk profile atau content
- **Location Services:** GPS untuk location-based features
- **Offline Capability:** Sync data ketika online
- **Dark Mode:** Theme switching
- **Multi-language:** Internationalization

#### **UI/UX Enhancements:**
- **Smooth Animations:** Loading states, transitions
- **Gesture Controls:** Swipe, pinch, long press
- **Accessibility:** Screen reader support, high contrast
- **Onboarding:** Tutorial untuk first-time users
- **Error States:** Friendly error messages dan recovery options

#### **Performance Optimization:**
- **Image Optimization:** Lazy loading, compression
- **Memory Management:** Proper cleanup
- **Bundle Size:** Remove unused dependencies
- **Loading Performance:** Skeleton screens, preloading

### **Quality Assurance Checklist:**

#### **Functionality:**
- [ ] Semua fitur utama bekerja sesuai spesifikasi
- [ ] Navigation flow lancar dan intuitif
- [ ] Data persistence berfungsi dengan benar
- [ ] Error handling yang comprehensive
- [ ] Form validation yang proper

#### **Performance:**
- [ ] App startup time < 3 detik
- [ ] Smooth scrolling di semua list
- [ ] No memory leaks
- [ ] Responsive di berbagai ukuran screen
- [ ] Battery usage yang reasonable

#### **User Experience:**
- [ ] Konsistensi design di semua screen
- [ ] Feedback visual untuk semua user actions
- [ ] Loading states yang informatif
- [ ] Error messages yang user-friendly
- [ ] Accessible untuk user dengan disabilitas

---

## 📄 WEEK 15: Finalization & Documentation

### **Objectives Week 15:**
- Final testing dan bug fixes
- Dokumentasi lengkap
- Persiapan presentasi
- App store preparation (opsional)

### **Final Documentation Required:**

#### **1. Technical Documentation**
- **API Documentation:** Endpoint dan payload structure
- **Component Documentation:** Props dan usage examples  
- **Setup Guide:** Step-by-step installation
- **Troubleshooting Guide:** Common issues dan solutions

#### **2. User Documentation**
- **User Manual:** Cara menggunakan aplikasi
- **FAQ:** Frequently asked questions
- **Feature Guide:** Penjelasan setiap fitur
- **Screenshots:** Visual guide untuk user

#### **3. Project Documentation**
- **Project Summary:** Ringkasan project dan achievements
- **Lessons Learned:** Apa yang dipelajari selama development
- **Future Roadmap:** Rencana pengembangan ke depan
- **Team Reflection:** Evaluasi kerja tim

### **Final Testing Protocol:**

#### **Regression Testing:**
1. Test semua fitur utama sekali lagi
2. Verify bug fixes tidak memunculkan bug baru
3. Performance testing di berbagai device
4. User acceptance testing dengan fresh perspective

#### **Deployment Checklist:**
- [ ] Remove all console.log statements
- [ ] Update app version
- [ ] Optimize assets (images, fonts)
- [ ] Test production build
- [ ] Prepare app store metadata

---

## 🎤 WEEK 16: UAS - Project Presentation

### **Format Presentasi:**
- **Durasi:** 15 menit per tim (10 menit presentasi + 5 menit Q&A)
- **Audience:** Dosen dan mahasiswa lain
- **Format:** Live demo + slide presentation

### **Struktur Presentasi:**

#### **1. Introduction (2 menit)**
- Problem statement dan target user
- Team introduction dan role division
- Project overview

#### **2. Live Demo (5 menit)**
- Walkthrough fitur utama aplikasi
- Highlight unique features
- Show technical achievements

#### **3. Technical Deep Dive (2 menit)**
- Architecture overview
- Challenges faced dan solutions
- Technology stack justified

#### **4. Results & Impact (1 menit)**
- User feedback dan testing results
- Lessons learned
- Future improvements

#### **Q&A Session (5 menit)**
- Technical questions dari audience
- Code review discussion
- Project management insights

### **Presentation Guidelines:**

#### **Demo Best Practices:**
- **Test Demo Sebelumnya:** Pastikan aplikasi berjalan perfect
- **Backup Plan:** Siapkan video demo jika ada technical issues
- **Highlight Features:** Focus ke fitur yang impressive
- **Show Real Data:** Gunakan data realistis, bukan lorem ipsum
- **Smooth Navigation:** Practice alur demo berkali-kali

#### **Slide Deck Requirements:**
- **Maximum 10 slides** untuk presentasi utama
- Design yang clean dan professional
- Include screenshots aplikasi
- Highlight technical achievements
- Show team collaboration evidence

### **Code Review Session:**

#### **Persiapan Code Review:**
- Pilih 2-3 component yang paling representative
- Explain design decisions dan trade-offs
- Show best practices implementation
- Demonstrate clean code principles

#### **Code Review Topics:**
1. **Component Architecture:** Reusability dan maintainability
2. **State Management:** Efficient data flow
3. **Performance Optimization:** Rendering dan memory usage
4. **Error Handling:** Graceful degradation
5. **Code Quality:** Readability dan documentation

---

## 📊 Rubrik Penilaian Project

### **Total: 100 poin**

#### **Project Planning & Management (20 poin)**
- **Proposal Quality (8 poin):** Clarity, feasibility, innovation
- **Team Collaboration (7 poin):** Communication, task distribution
- **Timeline Management (5 poin):** Meeting deadlines, adaptability

#### **Technical Implementation (40 poin)**
- **Core Functionality (20 poin):** All main features working properly
- **Code Quality (10 poin):** Clean, organized, maintainable code
- **Technical Complexity (5 poin):** Challenging features implementation
- **Performance (5 poin):** Optimized, responsive application

#### **User Experience & Design (20 poin)**
- **UI Design (10 poin):** Visual appeal, consistency, branding
- **UX Flow (7 poin):** Intuitive navigation, user-friendly
- **Accessibility (3 poin):** Inclusive design considerations

#### **Documentation & Presentation (20 poin)**
- **Documentation Quality (8 poin):** Complete, clear, helpful
- **Presentation Skills (7 poin):** Clear communication, demo quality
- **Code Review (5 poin):** Explain decisions, show understanding

### **Bonus Points (up to 10 poin):**
- **Innovation:** Unique approach atau creative solutions
- **Advanced Features:** Beyond basic requirements
- **Community Impact:** Positive feedback dari user testing
- **Open Source Contribution:** Sharing components atau insights

---

## 📝 Templates & Resources

### **Project Ideas (untuk Inspirasi):**

#### **Category: Lifestyle**
- **Aplikasi Recipe Manager:** Koleksi resep dengan shopping list
- **Fitness Tracker:** Workout logging dengan progress tracking
- **Expense Tracker:** Personal finance management
- **Habit Tracker:** Daily habits dengan streak tracking

#### **Category: Education**
- **Language Learning App:** Flashcards dengan progress tracking
- **Study Timer:** Pomodoro technique dengan analytics
- **Quiz App:** Subject-specific dengan leaderboard
- **Note Taking App:** Enhanced dengan categorization

#### **Category: Productivity**
- **Event Planner:** Manage events dengan guest list
- **Inventory Manager:** Stock tracking untuk small business
- **Task Manager:** Team collaboration features
- **Time Tracker:** Project time tracking dengan reporting

#### **Category: Social**
- **Community Forum:** Local community discussions
- **Event Discovery:** Find local events dan activities
- **Skill Sharing:** Connect people untuk skill exchange
- **Study Group:** Find study partners berdasarkan subjects

### **Useful Resources:**

#### **Design Resources:**
- **Icons:** Feather Icons, Heroicons, React Native Vector Icons
- **Colors:** Coolors.co, Adobe Color
- **Fonts:** Google Fonts, font pairings
- **Inspiration:** Dribbble, Behance, Mobile Patterns

#### **Development Resources:**
- **Component Libraries:** React Native Elements, NativeBase
- **Utilities:** Lodash, Moment.js, React Hook Form
- **Testing:** Jest, React Native Testing Library
- **Analytics:** Expo Analytics, Firebase Analytics

#### **API Suggestions (Free Tier):**
- **Weather:** OpenWeatherMap
- **News:** NewsAPI
- **Images:** Unsplash API
- **Quotes:** Quotable API
- **Maps:** Mapbox (limited free tier)

---

## 🏆 Success Metrics

### **Project Success Indicators:**
1. **All team members contribute meaningfully** ke project
2. **Application works reliably** di multiple devices
3. **User feedback is positive** dari testing sessions
4. **Code quality meets standards** established in guidelines
5. **Team demonstrates learning** dari Week 1-7 concepts
6. **Documentation is comprehensive** dan helpful untuk future development

### **Individual Assessment:**
- **Contribution Quality:** Impact of individual work ke project
- **Technical Growth:** Improvement dari Week 1-7
- **Collaboration Skills:** Effectiveness dalam team setting
- **Problem Solving:** Ability to overcome challenges
- **Communication:** Clear explanation dalam presentation dan code review

---

*Selamat mengerjakan project tim! Ingat, ini adalah kesempatan untuk mengaplikasikan semua yang telah dipelajari dan mengembangkan skills collaboration yang penting untuk karir di tech industry. Focus pada learning process, bukan hanya hasil akhir. Good luck! 🚀*
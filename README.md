# 👋 Hi there, I'm Darshan!

<!-- Profile Views Counter (optional) -->
<!-- ![Profile views](https://gpvc.arturio.dev/darshanpb111) -->

## 🚀 About Me

- 👨‍💻 **Software Engineer I**
- 🌟 Passionate about building modern web applications
- 💡 Always learning and growing in the world of tech

## 🛠️ Skills

- **Languages:** JavaScript
- **Frameworks/Libraries:** React.js

## 📈 What I'm Up To

Currently focused on sharpening my frontend development skills, especially with React.js and modern JavaScript. Excited to collaborate on open-source projects and expand my portfolio!

## 🗂️ Featured Projects

> _I’m just getting started! Stay tuned for exciting projects._

<!-- You can add your top repositories here, for example: -->
<!--
- [Project Name](https://github.com/darshanpb111/project-name): Short project description
-->

## 📫 Let's Connect

<!--
- [LinkedIn](https://www.linkedin.com/in/yourprofile)
- [Twitter](https://twitter.com/yourhandle)
- [Portfolio](https://yourwebsite.com)
-->

---

_Thanks for visiting my profile!_


PI-8 Learning Week plans:

# 📱 React Native Mobile Architecture – 2-Week Learning Plan

## 🎯 Objective
Gain practical understanding of scalable architecture patterns in React Native. Learn how to structure mobile apps cleanly using best practices such as modular design, navigation flow, state management, testing, and CI/CD.

---

## 📅 Week 1: Foundations of Mobile Architecture

### ✅ Day 1: Introduction to Mobile Architecture
- Understand Clean Architecture, MVVM, MVC, and MVI
- Learn how these apply to React Native
- 📚 Watch: [React Native Clean Architecture - YouTube](https://www.youtube.com/results?search_query=react+native+clean+architecture)
- 📝 Task: Summarize Clean Architecture in your own words

---

### ✅ Day 2: Project Structure & Modularization
- Study modular folder structure (`/features`, `/core`, `/shared`, etc.)
- 📚 Read: [Modular React Native Architecture](https://medium.com/@AlexMiranda/modular-react-native-architecture-1dfc6bcf4d84)
- 🛠️ Task: Create a modular structure for a new RN project

---

### ✅ Day 3: Navigation Architecture
- Learn about React Navigation (stack, tab, drawer)
- Structure navigation for auth vs. main app flow
- 🛠️ Task: Build a tab+stack-based auth navigation flow

---

### ✅ Day 4: State Management Patterns
- Compare Context API, Redux, Zustand, and MobX
- 📚 Read: [State Management in React Native](https://blog.logrocket.com/react-native-state-management-comparison/)
- 🛠️ Task: Implement and compare Context + Reducer vs Redux

---

### ✅ Day 5: Dependency Injection & Services Layer
- Understand abstraction via services and repositories
- Optional: Explore DI libraries (`inversify`, etc.)
- 🛠️ Task: Create a `UserService` and inject it into a screen

---

### 📌 Weekend Mini-Project
Build a basic **"Notes App"** that uses:

---

## 📅 Week 2: Advanced Concepts & Real-World Applications

### ✅ Day 6: Testing Architecture
- Learn about unit tests, integration tests, and e2e tests
- Tools: Jest, React Native Testing Library
- 🛠️ Task: Write tests for one service and one UI component

---

### ✅ Day 7: Error Handling & Logging
- Create global error boundaries
- Integrate Sentry or Reactotron for logging
- 🛠️ Task: Add Sentry and handle API failure gracefully

---

### ✅ Day 8: Clean Code & Linting
- Enforce clean code practices
- Set up ESLint, Prettier, Husky, and commit hooks
- 🛠️ Task: Refactor a feature to follow clean separation of concerns

---

### ✅ Day 9: CI/CD Setup
- Learn about GitHub Actions, Expo EAS, Bitrise, Fastlane
- 🛠️ Task: Configure a GitHub Action for linting + testing on PR

---

### ✅ Day 10: UI Scalability & Theme Architecture
- Learn about theme providers and design systems
- Structure scalable UI components with props and variants
- 🛠️ Task: Build a reusable button and form input component

---

## ⚡ Second Priority (Optional/Advanced Topics)

### 📦 Offline-First Architecture (Pick any 1 day)
- Concepts: Caching strategies, offline storage, sync strategies
- Tools: `AsyncStorage`, `react-query`, SQLite
- 📚 Read:
  - [Offline Storage in React Native](https://reactnative.dev/docs/asyncstorage)
  - [Offline Sync Patterns – Firebase/REST APIs]
- 🛠️ Task: Extend your Notes App to:
  - Cache notes locally with AsyncStorage or SQLite
  - Show offline/online UI indicator

---

### 🧪 Optional: E2E Testing with Detox
- Setup Detox or Appium for device testing
- 🛠️ Task: Write 1 flow test: “create → edit → delete note”

---

### 🚀 Final Weekend Capstone
Extend your **Notes App** to include:
- ✅ Modular architecture
- ✅ Clean separation of presentation/domain/data
- ✅ Global error handling & logging
- ✅ Linting, testing, CI on PRs
- ✅ (Optional) Offline-first logic
- ✅ (Optional) Theme and design system setup

---

## 📚 Recommended Resources

### 📘 Articles
- [React Native Clean Architecture](https://medium.com/@leandromarino/react-native-clean-architecture-87c1780e2443)
- [MVVM in React Native](https://dev.to/abdulbasit313/mvvm-architecture-pattern-in-react-native-23in)
- [State Management Guide](https://blog.logrocket.com/react-native-state-management-comparison/)

### 📺 Videos
- Academind – *React Native Architecture Best Practices*
- Fireship – *Clean Code Tips in React*

### 📦 GitHub Boilerplates
- [TheCodingMachine/react-native-boilerplate](https://github.com/thecodingmachine/react-native-boilerplate)
- [InfiniteRed/ignite](https://github.com/infinitered/ignite)


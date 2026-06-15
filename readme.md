# Hi there! I'm Hromas 👋

I am a Frontend Platform Engineer with a focus on building scalable web and mobile platforms, designing clean architectures, and modernizing legacy codebases.

For me, engineering isn't just about writing code; it's about making life easier for other developers on the team while keeping the application fast, maintainable, and stable for end-users. I enjoy untangling complex systems, identifying performance bottlenecks, and automating repetitive tasks so we can focus on building features.

---

### 💡 What I Enjoy Doing Most

- **Smooth Migrations:** Transitioning legacy setups (like PHP/jQuery monoliths) to modern frameworks step-by-step, without breaking existing user flows.
- **Developer Experience (DX):** Streamlining CI/CD pipelines, writing scripts to automate boilerplate, and keeping configurations clean so developers can ship code with confidence.
- **Complex UI Challenges:** Building heavy, interactive interfaces—like dynamic graphs, data-rich tables, and real-time workspaces—and keeping them responsive under heavy load.
- **Code Sanitation:** Frankly, I find peace in deleting dead code. There is nothing quite like cleaning up thousands of lines of unused files to make a project run lighter.

---

### 🛠 My Toolbox

Here are the tools and technologies I work with most often:

*   **Web Ecosystem:** Next.js 15 (App Router, RSC, Server Actions, Turbopack), React, TypeScript (strictly configured)
*   **Mobile Development:** React Native, Expo (Router, Prebuild, Config Plugins, Reanimated)
*   **State & Data Fetching:** Zustand (with Immer), Redux Toolkit, TanStack Query (React Query), WebSockets
*   **Architecture & Design:** Feature-Sliced Design (FSD), Tailwind CSS, Responsive & Accessible Themes
*   **DevOps & Automation:** Fastlane, Semantic Release, Expo Updates (OTA), Docker (Multi-stage), Vitest, Jest
*   **Code Quality:** ESLint, Prettier, Husky, Knip

---

### 📁 A Look at Some of My Work (Commercial & NDA)

*Since much of my production work is proprietary, here is a summary of the architectural challenges I've solved:*

#### 🔄 Easing the Transition from Legacy to Next.js
I helped migrate a large-scale PHP legacy monolith (based on Blade templates) to Next.js 15 (App Router). Instead of a risky "rewrite-everything-at-once" approach, we used Nginx route proxying and kept sessions synchronized via NextAuth so users didn't notice any disruption. To keep our code organized as the team grew, I introduced Feature-Sliced Design (FSD) and wrote custom CLI scripts to prevent circular dependencies.

#### 📱 Modernizing the Mobile Stack
Our mobile app was built on a bare React Native setup that required painful manual maintenance of native Android and iOS folders. I led the transition to Expo (using Prebuild and Expo Router). I also optimized the rendering of large lists and moved local caching to `react-native-mmkv` to eliminate interface lag.

#### 📊 Solving UI Performance Bottlenecks
I love tackling complex visual challenges. I built an interactive, dynamic organization chart using React Flow and the ELK.js layout engine. The main challenge was ensuring that calculating layouts for thousands of interconnected nodes didn't freeze the browser. By optimizing rendering cycles and handling DOM measurements efficiently, we kept the experience highly responsive (60 FPS on heavy interactions).

#### 🧹 Keeping Codebases Clean and Test Suites Fast
I migrated our main test runner from Jest to Vitest, which brought down local test times and sped up our CI pipelines. I also ran a full-project audit using Knip, which helped us identify and delete over 16,300 lines of dead code and unused dependencies that were quietly slowing down our build times.

---

### 🚀 Side Projects & Indie Hacking

- **BridgeCloud (2024):** A custom cloud storage platform built with Node.js, Express, and MongoDB. The fun part: I used the VK API as an **unlimited backend storage engine**. I spent quite a bit of time optimizing multi-part file uploads (using Multer and concurrent streams) to prevent memory leaks and keep resource usage low on the server.

# Retro OS Interactive Portfolio

A nostalgic, interactive portfolio built with **Next.js**, designed to mimic a classic desktop operating system. It features draggable windows, a functional taskbar, a Start menu, and AI-powered insights using **Google Genkit**.

## ✨ Features

- **Retro Desktop UI**: A fully functional desktop environment with icons, a taskbar, and a Start menu.
- **Window Management**: Draggable, resizable, minimizable, and maximizable windows for displaying projects and information.
- **AI Recommends (Genkit Integration)**: An integrated AI feature built with Google Genkit that provides insights and interactive suggestions.
- **Dynamic Content**: Uses a structured data model to easily add or update projects, categories, and about-me information.
- **Modern Tech Stack**: Despite the retro look, it's powered by modern tools like Next.js 15, React 18, and Tailwind CSS.

## 🛠️ Tech Stack

- **Framework**: Next.js (App Router)
- **UI & Styling**: Tailwind CSS, Radix UI Primitives
- **State Management**: React Hooks
- **AI Integration**: `@genkit-ai/googleai`, `@genkit-ai/next`
- **Animations**: Framer Motion

## 📂 Project Structure

```text
src/
├── ai/                 # Genkit AI setup and configuration
├── app/                # Next.js App Router (Pages, Layouts)
│   ├── ai-recommends/  # AI Insight functionality route
│   └── page.tsx        # Main Desktop OS Interface
├── components/         # Reusable UI components
│   ├── retro-ui/       # Specific retro components (Taskbar, Windows, Start Menu)
│   └── ui/             # Generic UI components (Radix/shadcn based)
├── constants/          # Configuration and data (Projects list, Desktop items)
└── hooks/              # Custom React hooks
```

## 🚀 Getting Started

1. **Clone the repository**:
   ```bash
   git clone https://github.com/yovyshh/test01.git
   cd test01
   ```

2. **Install dependencies**:
   ```bash
   npm install
   ```

3. **Set up Environment Variables**:
   Ensure you have your `.env` configured for any API keys required by the AI integrations.

4. **Run the development server**:
   ```bash
   npm run dev
   ```

5. **Open your browser**:
   Navigate to `http://localhost:9002` to experience the retro OS portfolio.

## 🤖 AI Development (Genkit)

To run the Genkit developer UI and test your AI flows locally:

```bash
npm run genkit:dev
# or for watch mode
npm run genkit:watch
```

## 📝 License
This project is open-source. Feel free to use it as inspiration for your own portfolio!

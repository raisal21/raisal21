<h1 align="center">Raisal Ahmad</h1>

<p align="center">Full-stack software engineer. Mostly real-time, data-heavy things.</p>

<p align="center">
  Yogyakarta, Indonesia · open to work, remote or on-site
</p>

<p align="center">
  <a href="mailto:raisal.ahmad.dev@gmail.com">Email</a> ·
  <a href="https://linkedin.com/in/raisal-ahmad">LinkedIn</a> ·
  <a href="https://raisalahmad.dev">Website</a>
</p>

---

I work across the stack, React and TypeScript on the front, .NET 9 and Node on the back. The thread through most of my work is live data: dashboards, telemetry servers, and computer-vision tools that keep up with readings coming in several times a second. A lot of it came from drilling and geothermal field systems, but the hard parts (backpressure, reconnects, streaming without the stutter) show up anywhere data arrives in real time.

### Stack

![TypeScript](https://img.shields.io/badge/TypeScript-1c1b19?style=flat-square&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-1c1b19?style=flat-square&logo=javascript&logoColor=white)
![Python](https://img.shields.io/badge/Python-1c1b19?style=flat-square&logo=python&logoColor=white)
![C#](https://img.shields.io/badge/C%23-1c1b19?style=flat-square&logo=dotnet&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-1c1b19?style=flat-square&logo=postgresql&logoColor=white)

![React](https://img.shields.io/badge/React-1c1b19?style=flat-square&logo=react&logoColor=white)
![Next.js](https://img.shields.io/badge/Next.js-1c1b19?style=flat-square&logo=nextdotjs&logoColor=white)
![Tailwind](https://img.shields.io/badge/Tailwind-1c1b19?style=flat-square&logo=tailwindcss&logoColor=white)
![.NET](https://img.shields.io/badge/.NET%209-1c1b19?style=flat-square&logo=dotnet&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-1c1b19?style=flat-square&logo=nodedotjs&logoColor=white)

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-1c1b19?style=flat-square&logo=postgresql&logoColor=white)
![QuestDB](https://img.shields.io/badge/QuestDB-1c1b19?style=flat-square&logo=questdb&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-1c1b19?style=flat-square&logo=docker&logoColor=white)
![OpenCV](https://img.shields.io/badge/OpenCV-1c1b19?style=flat-square&logo=opencv&logoColor=white)
![FFmpeg](https://img.shields.io/badge/FFmpeg-1c1b19?style=flat-square&logo=ffmpeg&logoColor=white)

### Selected work

**RTDC** · React 19 · TypeScript · WebSocket · ECharts · MapLibre GL
A control-room dashboard for live drilling data. Reads binary sensor frames at 10 Hz over a WebSocket and shows them as log charts, live gauges, and a map you can click into. The layout changes by role, and it reconnects on its own when the link drops.

**WITSML Telemetry Server** · .NET 9 · ASP.NET Core · C# · WebSocket · QuestDB
The backend for that dashboard. A WebSocket server that broadcasts rig telemetry at 10 Hz and stores every reading in QuestDB. The write path sits behind a bounded queue, so a slow database doesn't stall the live stream. It pings clients to check they're alive, drops the ones that fall behind, and refuses any connection without a valid token. History is pre-summarised per zoom level but keeps the min and max, so a spike like H2S doesn't get averaged out.

**EyeLog** · Python · OpenCV · PySide6 (Qt) · RTSP · Nuitka
A computer-vision app that watches industrial camera feeds and measures coverage in real time. Handles three 1080p streams at 25 FPS on one machine with under 0.01% frame loss, around 85% F1 using classical CV (background subtraction plus morphology). Runs fully offline. It started as my thesis; a web version shipped to a client during my internship.

### GitHub

<p>
  <img height="165" src="https://github-readme-stats.vercel.app/api?username=raisal21&show_icons=true&hide_border=true&title_color=b23a2e&icon_color=a4560f&text_color=1c1b19&bg_color=fcfcfb" alt="GitHub stats" />
  <img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=raisal21&layout=compact&hide_border=true&title_color=b23a2e&text_color=1c1b19&bg_color=fcfcfb" alt="Top languages" />
</p>

### Background

Applied bachelor (D4) in Internet Engineering Technology, Universitas Gadjah Mada. GPA 3.79 / 4.00.
CCNA, Huawei HCIA (Cloud, AI), MTCNA, IELTS Band 6. PKM-RSH national research grant recipient.

### Привет! Я Артем - Junior Penetration Tester 🛡️

Целенаправленно иду в Offensive Security / Pentest. 2+ года в ИБ и сетевой
инфраструктуре (Газпром нефть, Ростелеком): контроль стандартов ИБ, аудит прав
доступа, обработка инцидентов, диагностика TCP/IP. Практикуюсь в пентесте
веб-приложений и API - от разведки и SSTI до OAuth-конфигураций.

Пишу инструменты на Python, разбираюсь в Linux и сетях, умею доводить находки
до воспроизводимого PoC и отчёта с CWE и РоС. Дополнительно - fullstack-разработка:
понимаю, как атакуемые приложения устроены изнутри, и умею писать безопасный код.

---

### 🎯 Фокус: Penetration Testing / Red Team

- **Web & API:** OWASP Top 10, SSTI (→ RCE), OAuth/OIDC (DCR, PKCE), Burp Suite
- **Recon:** Nmap, masscan, ffuf, ручная разведка
- **Трафик и сети:** Wireshark, TCP/IP, DNS, VPN, межсетевые экраны
- **Linux:** терминал, права доступа, диагностика, hardening
- **Автоматизация:** Python (сокеты, потоки, парсинг логов), SQL
- **Защита:** SIEM, обработка инцидентов, аудит прав доступа, СЗИ

---

### 🧪 Практика в пентесте

**PointPulse** - тестирование веб-приложений и API методом black-box:
- Подтвердил **Server-Side Template Injection** с эскалацией до **RCE**
- Нашёл уязвимость конфигурации OAuth-провайдера: открытая **Dynamic Client
  Registration**, небезопасный **PKCE method=plain**, повышение привилегий
  через смену scope
- Оформляю отчёты по black-box методологии с указанием **CWE** и **РоС**

**TryHackMe** - [профиль](https://tryhackme.com/p/apoliakov320)

---

### 🛠 Стек

**Offensive / InfoSec:**
![Burp Suite](https://img.shields.io/badge/Burp_Suite-FF6633?style=for-the-badge&logo=burpsuite&logoColor=white)
![Kali Linux](https://img.shields.io/badge/Kali_Linux-557C94?style=for-the-badge&logo=kalilinux&logoColor=white)
![Wireshark](https://img.shields.io/badge/Wireshark-1679A7?style=for-the-badge&logo=wireshark&logoColor=white)
![Nmap](https://img.shields.io/badge/Nmap-4682B4?style=for-the-badge)
![OWASP](https://img.shields.io/badge/OWASP_Top_10-000000?style=for-the-badge&logo=owasp&logoColor=white)

**Системы и сети:**
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)
![TCP/IP](https://img.shields.io/badge/TCP%2FIP_%7C_DNS_%7C_VPN-2B5B84?style=for-the-badge)

**Backend / автоматизация:**
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=postgresql&logoColor=white)

**Frontend (понимаю атакуемую поверхность изнутри):**
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=vite&logoColor=white)
![Cloudflare](https://img.shields.io/badge/Cloudflare-F38020?style=for-the-badge&logo=Cloudflare&logoColor=white)

**Инструменты:**
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![TryHackMe](https://img.shields.io/badge/TryHackMe-212C42?style=for-the-badge&logo=tryhackme&logoColor=white)

---

### 🚀 Проекты

- **[security-scripts](https://github.com/apoliakov320/security-scripts)** - инструменты на Python (только stdlib)
    - `port_scanner.py` - многопоточный TCP connect-сканер с определением сервисов и баннеров
    - `auth_log_analyzer.py` - анализ SSH `auth.log`: рейтинг неудачных входов по IP/логину, флаг успешного входа с подозрительного IP
    - *Фокус: сокеты, потоки, разбор логов, выявление IoC*

- **[inastralium](https://github.com/apoliakov320/inastralium)** - fullstack-платформа с ИИ
    - *Vite, Vanilla JS, Tailwind, Handlebars, Cloudflare Pages & Functions, Groq API*
    - Безопасный бэкенд (ключи не утекают на клиент), приватность (`sessionStorage`),
      A11y (`focus trap`), отказоустойчивость (скелетоны, fallback)
    - 🌐 [inastralium.pages.dev](https://inastralium.pages.dev/)

- **[basilico](https://github.com/apoliakov320/basilico)** - лендинг fine dining
    - *Vite, Vanilla JS, Tailwind, Handlebars, Cloudflare Pages & Functions, Telegram Bot API*
    - Безопасная отправка заявок (токены скрыты), строгая валидация формы,
      `IntersectionObserver`, mobile-first
    - 🌐 [basilico.pages.dev](https://basilico.pages.dev/)

---

### 📫 Контакты

- Telegram: [@poliakov_websec](https://t.me/poliakov_websec)
- Email: a.poliakov320@gmail.com
- GitHub: [apoliakov320](https://github.com/apoliakov320)

---

### 📈 GitHub

<p align="center">
  <img src="https://streak-stats.demolab.com/?user=apoliakov320&theme=radical" alt="GitHub Streak" />
</p>

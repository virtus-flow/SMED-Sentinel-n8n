# 🛡️ SMED Sentinel - Industrial Automation

## 🇷🇸 Опис пројекта
Аутоматизовани систем за надзор промене алата (SMED) изграђен у **n8n**. 
Систем спречава "информационе рупе" у производњи тако што прати реално време застоја 
и ескалира кашњења директно на Telegram.

### Кључне функције:
- **Асинхроно праћење:** Webhook-базиран на старт/стоп систему.
- **Паметни чувар** Аутоматски тајмер од 30 минута са детекцијом кашњења.
- **Аналитика трајања:** Математички прорачун трајања у минутима.

---

## 🇺🇸 Project Description
An automated SMED downtime monitoring system engineered with **n8n**. 
This solution eliminates production "black holes" by tracking real-time changeover 
durations and escalating delays via Telegram alerts.

### Key Features:
- **Asynchronous Tracking:** Webhook-based start/stop logic.
- **Smart Watchdog:** 30-minute automated timer with delay detection.
- **Automated Analytics:** Precise duration calculation (End - Start).

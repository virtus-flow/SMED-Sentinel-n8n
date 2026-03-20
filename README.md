# 🛡️ SMED Sentinel - Industrial Automation

## 🇷🇸 Опис пројекта
Аутоматизовани систем за надзор промене алата (SMED) изграђен у **n8n**. 
Систем спречава "информационе рупе" у производњи тако што прати реално време застоја 
и ескалира кашњења директно на Telegram.

### Кључне функције:
- **Асинхроно праћење:** Webhook-базиран на старт/стоп систему.
- **Паметни чувар** Аутоматски тајмер од 30 минута са детекцијом кашњења.
- **Аналитика трајања:** Математички прорачун трајања у минутима.

### ROI Анализа (Повраћај инвестиције):
- **Смањење застоја (Директна уштеда):** Сваки минут који машина стоји изван SMED лимита кошта фабрику од 50€ до 500€. Сентинел алармира менаџмент у секунди пробијања рока, смањујући време реакције за 30-50%.
- **Интегритет података (Скривена вредност):** Ручни записи су често „фризирани”. Сентинел пружа 100% тачне податке са временским жигом, откривајући стварна „уска грла” која су до сада била невидљива.
- **Оптимизација менаџмента:** Руководиоци штеде до 1 сат дневно јер не морају ручно да проверавају статус линија или контролишу папирне извештаје.

---

## 🇺🇸 Project Description
An automated SMED downtime monitoring system engineered with **n8n**. 
This solution eliminates production "black holes" by tracking real-time changeover 
durations and escalating delays via Telegram alerts.

### Key Features:
- **Asynchronous Tracking:** Webhook-based start/stop logic.
- **Smart Watchdog:** 30-minute automated timer with delay detection.
- **Automated Analytics:** Precise duration calculation (End - Start).

### Financial ROI Breakdown:
- **Downtime Reduction (Direct Savings):** Every minute a machine stands idle beyond the SMED limit costs between €50 and €500 (depending on the industry). By triggering real-time Telegram alerts, the system reduces response time by 30-50%.
- **Data Integrity (Indirect Savings):** Manual logs are prone to "buffer padding" (operators reporting shorter downtimes). Sentinel provides 100% accurate, timestamped data, revealing the true hidden bottlenecks.
- **Management Efficiency:** Supervisors save up to 1 hour/day by not having to manually check line status or verify paper logs.

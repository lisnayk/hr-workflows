# Аналіз бізнес-процесів та потоків даних відділу кадрів Університету

Цей проект містить аналіз поточних бізнес-процесів відділу кадрів університету та вимоги до їх інтеграції в CRM/ERP систему **ISPRO 8**.

## Основні потоки даних (Data Flows)

Нижче наведено перелік основних потоків даних, які підлягають автоматизації та інтеграції з ISPRO 8:

1.  [**Прийом на роботу (Onboarding)**](processes/onboarding/requirements.md) — від подання заяви до створення особової картки в ISPRO 8.
2.  [**Облік робочого часу та відпусток (Leave Management)**](processes/leave-management/requirements.md) — графіки роботи, табелювання, накази на відпустки.
3.  [**Звільнення працівників (Offboarding)**](processes/offboarding/requirements.md) — обхідні листи, накази на звільнення, передача справ.
4.  [**Підвищення кваліфікації та атестація**](processes/professional-development/requirements.md) — моніторинг термінів, сертифікати, зміна категорій.
5.  [**Інтеграція з бухгалтерією (Salary Sync)**](processes/salary-integration/requirements.md) — передача даних для нарахування заробітної плати та премій.

## Структура проекту

*   [`processes/onboarding/`](processes/onboarding/requirements.md) — технічні та функціональні вимоги до процесу прийому.
*   [`processes/leave-management/`](processes/leave-management/requirements.md) — вимоги до обліку відпусток та табелювання.
*   [`processes/offboarding/`](processes/offboarding/requirements.md) — вимоги до процесу звільнення.
*   [`processes/professional-development/`](processes/professional-development/requirements.md) — моніторинг атестацій та сертифікатів.
*   [`processes/salary-integration/`](processes/salary-integration/requirements.md) — опис взаємодії з фінансовим блоком ISPRO 8.

## Технологічний стек (для документації)

*   **Діаграми:** Mermaid syntax.
*   **Інтеграційна платформа:** ISPRO 8 HRM API / Import tools.

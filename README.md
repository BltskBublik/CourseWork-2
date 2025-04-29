# Hydroponic Calculator

**Android-приложение** для расчёта необходимого количества удобрений для различных растений, выращиваемых гидропонным методом.

## Описание проекта

Hydroponic Calculator позволяет:
- Выбрать растение (например, базилик, петрушка, листовой салат),
- Указать стадию роста (вегетация, цветение, плодоношение),
- Ввести объём раствора (в литрах),
- Получить расчёт количества основных элементов питания: азота (N), фосфора (P), калия (K).

Приложение разработано с использованием **Kotlin** и **Jetpack Compose** в Android Studio.

## Основной функционал

- Выбор растения из списка.
- Выбор стадии роста растения.
- Ввод объема раствора.
- Автоматический расчёт необходимого количества удобрений.
- Отображение результатов в удобочитаемом формате.

## Стек технологий

- **Язык программирования:** Kotlin
- **Интерфейс:** Jetpack Compose (Material 3)
- **Минимальная версия Android:** 8.0 (API 26)
- **Среда разработки:** Android Studio
- **Библиотеки:** Material3, Compose UI

## Установка

1. Склонируйте проект или загрузите APK-файл.
2. При необходимости разрешите установку приложений из неизвестных источников на устройстве.
3. Установите приложение и запустите его.

## Использование

1. Выберите растение из выпадающего списка.
2. Выберите стадию роста растения.
3. Введите желаемый объём питательного раствора.
4. Ознакомьтесь с рассчитанными пропорциями азота, фосфора и калия.

## Структура проекта

- `MainActivity.kt` — основной экран приложения, где размещены элементы интерфейса.
- `DropdownMenuBox.kt` — компонент для выбора растения и стадии роста через выпадающие списки.
- Логика расчётов встроена в `HydroponicApp()`.

## Лицензия

---

# Hydroponic Calculator

**Android application** for calculating the required amount of fertilizers for various plants grown using the hydroponic method.

## Project Description

Hydroponic Calculator allows you to:
- Select a plant (e.g., basil, parsley, lettuce),
- Specify the growth stage (vegetation, flowering, fruiting),
- Enter the solution volume (in liters),
- Obtain the calculated amounts of key nutrients: nitrogen (N), phosphorus (P), and potassium (K).

The application is developed using **Kotlin** and **Jetpack Compose** in Android Studio.

## Main Features

- Select a plant from a dropdown list.
- Select the plant's growth stage.
- Input the solution volume.
- Automatically calculate the required amount of fertilizers.
- Display results in an easy-to-read format.

## Technology Stack

- **Programming language:** Kotlin
- **Interface:** Jetpack Compose (Material 3)
- **Minimum Android version:** 8.0 (API 26)
- **Development environment:** Android Studio
- **Libraries:** Material3, Compose UI

## Installation

1. Clone the project or download the APK file.
2. If necessary, allow installation from unknown sources on your device.
3. Install the application and launch it.

## Usage

1. Select a plant from the dropdown menu.
2. Select the plant's growth stage.
3. Enter the desired solution volume.
4. View the calculated proportions of nitrogen, phosphorus, and potassium.

## Project Structure

- `MainActivity.kt` — the main screen of the application, containing the user interface elements.
- `DropdownMenuBox.kt` — a component for selecting plants and growth stages through dropdown menus.
- The calculation logic is embedded within `HydroponicApp()`.

## License

This project was developed as part of a coursework project at the National Research University Higher School of Economics (HSE University), Faculty of Computer Science.

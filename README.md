
[![CI Status](https://github.com/Sanyainthenorth/java-project-71/actions/workflows/ci.yml/badge.svg)](https://github.com/Sanyainthenorth/java-project-71/actions)
[![SonarQube Coverage](https://sonarcloud.io/api/project_badges/measure?project=Sanyainthenorth_java-project-71&metric=coverage)](https://sonarcloud.io/summary/new_code?id=Sanyainthenorth_java-project-71)
[![Codacy Badge](https://app.codacy.com/project/badge/Grade/7c963ae284764e4e8d4471fad893629b)](https://app.codacy.com/gh/Sanyainthenorth/java-project-71/dashboard?utm_source=gh&utm_medium=referral&utm_content=&utm_campaign=Badge_grade)

Утилита для сравнения структур данных в различных форматах с поддержкой разных форматов вывода.

## 📋 О проекте

Diff-Calculator — это программа, определяющая разницу между двумя структурами данных. Подобные утилиты используются для сравнения конфигурационных файлов, отслеживания изменений и вывода различий в тестах.

### 🎯 Цели проекта

- Освоение работы с коллекциями и сложными структурами данных
- Практика построения и обхода древовидных структур
- Работа с различными форматами данных (JSON, YAML)
- Разработка через тестирование (TDD) с использованием JUnit
- Настройка непрерывной интеграции и элементов экстремального программирования

## 🚀 Технологии

- **Language**: Java
- **Testing**: JUnit
- **Formats**: JSON, YAML
- **Build Tool**: Gradle
- **CI/CD**: GitHub Actions
- **Code Quality**: SonarCloud, Codacy

## 📊 Ключевые функции

### 📁 Поддержка форматов
- Чтение и парсинг **JSON** и **YAML** файлов
- Сравнение структур данных из разных источников

### 📊 Форматы вывода
- **Plain text** - простой текстовый формат
- **Stylish** - удобное для чтение форматирование
- **JSON** - машинно-читаемый вывод

### 🔍 Алгоритмы сравнения
- Построение дерева различий между структурами
- Определение добавленных, удаленных и измененных элементов
- Рекурсивное сравнение вложенных структур

## 🛠️ Использование

```bash
# Сравнение двух JSON файлов
./build/install/app/bin/app file1.json file2.json

# Сравнение с указанием формата вывода
./build/install/app/bin/app file1.json file2.json --format stylish

# Сравнение YAML файлов
./build/install/app/bin/app file1.yml file2.yml --format json

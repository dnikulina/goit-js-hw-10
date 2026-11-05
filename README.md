# Countdown Timer & Promise Generator

![JavaScript](https://img.shields.io/badge/JavaScript-ES6-yellow?style=flat-square&logo=javascript&logoColor=black)
![Vite](https://img.shields.io/badge/Vite-Build%20Tool-purple?style=flat-square&logo=vite&logoColor=white)
![Flatpickr](https://img.shields.io/badge/Flatpickr-Date%20Picker-lightgrey?style=flat-square)
![iziToast](https://img.shields.io/badge/iziToast-Notifications-green?style=flat-square)

## Overview

This project contains two asynchronous JavaScript exercises built with Vite: a countdown timer and a configurable Promise generator.

## Tech Stack

- JavaScript
- HTML
- CSS
- Vite
- Flatpickr
- iziToast
- Git & GitHub

## Features

### Countdown Timer

- lets the user select a future date and time with Flatpickr;
- prevents starting the timer with an invalid past date;
- calculates remaining days, hours, minutes, and seconds;
- updates the countdown every second;
- displays validation messages with iziToast.

### Promise Generator

- accepts a delay and Promise state from a form;
- creates a Promise that resolves or rejects after the selected delay;
- handles results with `.then()` and `.catch()`;
- displays success and error notifications with iziToast.

## Running Locally

```bash
npm install
npm run dev
```

## Live Demo

[Open GitHub Pages](https://dashakim2209.github.io/goit-js-hw-10/)

## Learning Outcomes

- asynchronous JavaScript;
- Promises;
- timers with `setInterval` and `setTimeout`;
- date calculations;
- form handling;
- integration of third-party libraries.

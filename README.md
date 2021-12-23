# Assignment 1: Website Revamp

![amCharts](https://img.shields.io/badge/amCharts-brightgreen?color=gray&logo=data:image/png;base64,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) ![chartJS](https://img.shields.io/badge/Chart.js-brightgreen?logo=chart.js&color=grey) [![Open in Visual Studio Code](https://open.vscode.dev/badges/open-in-vscode.svg)](https://open.vscode.dev/github.com/nakson/nakson-one-page.github.io)

This Project is to **revamp the following website**: https://eo.hkbu.edu.hk/ssq-home/


## One-Page Website

Using the **responsive grid system** and **styling** from the **Bulma** CSS library.

Data visualizations with **Chart.js** or **amCharts**.

Applying the **one-page website** design.

> ***A One Pager** is a **Single Page website** with no additional pages like About, Team or Services. All the content sits within the same webpage, traditionally in a **long-scrolling layout**. See the beauty of a One Page website is it tries to **promote one thing in an uncluttered, direct manner**.*

- Reference: https://onepagelove.com/what-is-a-one-page-website

The **theme** was based on [Free Bulma Templates](https://bulmatemplates.github.io/bulma-templates/)

- Using [AOS](https://michalsnik.github.io/aos/) (Animate On Scroll Library) for fade in effects.


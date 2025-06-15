---
title: How to install package
description: How to install package
github: https://github.com/zaimea/charts-docs/edit/main/
---

# Charts

[[TOC]]

## Instalation

```json
"repositories": [
        {
            "type": "vcs",
            "url": "https://github.com/zaimealabs/charts"
        }
    ]
```

```bash
composer require zaimealabs/charts
```

```bash
php artisan vendor:publish --tag=charts-config
```

```bash
php artisan vendor:publish --tag=charts-apexcharts-script
```

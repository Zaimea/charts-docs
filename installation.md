---
title: How to install package
description: How to install package
---

# Installation
- [install](#install)

<a name="install"></a>
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

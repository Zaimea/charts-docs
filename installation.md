---
title: How to install package
description: How to install package
github: https://github.com/zaimea/charts-docs/edit/main/
sections: 
    install : 'Install'
---

<a name="installation"></a>
# Installation
- [Install](#install)

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

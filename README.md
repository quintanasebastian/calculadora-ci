# Calculadora CI - Parcial 2

Proyecto de calculadora con pruebas unitarias automatizadas y pipeline de Integración Continua con GitHub Actions.

## Integrantes
- Sebastian Quintana Bonilla
- Brayan Yair Molina

## Estado del Pipeline

[![PHP Continuous Integration](https://github.com/quintanasebastian/calculadora-ci/actions/workflows/php-ci.yml/badge.svg)](https://github.com/quintanasebastian/calculadora-ci/actions/workflows/php-ci.yml)

## Tecnologías
- PHP 8.2
- PHPUnit 10
- GitHub Actions (CI)

## Cómo ejecutar las pruebas localmente

```bash
composer install
./vendor/bin/phpunit tests
```
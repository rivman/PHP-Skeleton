# PHP __Package__ library

[![Latest Stable Version](https://poser.pugx.org/__vendor__/__PREFIX____Package__/v/stable)](https://packagist.org/packages/__vendor__/__PREFIX____Package__) [![Latest Unstable Version](https://poser.pugx.org/__vendor__/__PREFIX____Package__/v/unstable)](https://packagist.org/packages/__vendor__/__PREFIX____Package__) [![License](https://poser.pugx.org/__vendor__/__PREFIX____Package__/license)](LICENSE) [![Codacy Badge](https://www.codacy.com/project/badge/00000000000000000000000000000000)](https://www.codacy.com/app/__Vendor__/__PREFIX____Package__) [![Total Downloads](https://poser.pugx.org/__vendor__/__PREFIX____Package__/downloads)](https://packagist.org/packages/__vendor__/__Vendor__) [![Travis](https://travis-ci.org/__Vendor__/__PREFIX____Package__.svg)](https://travis-ci.org/__Vendor__/__PREFIX____Package__) [![PSR2](https://img.shields.io/badge/PSR-2-1abc9c.svg)](http://www.php-fig.org/psr/psr-2/) [![PSR4](https://img.shields.io/badge/PSR-4-9b59b6.svg)](http://www.php-fig.org/psr/psr-4/) [![CodeCov](https://codecov.io/gh/__Vendor__/__PREFIX____Package__/branch/master/graph/badge.svg)](https://codecov.io/gh/__Vendor__/__PREFIX____Package__)

[English version](README.md)

Descripción.

---

- [Requisitos](#requisitos)
- [Instalación](#instalación)
- [Métodos disponibles](#métodos-disponibles)
- [Cómo empezar](#cómo-empezar)
- [Uso](#uso)
- [Tests](#tests)
- [Tareas pendientes](#-tareas-pendientes)
- [Contribuir](#contribuir)
- [Repositorio](#repositorio)
- [Licencia](#licencia)
- [Copyright](#copyright)

---

## Requisitos

Esta biblioteca es soportada por versiones de **PHP 5.6** o superiores y es compatible con versiones de **HHVM 3.0** o superiores.

## Instalación 

La mejor forma de instalar esta extensión es a través de [Composer](http://getcomposer.org/download/).

Para instalar **PHP __Package__ library**, simplemente escribe:

    $ composer require __Vendor__/__Package__

El comando anterior sólo instalará los archivos necesarios, si prefieres **descargar todo el código fuente** puedes utilizar:

    $ composer require __Vendor__/__Package__ --prefer-source

También puedes **clonar el repositorio** completo con Git:

	$ git clone https://github.com/__Vendor__/__PREFIX____Package__.git

O **instalarlo manualmente**:

[Descargar __Vendor__.php](https://raw.githubusercontent.com/__Vendor__/__PREFIX____Package__/master/src/__Package__.php):

    $ wget https://raw.githubusercontent.com/__Vendor__/__PREFIX____Package__/master/src/__Package__.php

## Métodos disponibles

### - Descripción:

```php
__Package__::sample($attr);
```

| Atributo | Descripción | Tipo | Requerido | Predeterminado
| --- | --- | --- | --- | --- |
| $attr | Descripción. | [TIPO DE DATO] | [Sí/No] | [] |

**# Return** (string) → Descripción.

## Cómo empezar

Para utilizar esta biblioteca con **Composer**:

```php
require __DIR__ . '/vendor/autoload.php';

use __Vendor__\__Package__\__Package__;
```

Si la instalaste **manualmente**, utiliza:

```php
require_once __DIR__ . '/__Package__.php';

use __Vendor__\__Package__\__Package__;
```

## Uso

Ejemplo de uso para esta biblioteca:

### - Descripción:

```php
```

## Tests 

Para ejecutar las [pruebas](tests) necesitarás [Composer](http://getcomposer.org/download/) y seguir los siguientes pasos:

    $ git clone https://github.com/__Vendor__/__PREFIX____Package__.git
    
    $ cd __PREFIX____Package__

    $ composer install

Ejecutar pruebas unitarias con [PHPUnit](https://phpunit.de/):

    $ composer phpunit

Ejecutar pruebas de estándares de código [PSR2](http://www.php-fig.org/psr/psr-2/) con [PHPCS](https://github.com/squizlabs/PHP_CodeSniffer):

    $ composer phpcs

Ejecutar pruebas con [PHP Mess Detector](https://phpmd.org/) para detectar inconsistencias en el estilo de codificación:

    $ composer phpmd

Ejecutar todas las pruebas anteriores:

    $ composer tests

## ☑ Tareas pendientes

- [ ] Añadir nueva funcionalidad.
- [ ] Mejorar pruebas.
- [ ] Mejorar documentación.
- [ ] Refactorizar código para las reglas de estilo de código deshabilitadas. Ver [phpmd.xml](phpmd.xml) y [.php_cs.dist](.php_cs.dist).

## Contribuir

Si deseas colaborar, puedes echar un vistazo a la lista de
[issues](https://github.com/__Vendor__/__PREFIX____Package__/issues) o [tareas pendientes](#-tareas-pendientes).

**Pull requests**

* [Fork and clone](https://help.github.com/articles/fork-a-repo).
* Ejecuta el comando `composer install` para instalar dependencias.
  Esto también instalará las [dependencias de desarrollo](https://getcomposer.org/doc/03-cli.md#install).
* Ejecuta el comando `composer fix` para estandarizar el código.
* Ejecuta las [pruebas](#tests).
* Crea una nueva rama (**branch**), **commit**, **push** y envíame un
  [pull request](https://help.github.com/articles/using-pull-requests).

**¡Gracias a quienes ya habéis contribuido a este proyecto!**

[<img alt="Josantonius" src="https://avatars3.githubusercontent.com/u/18104336?s=460&v=4" height="117" width="117">](https://github.com/Josantonius) |
:---:|
[Josantonius](https://github.com/Josantonius)|

## Repositorio

La estructura de archivos de este repositorio se creó con [PHP-Skeleton](https://github.com/Josantonius/PHP-Skeleton).

## Licencia

Este proyecto está licenciado bajo **licencia MIT**. Consulta el archivo [LICENSE](LICENSE) para más información.

## Copyright

__year__ __Name__, [__name__.com](https://__name__.com/)

Si te ha resultado útil, házmelo saber :wink:

Puedes contactarme en [Twitter](https://twitter.com/__Name__) o a través de mi [correo electrónico](mailto:__email__).
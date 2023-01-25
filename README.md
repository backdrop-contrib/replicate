# Replicate

Provides an API to duplicate / clone an entity.

Replicate provides a main cloning function, along with several hooks to control
exactly how a field or entity is duplicated based on its type, add info after
cloning, and supports custom fields and entities. It is intended to developers
and does not contain any GUI (a dedicated module is available).

The goal is to provide a way to easily clone any entity, and to allow
developers to be able to control exactly how entities are replicated, based
on their type or the fields they contain, and to be able to easily extend the
replication control to custom fields or entities.

## Installation

- Install this module using the [official Backdrop CMS instructions](https://backdropcms.org/guide/modules).

## Usage

 - Use the `replicate_clone_entity()` function to clone an entity without
   saving it.
 - Use the `replicate_entity()` function to clone an entity and save it at the
   end of the process.
 - See the `replicate.api.php` file for detailed use of hooks functions.

More details may be found (or added) in the [Wiki](https://github.com/backdrop-contrib/replicate/issues)

## Issues

Bugs and Feature requests should be reported in the [Issue Queue](https://github.com/backdrop-contrib/replicate/issues)

## Current Maintainers

- [Laryn Kragt Bakker](https://github.com/laryn)

## Credits

- Ported to Backdrop by [Laryn Kragt Bakker](https://github.com/laryn)
- Initial port was sponsored by [CEDC.org](https://CEDC.org)
- Maintained for Drupal 7 by [jgalletta](https://www.drupal.org/u/jgalletta) and
  [Vincent Bouchet](https://drupal.org/u/vbouchet)
- Originally sponsored by Capgemini Drupal Factory

## License

This project is GPL v2 software. See the LICENSE.txt file in this directory for
complete text.

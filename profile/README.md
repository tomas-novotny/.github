<div align="center" width="100%">

# Tomáš Novotný

[![Gravitton][ico-gravitton]][link-gravitton]
[![Gravitton blog][ico-gravitton-blog]][link-gravitton-blog]
[![inspirum][ico-inspirum]][link-inspirum]

Libraries I create, or help maintain through pull requests

<hr>

</div>

## Gravitton

Generic, allocation-conscious Go libraries for game development at [Gravitton][link-gravitton],
tested to 100% coverage, with results that stay bit-identical across amd64 and arm64.

- [geometry](https://github.com/gravitton/geometry): immutable 2D geometry: points, vectors and shapes with their tests, casts and constructions.
- [hexagon](https://github.com/gravitton/hexagon): hexagonal grid math: coordinates, rings, lines, line of sight and field of view.
- [grid](https://github.com/gravitton/grid): 2D grids with rectangular, isometric and hexagonal layouts, range and sight queries, and pathfinding.
- [spatial](https://github.com/gravitton/spatial): broad-phase spatial indexes: a spatial hash with box, point and cast queries and touching pairs.

### Blog

Each post on the [Gravitton blog][link-gravitton-blog] takes one decision from these libraries and
shows the code and the numbers behind it.

- [Go libraries for 2D games: geometry, hexagon and grid](https://gravitton.github.io/blog/posts/gravitton-libraries/)
- [What generics over number types cost in Go](https://gravitton.github.io/blog/posts/generic-numbers/)
- [Closed boundaries within a tolerance in a Go geometry library](https://gravitton.github.io/blog/posts/closed-boundaries/)

## Inspirum

PHP libraries and their Symfony bundles at [inspirum][link-inspirum].

- [balikobot](https://github.com/inspirum/balikobot-php): a client for the Balikobot shipping API.
- [xml](https://github.com/inspirum/xml-php): a simple XML writer and a memory-efficient XML reader with an xml-to-array cast.

## Biano

PHP libraries used at [Biano](https://github.com/BianoCZ).

- [bunny](https://github.com/jakubkulhan/bunny): a pure-PHP AMQP (RabbitMQ) client, sync and async on ReactPHP.
- [elasticsearch-dsl](https://github.com/BianoCZ/elasticsearch-dsl-php): a fork of ElasticsearchDSL with Symfony support for different Elasticsearch versions.

[ico-gravitton]:            https://img.shields.io/github/stars/gravitton?style=flat-square&label=gravitton&color=e8883a
[ico-gravitton-blog]:       https://img.shields.io/badge/gravitton-blog-e8883a?style=flat-square
[ico-inspirum]:             https://img.shields.io/github/stars/inspirum?style=flat-square&label=inspirum&color=1ba68b

[link-gravitton]:           https://github.com/gravitton
[link-inspirum]:            https://github.com/inspirum
[link-gravitton-blog]:      https://gravitton.github.io/blog/

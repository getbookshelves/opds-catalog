<p align="center">
  <img src="app-icon.png" alt="BookShelves eBook Reader" width="96" height="96">
</p>

# OPDS Catalog Guide

> Maintained by [BookShelves eBook Reader](https://getbookshelves.app) — a free EPUB reader for macOS and iOS.

A practical guide to OPDS (Open Publication Distribution System) — the open standard for discovering and downloading ebooks from any compatible reader app.

## What Is OPDS?

OPDS is like RSS for ebooks. It defines a standard way for ebook catalogs to publish their collections so that any OPDS-compatible ebook reader app can browse and download books directly.

Instead of visiting a website, finding a book, downloading the file, and importing it into your reader, OPDS lets you do everything from inside your app.

## How It Works

1. An OPDS catalog publishes a feed (Atom XML) listing available books
2. Your ebook reader app subscribes to the feed URL
3. You browse, search, and download books without leaving the app
4. The book lands in your library, ready to read

It's decentralized — anyone can host an OPDS catalog, and any reader can connect to it.

## OPDS Catalogs

These libraries and publishers offer OPDS feeds you can add to your ebook reader:

| Catalog | OPDS Feed URL | Description |
|---------|---------------|-------------|
| [Standard Ebooks](https://standardebooks.org/) | `https://standardebooks.org/feeds/opds` | Beautifully formatted public domain books |
| [Project Gutenberg](https://www.gutenberg.org/) | `https://m.gutenberg.org/ebooks.opds/` | 70,000+ public domain titles |
| [Feedbooks](https://www.feedbooks.com/) | `https://catalog.feedbooks.com/catalog/index.atom` | Public domain and original ebooks |
| [ManyBooks](https://manybooks.net/) | `https://manybooks.net/opds/index.php` | 50,000+ free titles |
| [Internet Archive](https://archive.org/) | `https://bookserver.archive.org/catalog/` | Massive digital library |
| [OAPEN](https://www.oapen.org/) | `https://library.oapen.org/opds` | Open access academic books |

## OPDS-Compatible Ebook Reader Apps

| App | Platform | OPDS Support |
|-----|----------|-------------|
| [BookShelves](https://getbookshelves.app) | macOS, iOS | Built-in OPDS browser with Standard Ebooks catalog pre-configured |
| [Calibre](https://calibre-ebook.com/) | Windows, macOS, Linux | Via "Get books" plugin and OPDS catalog browser |
| [KOReader](https://koreader.rocks/) | Linux, Android, E-ink | Full OPDS support with search |
| [Librera](https://librera.mobi/) | Android | OPDS catalog browser built in |
| [Thorium Reader](https://www.edrlab.org/software/thorium-reader/) | Windows, macOS, Linux | Full OPDS support from EDRLab |
| [Aldiko](https://www.aldiko.com/) | Android, iOS | OPDS catalog subscriptions |

## OPDS Versions

### OPDS 1.2 (Current Standard)
- Based on Atom (XML)
- Widely supported by existing readers and catalogs
- Defines navigation feeds, acquisition feeds, and search

### OPDS 2.0 (Newer)
- Based on JSON (OPDS 2.0 uses Readium Web Publication Manifest)
- Better support for pagination and faceted search
- Still gaining adoption

Most catalogs and readers today use OPDS 1.2.

## Hosting Your Own OPDS Catalog

Want to share your personal ebook collection? You can host your own OPDS server:

| Tool | Language | Description |
|------|----------|-------------|
| [Calibre Content Server](https://manual.calibre-ebook.com/server.html) | Python | Built into Calibre — share your library over the network |
| [COPS](https://github.com/seblucas/cops) | PHP | Calibre OPDS PHP Server — lightweight web interface for Calibre libraries |
| [Kavita](https://www.kavitareader.com/) | C# | Self-hosted digital library with OPDS support |
| [Komga](https://komga.org/) | Kotlin | Media server for comics and ebooks with OPDS feed |

## OPDS Specification

- [OPDS 1.2 Spec](https://specs.opds.io/opds-1.2)
- [OPDS 2.0 Spec](https://drafts.opds.io/opds-2.0)
- [OPDS Search](https://specs.opds.io/opds-1.2#7-search)

## Further Reading

- [The Best Free eBook Sources Nobody Talks About](https://medium.com/@theopenshelf/the-best-free-ebook-sources-nobody-talks-about-6a3b463b2352) — free ebook sources with OPDS feeds you can browse from your reader
- [EPUB vs Kindle Format: What You're Actually Missing](https://medium.com/@theopenshelf/epub-vs-kindle-format-what-youre-actually-missing-2e9c3d3b3302) — why open formats like EPUB matter

## License

This guide is released under [CC0 1.0](https://creativecommons.org/publicdomain/zero/1.0/).

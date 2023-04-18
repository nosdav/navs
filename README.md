

<div align="center">  
  <h1>navs</h1>
</div>

<div align="center">  
<i>navs</i>
</div>

---

<div align="center">
<h4>Documentation</h4>
</div>

---

[![GitHub license](https://img.shields.io/badge/license-MIT-blue.svg)](https://github.com/nosdav/navs/blob/gh-pages/LICENSE)
[![npm](https://img.shields.io/npm/v/nosdav-navs)](https://npmjs.com/package/nosdav-navs)
[![npm](https://img.shields.io/npm/dw/nosdav-navs.svg)](https://npmjs.com/package/nosdav-navs)
[![Github Stars](https://img.shields.io/github/stars/nosdav/navs.svg)](https://github.com/nosdav/navs/)

## NAVs

NAVs stand for **Nosdav Advancement Visions**.
They exist to document what may be implemented by [NosDAV](https://nosdav.com/)-compatible _server_ and _client_ software.

---

- [List](#list)
- [Criteria for acceptance of NIPs](#criteria-for-acceptance-of-navs)
- [License](#license)

---

## NosDAV Core Spec

- [NosDAV Core Spec](https://nosdav.com/spec/)


## List

- [NAV-01: Identity](01.md)
- [NAV-02: HTTP Verbs](02.md)
- [NAV-03: Authentication](03.md)
- [NAV-04: Access Control](04.md)
- [NAV-05: CORS](05.md)
- [NAV-06: Content Types](06.md)
- [NAV-07: Discovery](07.md)
- [NAV-08: Notifications](08.md)
- [NAV-11: Linked Data](11.md)

## Criteria for acceptance of NAVs

1. They should be implemented in at least one server and one relay -- when applicable.
2. They should make sense.
3. They should be optional and backwards-compatible: care must be taken such that clients and servers that choose to not implement them do not stop working when interacting with the ones that choose to.
4. Other rules will be made up when necessary.

## License

- MIT

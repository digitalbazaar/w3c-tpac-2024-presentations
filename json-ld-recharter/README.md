# CBOR-LD, YAML-LD & the JSON-LD Recharter

## CBOR-LD talking points
- one type table connects to JSON-LD now
  - streamlined abstracted process that links JSON-LD @type(s) to lookup tables
- the registry of CBOR-LD specific tag/varints via the CBOR tag registry
  - last byte of a tag for the first byte of the varint


## Outline

* Intro
* JSON-LD WG Recharter summary
  * current charter expires on ____
  * rechater underway
  * Maintaining JSON-LD stack
    * JSON-LD 1.1
    * JSON-LD 1.1 API
    * JSON-LD 1.1 Framing
  * Upgrading JSON-LD
    * JSON-LD 1.2 (possibly 2.0)
    * Driven by...
      * long standing feature requests (which we didn't get to last time)
      * RDF-star
  * New documents being added
    * Rec track
      * CBOR-LD
      * YAML-LD
    * Notes
      * Multiple languages in JSON via JSON-LD's value objects
      * Hash fragment to store content hash fragments intended for context URLs
* CBOR-LD
  * Enabling small data use cases
    * QR Codes
    * Web of Things
  * How?
    * Mapping terms to numbers
    * ...
  * Road ahead
    * Added to charter
    * CBOR-LD 1.0 Working Draft
    * incorporate other work
    * gather WG feedback/contribution/changes
* YAML-LD
  * Enable human-friendly Linked Data
    * stay compatible with JSON-LD for easy transformation
  * CCG developed spec
  * Stable, but needs implementers
  * WG picking up to formalize and build test suite
* [if time] Multiple languages in JSON
  * JSON-LD's Value Object pattern expressed "alone"
  * encourage implementations of Value Objects
  * encourage use in JSON documents that lack `@context`
  * create a referenceable spec/note for other specs
* [if time] Content hash fragment for context URLs
  * `#hash=...`
  * optionally used by document loaders to verify equality of contexts
  * not strictly about HTTP
* Questions?
* Thanks!
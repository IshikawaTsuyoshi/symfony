CHANGELOG
=========

5.3
---

 * Add `AbstractUid::fromBinary()`, `AbstractUid::fromBase58()`, `AbstractUid::fromBase32()` and `AbstractUid::fromRfc4122()`
 * [BC BREAK] Replace `UuidV1::getTime()`, `UuidV6::getTime()` and `Ulid::getTime()` by `UuidV1::getDateTime()`, `UuidV6::getDateTime()` and `Ulid::getDateTime()`

5.2.0
-----

 * made UUIDv6 always return truly random node fields to prevent leaking the MAC of the host

5.1.0
-----

 * added support for UUID
 * added support for ULID
 * added the component

# Delivery calculation
- [x] Connect Google Maps and protect delivery lookups with a checkout session.
- [x] Add pricing models and seller delivery settings using the existing store API.
- [x] Show quotes and totals at checkout; block unsupported delivery addresses; keep pickup free.
- [x] Test pricing rules and unrelated checkout flows (9 tests passed; seller settings persist; pickup order reads back in seller UI).
- [ ] Validate real Google Maps distances on an authorized deployed origin — blocked by sandbox Maps verification restrictions; user validation required.

Existing store settings and orders still use browser-local demo storage. This task preserves the existing store API; shared production persistence and secure seller accounts are not migrated here.
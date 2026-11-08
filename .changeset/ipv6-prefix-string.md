---
'@nestjs/throttler': patch
---

Honour an `ipv6SubnetPrefix` given as a numeric string, as `ConfigService` returns environment variables. It was silently replaced by the default `/64`.

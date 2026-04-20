Unreleased Changes
------------------

0.1.2 (2026-04-20)
------------------

* Feature - Accept a pre-built `s3_client` (e.g. `Aws::S3::EncryptionV2::Client`)
  for fetching SES client-side-encrypted inbound objects, plus optional
  `decrypt_fallback_to_plain` for mixed buckets (refs #5).

0.1.1 (2026-03-31)
------------------

* Fix - Prevent duplicate response errors when handling invalid or malformed SES inbound email requests. (#7)

0.1.0 (2024-11-16)
------------------

* Feature - Initial version of this gem.

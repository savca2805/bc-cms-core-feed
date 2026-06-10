# bc-cms-core-feed

Public update feed for the bc-cms-core CMS engine. Contains only `latest.json`
(version / date / notes) — **no code, no secrets**. Sites poll it via the
`ENGINE_UPDATE_URL` setting to show an "update available" badge in the admin.

On each engine release: bump `version` here to match `src/version.php` in the
(private) `bc-cms-core` repo.

# Fluency-Releases — RETIRED (2026-09-27)

**Do not publish here.** Releases now live in one repository per language,
served at `https://rabbijoshy.github.io/Fluency-Releases-<segment>/`:

- [Fluency-Releases-es](https://github.com/RabbiJoshy/Fluency-Releases-es)
- [Fluency-Releases-pt](https://github.com/RabbiJoshy/Fluency-Releases-pt)
- [Fluency-Releases-cs](https://github.com/RabbiJoshy/Fluency-Releases-cs)
- [Fluency-Releases-fi](https://github.com/RabbiJoshy/Fluency-Releases-fi)
- [Fluency-Releases-fr](https://github.com/RabbiJoshy/Fluency-Releases-fr)
- [Fluency-Releases-lyrics](https://github.com/RabbiJoshy/Fluency-Releases-lyrics)

Publish with `python3 scripts/publish_release.py --segment <seg> --release <dir>`
in RabbiJoshy/Fluency-App (see its `docs/decisions/0026-release-repos-per-language.md`).
Anything pushed here is not read by the app.

This site stays up until about 2026-10-04 so installed copies of the app that
still point here keep working, then it will be emptied. Until then it is also
the only copy of the superseded releases that were not carried over
(`*-speech-v15-10000x10`, lyrics v18, `lyrics-test-playlist-v16`).

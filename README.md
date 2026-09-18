# Wound Care — note generator

Hosted tool for a homecare wound-care documentation workflow.

**Live:** https://nvdberg.github.io/woundcare/

Paste the wound JSON produced by the Claude "Wound Care" project → editable form → plain-text note for SCM / Procura.

Hosted because hospital PCs cannot download files. Contains **no patient data**: the page ships with a de-identified sample only, and saved notes live in the user's own browser (plus an optional passphrase-gated Supabase sync).

Source of truth for this file is the private `AdelesWoundcare` repo; publish with its `publish.sh`.

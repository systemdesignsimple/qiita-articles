# qiita-articles

Qiita articles for System Design Simple (Japanese), managed with Qiita CLI.

Article files live under public/. Pushing to main runs the Publish articles
workflow (.github/workflows/publish.yml), which posts or updates the articles
on Qiita @systemdesignsimple. Files carry their Qiita article id in the front
matter, so a push updates the existing article instead of creating a new one.
The workflow needs the QIITA_TOKEN repository secret (a Qiita personal access
token with read_qiita and write_qiita scopes).

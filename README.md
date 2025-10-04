# Recon Submission — internee.pk
Date: $(date -u +"%Y-%m-%d %H:%M:%SZ" )

## What is included
- `full_recon.sh` — script used to run recon
- `targets_443_open.txt` — main targets list used
- `internee_subdomains*.txt`, `amass_all.txt`, `amass_passive.txt` — discovery outputs
- `reports/httpx_enriched.json` — httpx enrichment (JSON)
- `reports/ffuf_accounts_hits_clean.txt` — directory fuzz hits (filtered)
- `reports/ssl_certs.nmap`, `reports/robots_sitemaps_follow.txt` — nmap certs and robots/sitemap fetches
- `reports_2025-10-04_cleaned.tgz` & `.sha256` — tarball with cleaned reports

## Notes / disclaimers
- I removed/redacted any obvious secrets before packaging. Please inform me if you want additional redaction.
- Some hosts are behind Cloudflare/Vercel; follow-up interactive checks may be needed.
- Do not publish the tarball publicly if it contains sensitive data. Prefer a private repo.

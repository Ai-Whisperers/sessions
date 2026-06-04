# Ai-Whisperers / sessions

Organized archive of production session data from the Ai-Whisperers Hermes Agent system.

## Structure

- `client-projects/` — client work by account and topic
  - `paragu-ai/`
    - `admin-panel`
    - `business-planning`
    - `deployment`
    - `general-work`
    - `hermes-upgrades`
    - `infra`
    - `other`
    - `repo-work`
    - `seo-content`
    - `visual-design`
    - `whatsapp`
  - `fun4me/`
    - `admin-access`
    - `channels`
    - `client-onboarding`
    - `glass`
    - `nexa-discussions`
    - `other`
    - `payments`
    - `research`
    - `site-work`
  - `elviajero/`
    - `admin-panel`
    - `api-setup`
    - `business-docs`
    - `csp-and-errors`
    - `github-org`
    - `hermes-ops`
    - `image-assets`
    - `infra`
    - `login-issues`
    - `other`
    - `page-improvements`
    - `products`
    - `research-batch`
    - `seo`
    - `deployment-sync`
  - `nexa/`
  - `maskarada/`
  - `other/`
- `infra/` — operational work
  - `deployment`
  - `docker`
  - `github-actions`
  - `monitoring`
  - `supabase-postgres`
  - `traefik-swarm`
- `ai-agent-work/` — agent tooling work
  - `client-ops`
  - `cron`
  - `other`
  - `research`
  - `skills`
- `other/`
  - `oss`
  - `other`
- `research-intel/`
- `root/`

## File format

Sessions are stored as JSON and JSONL exports from the Hermes runtime. Filenames follow the original runtime pattern:

- session timestamp + short id
- human-readable dates where present

## Reprocessing

The original filtering pipeline is not included in this repo. For questions about the build, contact the ai-whisperers engineering team.

## Policy

- Contains internal operational data.
- Not for redistribution.
- Subject to Ai-Whisperers internal data handling policy.

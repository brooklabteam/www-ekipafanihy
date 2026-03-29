# CLAUDE.md — Ekipa Fanihy Website

## Overview

This is the [Ekipa Fanihy](https://ekipafanihy.org) website — a Jekyll static site deployed via Netlify. It shares the same base structure as the [Brook Lab website](https://brooklab.org) ([brooklabteam/www](https://github.com/brooklabteam/www)).

**Refer to [brooklabteam/www CLAUDE.md](https://github.com/brooklabteam/www/blob/main/CLAUDE.md) for full documentation** on local development, repository structure, adding news posts, top-level pages, navigation, site configuration, and deployment — the conventions are the same.

## Ekipa Fanihy–Specific Notes

### Bilingual Content

Many pages have both English and Malagasy versions:

| English file | Malagasy file | Notes |
|---|---|---|
| `index.md` | `index-mg.md` | Home page |
| `team.md` | `team-mg.md` | Team page |
| `work.md` | `work-mg.md` | Work/research page |

### Site Configuration

`_config.yml` points to `https://ekipafanihy.org`. Update this file if the site URL changes.

## Pending TODOs

- **WWW redirect**: Make sure `www.ekipafanihy.org` redirects to the apex domain `ekipafanihy.org` (via `_redirects` or `netlify.toml`).

---
title: Domains
---

# Domains
You can either use the official <https://github_username.github.io/repo_name>, or configure a custom domain.

## Configuring Custom Domains

> [!NOTE] 
> For further details, check the official [documentation](https://docs.github.com/en/pages/configuring-a-custom-domain-for-your-github-pages-site).

First, set the DNS records to point to Github Pages:

A Records (Hostname: `@`):
```
185.199.108.153
185.199.109.153
185.199.110.153
185.199.111.153
```

AAAA Records (Hostname: `@`):
```
2606:50c0:8000::153
2606:50c0:8001::153
2606:50c0:8002::153
2606:50c0:8003::153
```

It's always nice to set a subdomain like `www` or for separation a custom one, to do so, add a CNAME record for your subdomain.

- Hostname: `www` or your subdomain like `just-obsidian-docs`
- Value: `github_username.github.io` (**very important not to set it to your custom domain**)

Then, go set the custom domain, if you want the <subdomain.domain.top_level_domain> to be how users see your site, type that in. Or, if you just want your apex domain (that is, <domain.top_level_domain>) put that in.

Sometimes the check may fail because the DNS records haven't propagated over to Github yet, give it a few tries. In some cases, you can remove then add it back. HTTPS should work after a few minutes, if you see that Github has successfully acquired your certificate, then you should be able to click "Enforce HTTPS"

## Using the Default
You don't have to do anything, just remember to set baseURL to `/repo_name` and that's it.
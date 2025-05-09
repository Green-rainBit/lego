---
title: "RimuHosting"
date: 2019-03-03T16:39:46+01:00
draft: false
slug: rimuhosting
dnsprovider:
  since:    "v0.3.5"
  code:     "rimuhosting"
  url:      "https://rimuhosting.com"
---

<!-- THIS DOCUMENTATION IS AUTO-GENERATED. PLEASE DO NOT EDIT. -->
<!-- providers/dns/rimuhosting/rimuhosting.toml -->
<!-- THIS DOCUMENTATION IS AUTO-GENERATED. PLEASE DO NOT EDIT. -->


Configuration for [RimuHosting](https://rimuhosting.com).


<!--more-->

- Code: `rimuhosting`
- Since: v0.3.5


Here is an example bash command using the RimuHosting provider:

```bash
RIMUHOSTING_API_KEY=xxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxx \
lego --email you@example.com --dns rimuhosting -d '*.example.com' -d example.com run
```




## Credentials

| Environment Variable Name | Description |
|-----------------------|-------------|
| `RIMUHOSTING_API_KEY` | User API key |

The environment variable names can be suffixed by `_FILE` to reference a file instead of a value.
More information [here]({{% ref "dns#configuration-and-credentials" %}}).


## Additional Configuration

| Environment Variable Name | Description |
|--------------------------------|-------------|
| `RIMUHOSTING_HTTP_TIMEOUT` | API request timeout in seconds (Default: 30) |
| `RIMUHOSTING_POLLING_INTERVAL` | Time between DNS propagation check in seconds (Default: 2) |
| `RIMUHOSTING_PROPAGATION_TIMEOUT` | Maximum waiting time for DNS propagation in seconds (Default: 60) |
| `RIMUHOSTING_TTL` | The TTL of the TXT record used for the DNS challenge in seconds (Default: 3600) |

The environment variable names can be suffixed by `_FILE` to reference a file instead of a value.
More information [here]({{% ref "dns#configuration-and-credentials" %}}).




## More information

- [API documentation](https://rimuhosting.com/dns/dyndns.jsp)

<!-- THIS DOCUMENTATION IS AUTO-GENERATED. PLEASE DO NOT EDIT. -->
<!-- providers/dns/rimuhosting/rimuhosting.toml -->
<!-- THIS DOCUMENTATION IS AUTO-GENERATED. PLEASE DO NOT EDIT. -->

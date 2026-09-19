# OIDC beats long-lived cloud keys

Configure a trust policy against GitHub's OIDC issuer and the workflow exchanges a short-lived token at run time. This removes static cloud credentials from repository secrets entirely. Scope the trust condition to the specific repo and ref or any repo can assume the role.

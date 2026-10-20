---
name: manage-dlp-policy-rules
description: Authenticate to a self-hosted Forcepoint DLP Manager and read or update DLP policy rules and exceptions.
api: Forcepoint DLP REST API
operations:
- post_dlp_rest_v1_auth_refresh_token
- post_dlp_rest_v1_auth_access_token
- get_dlp_rest_v1_policy_enabled_names
- get_dlp_rest_v1_policy_rules
- post_dlp_rest_v1_policy_rules
- get_dlp_rest_v1_policy_rules_exceptions
generated: '2026-10-20'
method: generated
source: openapi/_ae-authored/forcepoint-openapi-generated.yml
---
Grounded in a contract GENERATED from the public DLP REST API Guide (not a Forcepoint-published spec).

1. Obtain a refresh token (`post_dlp_rest_v1_auth_refresh_token`) with an application registered in the Forcepoint Security Manager.
2. Exchange it for an access token (`post_dlp_rest_v1_auth_access_token`), sending `refresh-token: Bearer <token>`.
3. List enabled policies (`get_dlp_rest_v1_policy_enabled_names`), then read rules (`get_dlp_rest_v1_policy_rules`) and exceptions (`get_dlp_rest_v1_policy_rules_exceptions`).
4. Update a rule with `post_dlp_rest_v1_policy_rules` only after confirming the change; no idempotency or reversal mechanism is documented, so re-read the rule afterwards.

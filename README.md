**KV_AZ5_ALL_Components**

What this fixes (mapped to CIS v5.0)
Control	Status
Logging enabled	✅ Enforced
RBAC enabled	✅
Public access disabled	✅
Private endpoint	✅
Soft delete + purge protection	✅
Key expiration	✅ (example enforced pattern)
Secret expiration	✅ (example enforced pattern)
Key rotation	✅

**KV_AZ5_ResourceAlone**

What this gives you

This is the tightest Key Vault-only baseline you can enforce in a single vault resource block:

RBAC permission model enabled
public network access disabled
purge protection enabled
soft delete retention set
network ACL default deny
What this does not cover

Because you asked for just the Key Vault resource, these are not included:

private endpoint
private DNS
diagnostic settings / AuditEvent logging
keys with expiration
secrets with expiration
key rotation policy

Khatru Pyramid is a Nostr relay that uses an invite-based hierarchy to control who can publish events. Only users in the invite tree can write to the relay. Each existing member can invite a configurable number of new members, creating a web-of-trust access model.

Features:

- Invite-based access control (pyramid/hierarchy model)
- LMDB storage backend for fast event storage and retrieval
- Web interface for managing the invite tree and viewing reports
- Full Nostr relay protocol support (NIP-01, NIP-11, NIP-42, NIP-09)
- Negentropy sync protocol support
- Configurable maximum invites per person

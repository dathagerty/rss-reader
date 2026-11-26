# Single-user, self-hosted

The reader serves exactly one person per instance. There is no account model: no user IDs on data, no per-user read state, no tenant isolation between agents. Multi-user was rejected because it multiplies auth, schema, and isolation work for a tool meant to run on one person's server; adding it later means a schema migration that attaches all existing data to a first user.

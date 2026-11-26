# RSS Reader

A single-person, self-hosted aggregator that follows Feeds and serves their Articles to the person directly, to e-readers, and to agents.

## Language

### Sources

**Feed**:
Something the reader follows that produces **Articles** over time: either a syndication feed (RSS, Atom, JSON Feed) or a **Publication**.
_Avoid_: Source, channel, subscription

**Publication**:
A standard.site publication record on the AT Protocol, followed as a **Feed**.
_Avoid_: Site, blog

### Organisation

**Folder**:
A named group that a **Feed** belongs to; each **Feed** is in at most one.
_Avoid_: Category, tag, collection

### Content

**Article**:
One piece of content produced by a **Feed**. A standard.site document is an **Article** of its **Publication**.
_Avoid_: Item, entry, post, document

**Feed Content**:
The body of an **Article** as the **Feed** delivered it, which may be only a summary.
_Avoid_: Summary, description

**Extracted Content**:
The body of an **Article** recovered from its web page, used when **Feed Content** is incomplete.
_Avoid_: Full text, readability content

### Reading state

**Read**:
An **Article** the person has consumed, either by opening it in the reader or by marking it. An agent fetching an **Article** never makes it **Read**.
_Avoid_: Seen, viewed, consumed

**Starred**:
An **Article** the person has chosen to keep; it is exempt from retention.
_Avoid_: Saved, favourite, bookmarked

### Delivery

**Digest**:
A single e-book that bundles several **Articles** for reading on an e-reader.
_Avoid_: Bundle, issue, compilation

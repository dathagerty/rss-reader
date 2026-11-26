# standard.site Publications are Feeds, polled from the PDS

A standard.site Publication is modelled as a Feed alongside RSS/Atom/JSON Feed, so the reader, OPDS, and MCP surfaces never special-case it. New Documents are found by periodically listing the publisher's PDS repository, not by consuming the AT Protocol firehose/Jetstream: polling matches how every other Feed is refreshed and needs no long-lived connection, at the cost of minutes of latency.

---
title: "Encryption"
draft: false
weight: 60
---

# Use of end-to-end encryption

1:1 calls are now encrypted end-to-end by default. Therefore, a configured key
backup as well as a verification of all self used client devices is recommended
([Important settings]({{< ref "matrix/settings" >}}))

The decision whether a room should be encrypted in this way must be well thought
out and cannot be undone. If the room is large or public, checking all keys of
all interlocutors will take a lot of time. But this manual check can be done
later on occasion and end-to-end encrypted conversations can be started directly
with blind trust for the time being.

If you want end-to-end encryption (E2EE) to interlocutor:inside in an
unencrypted room, you can achieve this by clicking on the settings of the
desired room. (or in the room via "Room info" > "Room settings" in the upper
right corner):

To do this, move the Encrypted slider on the Security & Privacy tab:

This can be confirmed with OK. From now on the messages can only be read by
those involved in the conversation. If you have not set up a key protection in
the settings before, you should do this now (see [Important
settings]({{< ref "matrix/settings" >}})) to be able to read earlier messages or
one sent when your clients are closed.

A detailed description of the topic can be found in this
[in this Matrix blog article](https://blog.riot.im/e2e-encryption-by-default-cross-signing-is-here).

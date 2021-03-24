---
title: "Message search"
draft: false
weight: 40
---

It is not uncommon to want to search for older conversation content. To search
through the message history of a room (or all rooms) for a certain text, you
need to click the 🔍 "Search" button in the upper right corner of the Element
App.

Looking for messages is possible in _unencrypted_ rooms without any problem
since Element has access to all the messages.

The situation is different in encrypted rooms because Element does not have
access to all your encrypted messages. This function is only possible using the
[desktop client]({{< relref "clients" >}}) because messages must be cached for
the search, which is a disabled function by default. The message search must be
explicitly enabled under `Settings` -> `Security & Privacy` -> `Message search`
-> `Enable`. Afterwards, searching is also possible in encrypted rooms.

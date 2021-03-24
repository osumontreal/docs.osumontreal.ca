---
title: "Share rooms"
draft: false
weight: 40
---

This page is about sharing rooms to others through links.

{{% notice note %}} To share or publish a global address, you have to create a
local address first. **It is necessary to create a local address in both
cases!** If you did not do this step when you created a room, you have to do
this, please refer to the [Settings for Rooms
section]({{% ref "create#room-settings" %}}) to do it. {{% /notice %}}

That being said, you can find the room address with following structure
`#room-address-name:openscience.ca` in the _Room settings_ under the General
tab > Room Addresses > Published Addresses. If you don't find an address there,
click on "Show more" under Local Addresses, and it should be there. If you don't
see any address, it means that the admin never created one in the first place.
If you want to share a room within Matrix, you don't have to go through this
procedure, you simply have to know the name of the room you want to share, as
described below.

## How to share a room within Matrix

When you want to share a room that you are a member of, you can simply use the
internal link feature by starting typing `#` followed by the _room address_ or
_name_. You can confirm the room name by autocompleting it using your mouse or
your arrow keys on your keyboard. You can also autocomplete the room name by
hitting your `tab` button. When you use the `#room-address:openscience.ca`
format into the chat box, it renders the name of the room automatically.

This is a special link for a usage within matrix, which will open directly in
the client of the receiver when they click on it with their mouse.

## How to share a room outside Matrix

{{% notice warning %}}

There is a share icon in the upper right corner of each room also provides a
link, a QR code and various social networks. However, these links lead to
https://matrix.to/ from which anyone can access the room or get invited to join
the room via the Element Web <https://element.io> **(not our Element App)** if
they don't have a matrix client installed on their computer. To prevent
misunderstanding and to share a room so people can register through our Open
Science Server, we highly advise you to use the methode explained below. Matrix
developpers are aware of this issue
([#197](https://github.com/matrix-org/matrix.to/issues/197)).

{{% /notice %}}

A typical link looks like this
`https://chat.openscience.ca/#/room/#ROOM-ADDRESS:openscience.ca`. The only
thing you have to change in this URL is the `ROOM-ADDRESS` part.

If you are using the **Element Web App**, the easiest way to share a link to
someone outside the Matrix ecosystem is to simply copy and paste the URL you see
in the address bar of your browser. If the room is public, the person who clicks
on the link will be prompted to log in or sign up.

If you are using any other app, you can create a hyperlink to the room, which
you have to construct like this:
`https://chat.openscience.ca/#/room/#support:openscience.ca`

The link you share is, in fact, an internet address (URL) which can be easily
distributed to the public or target group. BUT, **this link opens only an
Element Web in the browser** of the people, not in an installed Element Desktop.
Once a person has joined the room, they will see it appear in their desktop app
automatically.

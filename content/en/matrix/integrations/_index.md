---
menutitle: Integrations
title: Widgets, Bots, & Bridges Integrations
draft: false
weight: 80
---

Integrations or Widgets can be managed via the room information in the upper
right corner.

Here, for example, an etherpad, a jitsi video conference, an RSS bot, etc. can
be integrated, i.e. services that are located and run on other servers.
Therefore, when using integrations, the JavaScript activity of vector.im (for
the integration manager) and other servers (e.g. in the Firefox addon NoScript)
must be allowed. Since the widgets are often too small to use the services in
their full functionality, widgets can often be opened large in new browser tabs.

## Jitsi Videoconference

A 1:1 phone call or video within Matrix uses the direct WebRTC connection
between both parties. From the 3rd person on,
[Jitsi](https://wikipedia.org/wiki/Jitsi) is used, a free video conferencing
tool (Apache license).

In order for Jitsi to be used for the video conference, at least three people
must participate in the conference. If only two people participate in the
conference, a direct connection will be established.

{{% notice warning %}} You can also add via the Integration Manager to feature
talks while others can chat in the room. {{% /notice %}}

Also with Jitsi, opening the widget as a separate tab is useful to use the full
functionality (e.g. screen sharing).

The use of a headset is highly recommended to avoid feedback between sound
recording and sound playback. Ideally a headset with a microphone close to your
mouth works best because the use of the microphone hole on the laptop may cause
more noise through.

The `m` key mutes your microphone - you should always start a conference with
your microphone muted. The `space bar` switches the microphone on when muting is
active (push-to-talk). Since the microphone input levels are all set
differently, all hearing participants can adjust the volume of all conference
participants individually. Furthermore, the individual video quality can be
adjusted.

For sharing the screen contents (or specific program windows), it may be
necessary to adjust the security settings of the operating system (This is often
the case with MacOS: under System Preferences > Security > Privacy > Screen
Capture).

## Etherpad

The Etherpad widget can be used for collaborative writing or attaching important
information to a room.

{{% notice warning %}} For this purpose, a name must be assigned which must have
less than 16 characters! {{% /notice %}}

Etherpads have no user rights management, everyone can write and overwrite other
texts (caution!). If user management is needed, you may want to use another
solution.

## Custom widget

Any Internet page can be integrated.

---

{{% notice tip %}}

More information about bridges, bots and other integrations will be added in the
future.

{{% /notice %}}

---

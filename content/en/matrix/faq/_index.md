---
menutitle: "FAQ"
title: "Frequently asked questions"
weight: 200
---

This is a collection of frequently asked questions and their answers. Some of
the answers are not yet written. In these cases please ask in the support room
`#support:openscience.ca`. Beware that it is community support, so you may not
get a reply within seconds.

{{%expand "Messages not readable" %}}

- At least one verified session must be open at all times, the easiest way to do
  this is to set up the Desktop Client or Element on a smartphone. These
  programs can be closed and restarted without having to log in again.
  Otherwise, a verified Matrix session can be created in a private web browser
  window by logging into Matrix there and verifying this session from an
  existing one. This window can be closed after about five minutes. The keys are
  transferred to the other Matrix clients by the verification process. This
  creates a ghost session which is then always open. Then all other clients can
  be logged out. Otherwise messages which are received in the period without
  open matrix session cannot be read later. This is to be solved in the future
  by means of the function dehydrated devices.
- Has the [Secure Backup]({{< relref "matrix/settings/#secure-backup" >}}) been
  set up properly?
- Messages remain unreadable when matrix sessions are created and then the web
  browser window is simply closed without logging out. Solution: only possible
  for new messages: read this documentation. {{% /expand%}}

---

{{%expand "What is the difference between passphrase and recovery key?" %}} The
password that can access the key backup is called the recovery key and is very
long, starts with a capital E and should be saved or printed after setup. Since
this password is hard to remember in everyday life (e.g. when you are on the
road, want to have a look at Matrix, but only have access to other computers)
you can think of a (easy to remember) passphrase from which the recovery key can
be calculated (in the browser/client) before trying to "open" the key backup.
{{% /expand%}}

---

{{%expand "Why is there no status bar at the bottom of the screen when hovering over hyperlinks in the Desktop-Client element? How can you trust them then? " %}}
In fact, the status bar is a popular test of the seriousness of hyperlinks you
are trying to click on. In the Desktop Client element this is not possible,
similar to the mobile clients. Here you can only right-click on the link and
check the presented target page for seriousness. {{% /expand%}}

---

{{%expand "How to tell people a room address with Element Desktop Client?" %}}
You can see the public address when you click on the `I` (ℹ️) icon in the top
right corner. It will open a sidebar and display the address below the picture
and the name (`#room:openscience.ca`). To get the link for a direct access from
outside Matrix, click on "Share room" and you will see a link starting with
`https://matrix.to...`.

{{% /expand%}}

---

{{%expand "Can I write LaTeX formulas?" %}} It is an experimental feature as of
March 2021. It will be available for everybody within the coming weeks. You can
get the latest update from this
[issue](https://github.com/vector-im/element-web/issues/1945). {{% /expand%}}

---

{{%expand "Are there something like Threads (like in Mattermost/Slack) in Matrix?" %}}
No, threads like in Mattermost or Slack are currently not available in Matrix.
The developers of Element are working hard to implement such functionality in
the near future. In the meantime, you can hit the `reply` (↩️) button when you
hover a message to keep conversations tidy. To get more information, follow
their [roadmap](https://github.com/vector-im/roadmap/projects/1). {{% /expand%}}

---

{{%expand "I do not have a security key (recovery key)" %}} To do this, please
check whether this has been set up first. See [Secure
backup]({{< relref "matrix/settings/#secure-backup" >}}) {{% /expand%}}

---

{{%expand "How do I change the passphrase for my backup key?" %}}

- Export the room keys for all matrix sessions except for one, which is still
  accessible, `Settings` -> `Security & Privacy` -> `Encryption`/`Cryptography`,
  here it is best to provide the matrix login password. Finally, log out by
  clicking on the user name in the upper left corner and log out. If you are
  asked whether you want the encrypted messages, click on 'I don't want my
  encrypted messages', because these keys have already been exported.
- Under `Settings`-> `Security & Privacy` -> `Secure Backup` press first
  `Delete Backup`, afterwards the button `Reset` and may a clearing of the cache
  under `Settings`-> `Help & About` is necessary, as well a logging off and
  logging on again. If all this does not work, continue in the next point. The
  action was successful, if only the green 'Setup' button is displayed.
- For all previously exported key backups, perform the manual import path
- Set up a new security backup. See [Secure
  backup]({{< relref "matrix/settings/#secure-backup" >}}) {{% /expand%}}

---

{{%expand "How do I reset the secure backup if I have lost my security phrase AND my (saved and printed) security key?" %}}
Please execute the following:

- export the room keys for all matrix sessions except for one, which is still
  accessible, `Settings` -> `Security & Privacy` -> `Encryption`/`Cryptography`,
  here it is best to provide the matrix login password. Finally, log out by
  clicking on the user name in the upper left corner and log out. If you are
  asked whether you want the encrypted messages, click on 'I don't want my
  encrypted messages', because these keys have already been exported.
- [Delete]({{< relref "matrix/settings/#security--privacy" >}}) all sessions
  that are no longer accessible. the top one in bold is the current session, do
  not tick this one
- Log off the last session
- Write a message to the ServiceDesk with a request to delete the security keys
  from the database.
- Wait for the answer
- Log in again at Matrix and skip verification at windows and messages
- Log out from Matrix
- Log in again at Matrix and skip verification at windows and messages again
- Under `Settings`-> `Security & Privacy` -> `Secure Backup` look if there is a
  green button `Setup` and no red buttons. If there are still red buttons, press
  first `Delete Backup`, afterwards the button `Reset` and may a clearing of the
  cache under `Settings`-> `Help & About` is necessary, as well a logging off
  and logging on again. Also it may be necessary to press the red button `Reset`
  under `Settings`-> `Security & Privacy` -> `Cross-Signing`. The action was
  successful, if for 'Secure Backup' and 'Cross-Signing' only the green 'Setup'
  button is displayed.
- If all this does not work reply to the ticket with a request for a jitsi
  meeting
- For all previously exported key backups, perform the manual import path
- Set up a new security backup. See [Secure
  backup]({{< relref "matrix/settings/#secure-backup" >}}) {{% /expand%}}

---

{{%expand "How can I, as the administrator, delete many messages at once?" %}}

{{% /expand%}}

---

{{%expand "How can I mark the room as 'unread' again?" %}} As of March 2021,
this function has not been implemented yet. As a workaround, you can mark the
room as a favorite to have a quick access to it. {{% /expand%}}

---

{{%expand "What should I do if video or audio in a video conference does not work on a MacOS?" %}}
Often Element does not have the rights to access the webcam and microphone.
These can be assigned in the system settings under Security and Privacy.
{{% /expand%}}

---

{{%expand "How many people can be invited at ones into a room? Can I invite people by their e-mail address?" %}}
Mass invite by e-mail is currently not supported in Element. If you want to mass
invite, please send an request via the `#support:openscience.ca` room, so we can
assist. You can invite 100 people by their username yourself. {{% /expand%}}

---

{{%expand "What is the 'community/communities' option?" %}} Communities were
created by Matrix to group multiple rooms together. However, major refactoring
is happening on communities, which will become _'spaces'_ in the future. Spaces
will be really powerful, we are excited to implement this feature as soon as
possible! For the time being, you can play with _Communities_ but know that it
will probably be not possible to import your _Communities_ into _Spaces_.
{{% /expand%}}

---

{{%expand "Can I manage multiple Matrix-Account on my Element Desktop Client?" %}}
With the Element Desktop client, you can only manage one Matrix-Account right
now. But it is possible to start several Element-windows with different
Matrix-Accounts, also within your Autostart-settings of your computer.
Therefore, you need to change (or create additional) execution commands to open
a specific profile through the command line:

```bash
element-desktop --profile PROFILE_NAME
```

So you can place several Element-Starters in your Autostart, with different
profile names, e.g. `--profile OSUM` or `--profile Private`. Unfortunately, both
opened windows will appear with the same Icon in the Indicator-Applet. Someone
is probably already working on a solution to this problem.

Furthermore, there are other Matrix-Clients, that can handle more
Matrix-Accounts per se, e.g.
[weechat](https://matrix.org/docs/projects/client/weechat-matrix),
[Spectral](https://matrix.org/docs/projects/client/spectral),
[Quaternion](https://matrix.org/docs/projects/client/quaternion), or
[Mirage](https://matrix.org/docs/projects/client/mirage). {{% /expand%}}

---
title: "Format messages"
draft: false
weight: 30
---

## Write and format messages

You can format your text using
[**Markdown**](https://wikipedia.org/wiki/Markdown), a lightweight markup
language. Markdown has become more common recently given its ease of use and its
readability to create formatted text using a plain-text editor.

You can think of Markdown as a few little symbols around your text that will
allow Element to render the text with a little bit of formatting. For example
you can write words as **bold** (`**bold**`), or in _italics_ (`*italics*`), as
a [link](https://youtu.be/dQw4w9WgXcQ) (`[link](https://youtu.be/dQw4w9WgXcQ)`)
to a webpage, or as an image
(`![](https://docs.osumontreal.ca/img/en/kitty.jpg)`): ![](/img/en/kitty.jpg)

[CommonMark](https://spec.commonmark.org/current/) is the current Markdown
specification implemented in Element.

The input of LaTeX formulas is currently not supported. It is offered as an
experimental feature as of the time of updating this page. It will be available
for everybody in the near future. You can get the latest update from this
[issue](https://github.com/vector-im/element-web/issues/1945). Alternatively, an
integration can be used to display LaTeX formulas in the meantime.

**Hashtags** (`#`) can be used to make terms easier to find using the [search
function]({{% relref "search" %}}).

**Smileys** can be reached with a starting colon `:` and then the emoji name.
For example, _\:rainbow_flag\:_ is rendered as :rainbow_flag:.

For a new line break, press **Shift + Enter**.

When the **Ctrl + Enter** option is enabled, you can create a new line break by
pressing **Enter** only.

### Send messages

Messages can be sent by pressing the **Enter key**. If you are used to using
**Ctrl + Enter** to send messages, you can enable the _"Use Ctrl + Enter to send
a message"_ setting in
`Settings > Preferences > Use Ctrl + Enter to send a message`.

### Edit your messages

When you hover your message, you can click on the Edit button (:pencil:) to edit
your message. If a message is edited, it will also appear as edited in
_[threads](#reply-to-a-specific-message-or-thread)_.

### Delete your messages

When you hover your message, you can click on the **...** button, then Remove to
erase this message. The content of the message will be erased and replaced by
the following content _"Message deleted"_. If a message inside thread is
deleted, it will also appear as _"Message deleted"_ in
_[threads](#reply-to-a-specific-message-or-thread)_.

### Keyboard shortcuts

Keyboard shortcuts can save you a lot of time when formatting a message in the
**_Composer_** pane. The usual **Ctrl + b** will turn the highlighted text bold,
etc. The keyboard shortcut to toggle all the keyboard shortcuts is **Ctrl + /**.

This window will pop up:

![Keyboard shortcuts](../keyboard_shortcuts.png)

## Read messages

If there are more unread messages in a room than the screen cannot display,
clicking on the circle with the chevron icon
(<i class="fas fa-chevron-circle-up"></i>) near the right edge of the message
pane will make you jump to the oldest unread message.

Similarly, you can jump to the latest timestamp of a conversation by clicking on
the circle (<i class="fas fa-chevron-circle-down"></i>) in the bottom right
corner of the message pane.

## Reply to a specific message or thread

To keep conversations tidy, you can hit the `reply` (↩️) button when you hover
the last message you want to reply to. If more than one message in involved in
the _thread_, you can click on the _"In reply to"_ to unroll the thread message
by message.

Threads like in Mattermost or Slack are currently not available yet in Matrix.
The developers of Element are working hard to implement such functionality in
the near future. In the meantime, you can hit the `reply` (↩️) button when you
hover a message to keep track of conversations.

To get more information about threading, follow their
[roadmap](https://github.com/vector-im/roadmap/projects/1), more specifically
this [issue](https://github.com/vector-im/element-web/issues/2349).

## Upload and send files

Files and any other media objects (image, GIF, video, etc.) can be sent up to a
maximum size of 10MB. For this purpose the paper clip :paperclip: button must be
selected. The sidebar with the document symbol shows the files within a room.
Larger files needs to be shared via a third-party service via a share link.

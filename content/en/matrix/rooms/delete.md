---
title: "Delete rooms"
chapter: true
draft: false
weight: 30
---

## Delete rooms

If the last person in a room leaves it, the room is still in the archive for 7
days, but is then permanently deleted[^1].

If you are an administrator[^2] of a room and you want to delete it, the
recommended steps are to be done in the following order:

1. Go in the room [settings]({{% relref "settings" %}}) Disable Security &
   Privacy
1. all room members should first be "kicked" out of it (removed from the room),
1. the administrator is the last to leave the room and thus initiates the later
   deletion by the server.

{{% notice warning %}} At the moment, there is no official way to export the
room history into a log file either in `.txt`, `.html` or `.json`. Refer to this
[GitHub issue](https://github.com/vector-im/element-web/issues/2630) to know
more. There are amazing open sourcerers who provided clever solutions in this
issue, including
[matrix-archive](https://github.com/russelldavies/matrix-archive), and
[matrix-dl-csv](https://github.com/shawntabrizi/matrix-dl-csv) that were seen
active recently. {{% /notice %}}

[^1]: We can't be deem responsible for any dataloss.
[^2]:
    Unless the default settings have been changed, the creator of a room is the
    default administrator from the moment the room was created.

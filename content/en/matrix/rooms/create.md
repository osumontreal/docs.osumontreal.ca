---
title: "Create rooms + Settings"
draft: false
weight: 20
---

## Create rooms and take responsibility

New rooms are created using the :plus: (+) button in the left sidebar next to
the _Rooms_ section title.

|                                                             |                                                                |
| ----------------------------------------------------------- | -------------------------------------------------------------- |
| ![Create a private room](../room_create_pv_advanced_lt.png) | ![Create a public room](../room_create_public_advanced_lt.png) |

1. Assign a name to the room.
1. _Optional_: you can also assign a topic.
   - This can be added or modified later on.
1. Decide whether the room should be made publicly accessible (this is not the
   default setting, meaning the default is _unpublished/private_).
   - This can be modified later on, but it is much simpler to set it at this
     stage if you plan to have your room searchable on the server.
1. If you choose to create a **private** room, decide whether you want to enable
   end-to-end ecryption (default option) or not.
   - You **can’t disable** this later, so consider this choice carefully.
     However, it can be enabled at a later time.
   - If you plan to make your room public in the future, we don't recommend
     enabling encryption. In addition, bridges & most bots won’t work yet.
   - If you are unsure about this option, you can get more information in the
     [end-to-end encryption]({{< relref "encryption" >}}) section.
1. If you choose to create a **public** room, decide of a human-friendly address
   for your room.
   - This can be added or modified later on.
1. With an additional click on "Show more", you can block anyone not registered
   with a @openscience.ca account from joining your room.
   - Again, you can't disable it laterit can be prevented that Matrix users from
     outside the Open Science home server (Homeserver) can enter the room.
   - This can be turned _on_ later.

Once you click on **Create Room**, the room is created and appears in your _Room
section_ in the left sidebar. It gets assigned a random color with the first
letter inside the circle. There are many more options that can be adjusted in
the _Room settings_.

{{% notice warning %}} As the room administrator, you are **responsible** for
the content shared in the room (e.g. false messages, hate mail, etc.). You have
admin tools that are useful to moderate rooms (mute, kick, ban, and remove
recent messages). You can also include other people to help you with this
important responsibility by assigning roles in the right sidebar when you click
on a person icon. You can change the _"Permission Level"_ drop-down menu (Admin,
Moderator or Custom). There is also a bot that can help you, but you have to
invite it. {{% /notice %}}

---

## Room settings

To have full control over a room's settings, one needs to be an _admin_. You are
an admin when:

1. You create a room, you become its admin by default;
2. An admin of a room makes you an admin.

By clicking on the :information: icon (**i**) in the upper right corner and then
the gear wheel "room settings" you can access the room settings:

### General tab

In this tab, you can adjust many settings:

- Update the room name;
- Add a description or topic;
- Upload a room-specific image/icon using the upload button on the right;
- Add 0r modify Room Addresses;
  - Refer to the [dedicated section below](#room-addresses)).
- Publish this room to the public in openscience.ca's room directory?;
  - Read the [#room-addresses section](#room-addresses) below.
- Enable URL previews for everyone by default or for you;
  - In encrypted rooms, URL previews are disabled by default to ensure that the
    our server (where the previews are generated) cannot gather information
    about links you see in these rooms.

#### Room addresses

Every room has a so-called _internal room ID_ that looks like
`!JbwMKWxduJCSMqzHWp:openscience.ca`. Because this cryptic address can not be
read nor easily remembered by humans, custom room addresses can be assigned.
While you can always view the _internal room ID_ in the **Advanced** tab, you
can assign in parallel a local room address in the **General** tab, which is
even more important when we want to [share]({{% relref "share" %}}) a room.

The assigned local room address can then easily be distributed in public or to
the target group and has the following structure:
`#room-address:openscience.ca`.

This is only necessary for rooms you want to make public and reference in other
places which would look like this: `#support:openscience.ca` instead of
`!JbwMKWxduJCSMqzHWp:openscience.ca`.

To assign a local address, you have to click on _"Show more"_ under _"Local
Addresses"_.

Room addresses can be published **locally** with a local address within the
openscience.ca's, which is only valid within the matrix home server for
openscience.ca or **globally** (findable by users in other servers - useful for
topics beyond Open Science), which will make the _local address_ to a _main
address_ as well.

### Security & Privacy tab

Room administrators have to make 3 important decisions:

#### Should the room be encrypted?

If for a reason you want to enable encryption from now on, this is the button
you can use to do it. There is chance of reverting it once encryption is
enabled, so think carefully before acting.

{{% notice note %}} The end-to-end encryption of large or public spaces is
critical in terms of the difficult verification. See [Use end-to-end
encryption]({{< relref "encryption" >}}). {{% /notice %}}

#### Who is allowed access?

There are 3 options:

1. **Only people who have been invited**: These are closed/private rooms. Access
   at the moment only by explicit invitation by moderator:inside or
   administrator:inside
2. **Everyone who knows the room's link, apart from guests**: This is a public
   room, but you can only read it if you enter it (and thus become visible to
   all room members). Here you can see exactly who is in the room and when. If
   necessary, you can use the admin tools to control the access (kick and ban
   people who should not be in the room).
3. **Everyone who knows the room's link, including guests**: This is a public
   room, and everyone can read it. All over the world. And room members will
   never know who read it and when. So this is like a website where everyone can
   take notes. This setting often goes along with the option that "everyone" can
   read the chat history.

A "call waiting" to closed rooms is not yet possible. The closest workaround is
to send a direct message to the room administrator, who will then invite you.

#### And who can read the chat history?

There are 4 options:

- **Anyone**
- **Members only (since the point in time of selecting this option)**
- **Members only (since they were invited)**
- **Members only (since they joined)**

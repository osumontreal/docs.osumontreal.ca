---
title: "Element Web (Browser)"
titlehide: true
draft: false
chapter: false
weight: 10
---

# Using the [Element](https://chat.openscience.ca) Web client

In order to use our Element Web client, you have to go
[https://chat.openscience.ca](https://chat.openscience.ca).

{{% notice info %}} Unless you have already registered with another matrix
server and know how to join our server through the federation, the first time
you use our service, you will have to register by clicking on
"[Create Account](https://chat.openscience.ca/#/register)" on the homepage
[https://chat.openscience.ca](https://chat.openscience.ca).

If you require help during the registration process, you can refer to the [First
steps]({{% ref "matrix/first-steps" %}}) section.

Analogous to e-mail addresses, this results in matrix addresses with the
following structure: `@USERNAME:openscience.ca`

{{% /notice %}}

## Sign in process

1. Click on the blue _Sign in_ button.
2. The default option is to enter your _Username_, but you can change the
   _Username_ option for the email address you signed up with or your phone
   number, via the drop-down menu "_Sign in with:_". We recommend leaving it to
   the default option, namely _Username_. Then the following entries must be
   made:
3. Enter your username and password
4. Click on _Sign In_
5. You are now signed in, congratulations! :tada:

{{% notice warning %}} If you want to immediately start using a [Matrix
Client]({{< relref "../clients" >}}) instead of the above mentioned website
(Element Web-App installed at openscience.ca), it is important to change the
home server from the default matrix.org server to https://matrix.openscience.ca
{{% /notice %}}

## Browser settings

### Browser selection

Recommended are the browsers [Firefox](https://www.mozilla.org/de/firefox/new/),
[Chromium](https://www.chromium.org/getting-involved/download-chromium), newer
versions of MS Edge (based on Chromium). Older or unsuitable browsers may only
show a white page.

### NoScript

Many people use script blockers to protect themselves from
[Tracking](https://ofaolain.com/blog/2018/04/23/tracker-blocking-with-noscript-and-privacy-badger/)
and malware in the browser, for example with the addon
[NoScript](https://addons.mozilla.org/de/firefox/addon/noscript/). Here you have
to make the following settings (for the integration manager, e.g.
Jitsi/Etherpad)

<!-- ![Browser plugin settings NoScript with openscience.ca and vector.im selected as trusted script sources](/images/10_Sicherheit2_en.png) -->

### Cookies

You will allow cookies from

- openscience.ca
- vector.im (for the integration and app manager)
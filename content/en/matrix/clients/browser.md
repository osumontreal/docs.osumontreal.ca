---
menutitle: "Element Web (Browser)"
title: Using our Element Web client
draft: false
weight: 10
---

In order to use our Element Web client, you have to go
[https://chat.openscience.ca](https://chat.openscience.ca).

{{% notice info %}} The first time you use our service, you will have to
register by clicking on
"[Create Account](https://chat.openscience.ca/#/register)" on the chat homepage
[https://chat.openscience.ca](https://chat.openscience.ca) unless you have
already registered with another matrix server and know how to join our server
through the federation.

If you require help during the registration process, refer to the [First
steps]({{% ref "matrix/first-steps" %}}) section.

{{% /notice %}}

If you are registered, you can skip the registration process section and read
the [Sign in section below](#sign-in) to make sure to use your existing account
**on our server** and not create a new account on another server like
matrix.org.

## Register using the Element Web App

1. Open the Element Web App @ <https://chat.openscience.ca>;
1. Click on the green _Create Account_ button;
1. Fill in the form.
   - Choose your username carefully since it is not possible to change it. We
     recommend using your `FirstLastname` but you are free to pick any username
     that complies with our Code of Conduct.
   - Analogous to e-mail addresses, this results in matrix addresses with the
     following structure: `@USERNAME:openscience.ca`
   - E-mail address are mandatory on our server, this is to ensure you can reset
     your password at anytime.
1. Click on the _Register_ button.
1. Voilà, you should now be signed in to the Matrix 🌐!

## Sign in

1. Click on the blue _Sign in_ button.
1. The default option is to enter your _Username_, but you can change the
   _Username_ option for the email address you signed up with via the drop-down
   menu "_Sign in with:_". We recommend leaving it to the default option, namely
   _Username_.
1. Enter your username and password
1. Click on _Sign In_
1. You are now signed in, congratulations! :tada:

{{% notice warning %}} If you want to immediately start using another [Matrix
Client]({{< relref "../clients" >}}) instead of the Element Web client installed
at chat.openscience.ca, it is important to change the home server from the
default matrix.org server to https://matrix.openscience.ca {{% /notice %}}

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

<!-- ![Browser plugin settings NoScript with openscience.ca and vector.im selected as trusted script sources](.png) -->

### Cookies

You may also want to allow cookies from the 2 sites below for a smoother
experience.

- openscience.ca
- vector.im (for the integration and app manager)

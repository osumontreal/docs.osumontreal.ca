---
menutitle: First steps
title: First steps - How to use Matrix?
chapter: false
draft: false
weight: 2
---

- [1. How to register?](#1-how-to-register)
  - [Registration process through our Web App (browser)](#registration-process-through-our-web-app-browser)
  - [Registration through the Element Desktop or Mobile App](#registration-through-the-element-desktop-or-mobile-app)
- [2. How to use?](#2-how-to-use)
  - [How to sign in using our Web app (browser)?](#how-to-sign-in-using-our-web-app-browser)
  - [Element Web client](#element-web-client)
  - [Element Desktop client](#element-desktop-client)
  - [Element Phone client](#element-phone-client)
- [3. Crucial information to know](#3-crucial-information-to-know)
  - [Convenient use of end-to-end encryption (E2EE)](#convenient-use-of-end-to-end-encryption-e2ee)

## 1. How to register?

There are many ways to join our server. You can create an account as described
below using either a browser, a desktop app or a mobile app. For more advanced
users who already have a Matrix account on another server that is globally
federated, they can find rooms they would like to join from their server
:exploding_head:.

Instruction to create an account from the [different client
Apps]({{% relref "/matrix/clients/_index.md" %}}) are listed below and in their
respective section of this documentation, which also includes more details
regarding the installation and usage of each app.

- [Web App (browser)]({{% relref "/matrix/clients/browser.md" %}}) section
- [Desktop App]({{% relref "/matrix/clients/desktop.md" %}}) section
- [Mobile App]({{% relref "/matrix/clients/mobile.md" %}}) section

{{% notice info %}}

**When you register, keep these points in mind:**

- **Choose your username carefully** as it is not possible to change it. We
  recommend using your `FirstLastname` but you are free to pick any username
  that is compliant with our Code of Conduct.
- Analogous to e-mail addresses, matrix addresses have the following structure:
  `@USERNAME:openscience.ca`
- An e-mail address is mandatory to register on our server to ensure you can
  reset your password at anytime. It won't be shared with anyone, we don't
  directly have access to it.

{{% /notice %}}

### Registration process through our Web App (browser)

The easiest way to create an account is by far through the Element Web App the
we provide:

1. Open the Element Web App @ <https://chat.openscience.ca>;
1. Click on the green _Create Account_ button;
1. Fill in the form.
1. Click on the _Register_ button.
1. Voilà, you are now signed in to the Matrix 🌐!

### Registration through the Element Desktop or Mobile App

1. [Download and install the Desktop and/or Mobile
   App]({{% relref "/matrix/clients/" %}})
2. Open the Element Desktop or Mobile App;
3. Click on the green _Create Account_ button;
4. **Click on _Change_ and enter our custom homeserver:
   `https://matrix.openscience.ca`**
5. Fill in the form.
6. Click on the _Register_ button.
7. Voilà, you are now signed in to the Matrix 🌐!

## 2. How to use?

{{% notice tip %}} We recommend using the official [Element
client]({{% relref "/matrix/clients/_index.md" %}}) as it is the official client
developped by the Matrix core team and the only one we officially support.

{{% /notice %}}

### How to sign in using our Web app (browser)?

1. Open your favorite browser and go to
   [https://chat.openscience.ca](https://chat.openscience.ca)
1. Click on the blue _Sign in_ button.
1. The default option is to enter your _Username_, but you can change the
   _Username_ option for the email address you signed up with via the drop-down
   menu "_Sign in with:_". We recommend leaving it to the default option, namely
   _Username_.
1. Enter your username and password
1. Click on _Sign In_
1. You are now signed in, congratulations! :tada:

{{% notice tip %}} If you want to immediately start using another [Matrix
Client]({{< relref "../clients" >}}) instead of the Element Web client installed
at [chat.openscience.ca](https://chat.openscience.ca), it is important to change
the home server from the default matrix.org server to
https://matrix.openscience.ca {{% /notice %}}

### Element Web client

In order to use our Element Web client, you have to go
[https://chat.openscience.ca](https://chat.openscience.ca). To use the Element
Web client we provide, see the guide under [clients :right_arrow:
Browser]({{< ref "../clients/browser" >}}).

### Element Desktop client

Downloads for:
{{% button href="https://packages.riot.im/desktop/install/win32/x64/Element%20Setup.exe" icon="fas fa-download" %}}Windows{{% /button %}}
{{% button href="https://packages.riot.im/desktop/install/macos/Element.dmg" icon="fas fa-download" %}}macOS{{% /button %}}
{{% button href="/matrix/clients/install_linux" icon="fas fa-download" %}}Linux{{% /button %}}

To use the Element Desktop App, see the guide under [clients :right_arrow:
Desktop]({{< ref "../clients/desktop" >}}).

### Element Phone client

<!-- prettier-ignore -->
Downloads for:
{{% button href="https://play.google.com/store/apps/details?id=im.vector.app" icon="fas fa-download" %}}Android (Google Play){{% /button %}}
{{% button href="https://apps.apple.com/app/vector/id1083446067" icon="fas fa-download" %}}iOS (iPhone/iPad){{% /button %}}
{{% button href="https://f-droid.org/packages/im.vector.app/" icon="fas fa-download" %}}Android (F-Droid){{% /button %}}

To use the Element Mobile App, see the guide under [clients :right_arrow:
Desktop]({{< ref "../clients/mobile" >}}).

## 3. Crucial information to know

Because we believe in your privacy, all unpublished or private rooms (just like
all new 1:1 conversations) have [end-to-end
encryption]({{< relref "encryption" >}}) enabled by default.

**Encryption** means scrambling a message in such a way that only those knowing
the _"secret key"_ can unscramble it. Matrix uses encryption to keep your
messages and files private.

### Convenient use of end-to-end encryption (E2EE)

Matrix not only encrypts transports to and from the home server (located in
Montreal, Canada) but also allows the use of end-to-end encryption (E2EE). For
this, cryptographic keys have to be exchanged between all devices that want to
write end-to-end encrypted. This technical necessity sounds and is complicated,
but in the meantime it has become very convenient for the users.

When E2EE is enabled, messages can only be read by the participants in the
conversation and nobody else. This means messages can't be read by the
maintainers of the server, or by any other third party. **It also means that if
you lose your keys, you won't be able to read your messages either. So, back
them up.**

The cryptographic keys created by the client are stored on the respective
device. If this is a tab in a browser, for example, there is a risk that this
tab will be closed unintentionally. Then all encrypted contents are no longer
readable. To prevent this from happening, a key protection is offered on our
home server, on which (protected with a security phrase (or security key that
can be calculated from it) all cryptographic keys are stored encrypted.

{{% notice info %}} It is highly recommended to read more about [encryption in
its own dedicated section]({{< relref "encryption" >}}) to prevent unforeseen
damage! {{% /notice %}}

---
title: "Element Desktop"
draft: false
weight: 20
---

Downloads for:
{{% button href="https://packages.riot.im/desktop/install/win32/x64/Element%20Setup.exe" icon="fas fa-download" %}}Windows{{% /button %}}
{{% button href="https://packages.riot.im/desktop/install/macos/Element.dmg" icon="fas fa-download" %}}macOS{{% /button %}}
{{% button href="/clients/install_linux" icon="fas fa-download" %}}Linux{{% /button %}}

{{% notice info %}} After installing the Element Desktop client, you will have
to register if you have not registered yet. As said in the previous sections,
the first time you use our service, you have to register unless you have already
registered with another matrix server and know how to join our server through
the federation.

If you require help during the registration process, refer to the [First
steps]({{% ref "matrix/first-steps" %}}) section.

{{% /notice %}}

If you are registered, you can skip the registration process section and read
the [Sign in section below](#sign-in) to make sure to use your existing account
**on our server** and not create a new account on another server like
matrix.org.

### Registration process through the Element App

1. Open the Element Desktop App;
1. Click on the green _Create Account_ button;
1. Click on **Change** and enter the custom homeserver:
   `https://matrix.openscience.ca`
1. Fill in the form. Choose your username carefully since it is not possible to
   change it. We recommend using your `FirstLastname` but you are free to pick
   any username that complies with our Code of Conduct.
   - Analogous to e-mail addresses, this results in matrix addresses with the
     following structure: `@USERNAME:openscience.ca`
   - E-mail address are mandatory on our server, this is to ensure you can reset
     your password at anytime.
1. Click on the _Register_ button.
1. Voilà, you should now be signed in to the Matrix 🌐!

### Sign in

1. Click on the blue _Sign in_ button;
1. To not accidentally end up on the wrong server (matrix.org), click on
   **Change** and manually specify the home server:
   `https://matrix.openscience.ca`;
1. Click Next and enter your credentials. The default option is to enter your
   _Username_, but you can change the _Username_ option for the email address
   you signed up with via the drop-down menu "_Sign in with:_". We recommend
   leaving it to the default option, namely _Username_.
1. Enter your username and password
1. Click on _Sign In_
1. You are now signed in, congratulations! :tada:
1. By activating the slider under Settings > Settings > "**Automatic start after
   system login**", the Element client will start after every reboot and you
   will no longer miss any notifications due to accidentally closing the browser
   tab.

{{% notice tip %}} There are many useful, additional settings and
recommendations described in the [Settings]({{% relref "../settings" %}})
section that will make you life easier :smile: {{% /notice %}}

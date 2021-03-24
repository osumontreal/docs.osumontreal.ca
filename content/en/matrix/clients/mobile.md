---
title: "Element Mobile"
draft: false
chapter: false
weight: 30
---

<!-- prettier-ignore -->
Download the Element app for your platform:
{{% button href="https://play.google.com/store/apps/details?id=im.vector.app" icon="fas fa-download" %}}Android (Google Play){{% /button %}}
{{% button href="https://apps.apple.com/app/vector/id1083446067" icon="fas fa-download" %}}iOS (iPhone/iPad){{% /button %}}
{{% button href="https://f-droid.org/packages/im.vector.app/" icon="fas fa-download" %}}Android (F-Droid){{% /button %}}

{{% notice info %}} After installing the Element Mobile client, you will have to
register if you have not registered yet. As said in the previous sections, the
first time you use our service, you have to register unless you have already
registered with another matrix server and know how to join our server through
the federation.

If you require help during the registration process, refer to the [First
steps]({{% ref "matrix/first-steps" %}}) section.

{{% /notice %}}

If you are registered, you can skip the registration process section and read
the [Sign in section below](#sign-in) to make sure to use your existing account
**on our server** and not create a new account on another server like
matrix.org.

## Registration process through the Element Mobile App

1. Open the Element Mobile App;
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

## Sign in

1. Open the Element Mobile App
1. Click on _Get Started_
1. Choose _Other - Custom & advanced settings_
   - This ensures you do not accidentally end up on the wrong server
     (matrix.org).
1. Set the address server to: `https://matrix.openscience.ca` and click on
   _Continue_.
1. Enter your credentials. The default option is to enter your _Username_, but
   you can change the _Username_ option for the email address you signed up with
   via the drop-down menu "_Sign in with:_". We recommend leaving it to the
   default option, namely _Username_.
1. Click on _Sign In_
1. You are now signed in, congratulations! :tada:

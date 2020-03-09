---
layout: post
title: "Keybase: the new way to keep your online accounts secure"
---

![](/img/Screenshot_2020-03-09_18-22-04.png)

Are you ever worried that someone will hack your social media accounts
and they will be able to steal your identity? Well, with Keybase they
will not be able to.

Keybase uses a combination of PGP and device keys to make sure that even
if someone knows the password to your keybase account, they will not be
able to take over your account. Of course take control of your account
if they have one of your devices or paper keys, but those should be well
protected. Keybase makes a signed keychain for each user, essentially
your own blockchain of proof that you own your other accounts.

Since your Keybase proofs and keychain are both public, anyone can use your
public key to verify them, and will not have to trust Keybase. In fact, if
Keybase is hacked, an attacker would not be able to add something to your
keychain because Keybase does not have your public key to be able to sign
things into your keychain.

Now that we have talked about how Keybase is so secure, let's talk about
how it can verify your accounts. When you want to verify an account,
Keybase will sign a proof into your keychain, and to verify that you
are the owner of the account. Then you will also have to post the proof in a
public place from that account to verify you are the owner. As a result
anyone will be able to verify your identity, and you can revoke the proof
if you lose the account.




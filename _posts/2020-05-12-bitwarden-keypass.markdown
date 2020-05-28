---
layout: default
title:  "Bitwarden v Keypass"
date:   2020-05-12 13:53:00 +0000
categories: security bitwarden keypass
---

# Summary

I have been a long time Keepass user, recently looking at Bitwarden following some recommendations.

These are my thoughts. (Notes for now, will add details over time)

# Bitwarden

## Pro

* cool look.
* integrations with Andriod / Windows.
* support Card type fields.

## ConyG

Cons are **_all_** of the Pro in Keepass.
 
# Keepass

## Pro

* quick launch CTRL-ALT-K to launch, CTRL-E to get to edit.
* plugins, e.g. rdp connections can be configured to launch, logged in with CTRL-U.
  * configured for `rdp://` url
* shortcut keys:
  * quick launch CTRL-ALT-K to launch.
  * CTRL-E to quickly jump to Search field.
* search does not search password fields for pattern.
* search does not search note fields.
* form fill: In Keepass, matching defaults are pre-inserted into user/pass login fields, in Bitwarden I still need to mouse all the way up to top-right of browser and click the Bitwarden icon and then click the matching entry.
  * 2020-05-28, found experimental feature that enables this, working fine so far.
* Auto-type, CTRL-V in Keepass will auto-type the user password into the login page. The auto-type can be customised per site.

## Con

  * Pretty poor integration with web. Kee does a good job, but is 3rd party.

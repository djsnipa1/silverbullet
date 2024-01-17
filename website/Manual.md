Welcome to wonderful world of SilverBullet. The goal of this manual is to give you a broad sense of how to use this tool and what it’s capable of. However, its full capabilities are yet to be discovered. You too may find new and creative ways to use the various SilverBullet features in ways nobody previously thought of.

However, that is all unlikely to happen unless you understand what SilverBullet can actually do. So let’s give you a bit of a sense.

# Keeping up-to-date
* [[CHANGELOG]]: what’s new in SilverBullet? This page will give you the latest details. It’s worth monitoring this page.

# Installation and deployment
The biggest hurdle to get over with SilverBullet is that you need to get this thing running. And as of yet, the only way to do that is to install and deploy it yourself. 🤷

* [[Install]]: Installation instructions for various setups
* [[Deployments]]: various deployment options
* [[Authelia]]: configuring SilverBullet with [Authelia](https://www.authelia.com/) authentication.
* [[Guide/Deployment/Cloudflare and Portainer]]: configuring SilverBullet with a Cloudflare tunnel, portainer and optional Cloudflare zero trust authentication.

# User interface
SilverBullet’s UI is minimalist by design. Let’s look at the few UI elements and how to use them.

* The [[Top Bar]] contains:
  * [[Page Namer]]
  * [[Client Modes]] (the 🔄 button)
  * [[Index Page]] (the 🏠 button)
  * [[Page Picker]]
  * [[Command Palette]]
* The main [[Editor]] component contains your page’s text, as well as potentially:
  * [[Table of Contents]] 
  * [[Linked Mentions]]

# Core Concepts
These are the core concepts used in SilverBullet:
* [[Spaces]]
* [[Pages]]
  * [[Frontmatter]]
  * [[Page Name Rules]]
* [[Folders]]
* [[Attachments]]
* [[Templates]]

# Editing and Formatting
* Content is written using [[Markdown]] and rendered using [[Live Preview]]
  * Markdown [[Markdown/Basics]]
  * Markdown [[Markdown/Extensions]]
    * [[Markdown/Admonitions]]
    * [[Plugs/Tasks]]
    * [[Markdown/Syntax Highlighting]]
    * [[Markdown/Code Widgets]]
* [[Slash Commands]]
* [[Outlines]]

# Navigation
The main ways to roam your space, beside following page links, are:
* [[Page Picker]]
* [[Linked Mentions]]
* [[Full Text Search]]

# Advanced topics
* [[Objects]]
  * [[Frontmatter]]
  * [[Attributes]]
* [[Live Queries]]
* [[Templates]] and [[Live Templates]]
* [[Federation]]: it possibly to “sync in” content from outside sources, such as [[Template Sets]]

# Extending SilverBullet
A lot of SilverBullet’s functionality is built as [[Plugs]] using the robust [[PlugOS]] extension mechanism. If you are adventurous you can try to build [[Plugs/Development|such plugs yourself]].

# Contributing
SilverBullet is free and open source software. You can contribute to it [via Github](https://github.com/silverbulletmd/silverbullet). For some details on how to do this, have a look at [[Development]].

# Personalization
Want to tweak something? [[SETTINGS]] gives you a few settings you can tweak.

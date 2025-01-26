---
tags:
  - help
  - issue
  - problem
  - trouble
  - missing
---

# Help Centre

Having trouble experiencing Zen? We're here to help. If these articles don't resolve your issue, please don't hesitate to post on the [Help Forum](https://zen.anekodot.lol/community/forums/5) or make a ticket in our Discord!

## Sections {id=sections}

Choose the section that matches your problem the most to find a suitable solution to the issue.

| Section | Area of focus |
| :-- | :-- |
| [Account](/wiki/Help_centre/Account) | zen!supporter, sign-in and access recovery, name changes, profile data |
| [Account restrictions](/wiki/Help_centre/Account_restrictions) | All about restrictions: overview, appeal process, common reasons and cooldowns |
| [Tournament bans](/wiki/Help_centre/Tournament_bans) | All about tournament bans: overview, common reasons, and cooldowns |
| [Website](/wiki/Help_centre/Website) | Blocking users, contacting with the support, site appearance |

## Help us help you {id=diagnostics}

### Log files {id=log-files}

**Log files are our client's way of saying what caused the issue you're experiencing.**

Log files help us figure out what exactly went wrong, and gives us the info we need to help you! Here's how to get them: 

**NOTE: These files can contain potentially sensitive information about your account or computer. Please don't share these with people outside the the zen!Staff team unless you know what you're looking for when going through the file.**

#### **TODO**

### Event Viewer {id=event-viewer}

**Event Viewer is a built in component of Windows which can be used to find crash logs when osu! does not provide you with any. These crash logs can be used to help determine what is causing your issue.**

When having problems with osu! crashing, if osu! doesn't give you a crash log the only place to find one is through Event Viewer.

If a support team member has asked you to find a crash log in Event Viewer, here's how to do it:

1. After osu! has crashed, press `Win` + `R` to open the run box.
2. In the run box type `eventvwr` and press `Enter`. This will open the Event Viewer.
3. In Event Viewer, on the left, click `Windows Logs` and then `Application`.
4. On the right, click `Filter current log`.
5. On the filter window that opens, make sure you have the `Error` box checked and click `OK`.
6. Press `Ctrl` + `F` and type osu! in the find box. It will find the first crash log from osu!.
7. Go into the `Details` tab, expand `System` and `Event Data` by clicking on each of them.
8. Copy the text from there and paste it into your support ticket or forum post.

### Frame Time Graph {id=frame-time-graph}

**The Frame Time Graph is a feature of osu! that can help us gather more useful information on performance issues you may be experiencing.**

#### **TODO**
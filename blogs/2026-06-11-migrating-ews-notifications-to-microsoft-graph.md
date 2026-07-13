---
title: "Migrating EWS notifications to Microsoft Graph"
url: "https://devblogs.microsoft.com/microsoft365dev/migrating-ews-notifications-to-microsoft-graph/"
date: "2026-06-11"
author: "Microsoft Graph team"
feed_url: "https://devblogs.microsoft.com/microsoft365dev/feed/"
---
Migrating from the Exchange Web Services (EWS) notification framework, which supports push, pull, and streaming notification types, to the Microsoft Graph subscription model represents a transition toward a unified, stateless, and event-driven framework. This framework supports more than just Exchange data. Although Microsoft Graph streamlines notifications through webhooks, replacing the varied EWS push, pull, and long-lived connection models requires an architectural redesign.

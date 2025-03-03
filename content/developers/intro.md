---
title: Introduction
weight: -10
---

This documentation is for application developers who want to use the UnifiedPush library.

If you want to write a new distributor, please refer to the [definitions](/spec/definitions/) and the [specifications](/spec/android/). You may also want to look at the code of [NoProvider2Push](/users/distributors/np2p/), which is mostly only UnifiedPush related code.

Reading [the definitions](/spec/definitions/) may help you to understand this part.

The UnifiedPush libraries, also named **Connector** are the libraries that connect to the distributor. They follow [the specifications](/spec/android/) and are able to list available distributors, choose a distributor, register the application to that distributor, receiving new endpoint, receiving messages, being notified when unregistered.

If you want to let users choose how to receive notifications using UnifiedPush but, you also want a Firebase Cloud Messaging backup when the users don't have any distributor, you can use add the [**embedded FCM distributor**](/developers/embedded_fcm/).

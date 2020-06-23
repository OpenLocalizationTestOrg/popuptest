---
title: Add authentication to your bot via Azure Bot Service | Microsoft Docs
description: Learn how to use the Azure Bot Service authentication features to add SSO to your bot.
author: JonathanFingold
ms.author: JonathanFingold
manager: kamrani
ms.topic: article
ms.service: bot-service
ms.date: 10/04/2018
---

# Add authentication to your bot via Azure Bot Service

[!INCLUDE [pre-release-label](includes/token_test.md)]  

This tutorial uses new bot authentication capabilities in Azure Bot Service, providing features to make it easier to develop a bot that authenticates users to various identity providers such as Azure AD (Azure Active Directory), GitHub, Uber, and so on. These updates also take steps towards an improved user experience by eliminating the _magic code verification_ for some clients.

Prior to this, your bot needed to include OAuth controllers and login links, store the target client IDs and secrets, and perform user token management.
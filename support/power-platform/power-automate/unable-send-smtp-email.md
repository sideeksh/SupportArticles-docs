---
title: Unable to send SMTP Email
description: Provides a solution to an error that occurs when  try to send mails via your own SMTP server from a newly created Flow app.
ms.reviewer: 
ms.topic: troubleshooting
ms.date: 3/31/2021
ms.subservice: power-automate-flows
---
# Unable to send SMTP Email

This article provides a solution to an error that occurs when  try to send mails via your own SMTP server from a newly created Flow app.

_Applies to:_ &nbsp; Microsoft Dynamics 365  
_Original KB number:_ &nbsp; 4535859

## Symptoms

You try to send mails via your own SMTP server from a newly created Flow app, but you meet a problem while setting up the connection.

## Cause

SSL (Secure Sockets Layer) connection isn't enabled.

## Resolution

To fix this issue, you could request to enable the SSL connection and check the security settings for your account. If you enabled two-step verification, try using your app password. Otherwise, enable access for less secure apps.

:::image type="content" source="media/unable-send-smtp-email/smtp-setting.png" alt-text="Screenshot to enable the S S L connection in the S M T P setting.":::

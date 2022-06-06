---
layout: page
#
# Content
#
subheadline: "Preliminary Work"
title: "What should verbal consent look like for voice assistants?"
teaser: "Determining how voice assistants should broker consent to share data with third party software has proven to be a complex problem. Alexa now offers “voice-forward consent”, allowing users to grant skills access to personal data mid-conversation using speech. While more usable and convenient than current alternatives, asking for consent 'on the fly' can undermine several concepts core to the informed consent process. The intangible nature of voice interfaces further blurs the boundary between parts of an interaction controlled by third-party developers from the underlying platforms. We outline a research agenda towards usable and effective voice-based consent to address the problems with brokering consent verbally, including our own work drawing on the GDPR and work on consent in Ubicomp."
categories:
  - publications
tags:
  - publications
#
# Styling
#
header: no
image:
    title: stock-alexa.jpg
    thumb: stock-alexa.jpg
    homepage: stock-alexa.jpg
    caption: Photo by The-Unwinder (CC-BY-SA)
    caption_url: https://www.flickr.com/photos/the-unwinder/
mediaplayer: false
author: wseymour
---
Read the full paper [here](https://arxiv.org/abs/2204.10058).

A vital aspect of the software marketplaces available on today's smart devices, including voice assistants (VAs), is the way that sharing of personal data with third parties is managed. Consent has emerged as the primary means of managing this relationship with skill developers, and is intended to allow users to decide for themselves what they are willing to share when using third party skills. The growing ubiquity and pervasiveness of these devices - that are often able to listen to everything said in the home - mirrors wider concerns in the Ubicomp community around the information on which users are expected to decide whether or not to grant consent.

Unsurprisingly, designing mechanisms to broker consent for data sharing between users of voice assistants and third-party skills has proven to be somewhat of a wicked problem. When using a skill that requires permission to access personal data, Alexa and Google Assistant direct users to grant access in the companion smartphone app. This mirrors the flow of managing permissions on smartphone apps that was once commonplace, where consent would be granted in the app store at the threshold of use. But directing users of a hands-free device that can be used anywhere within earshot to manually interact with a specific device leads to a poor user experience. Last year, Amazon introduced "voice-forward consent" (VFC) for Alexa, allowing developers to request consent for data sharing mid-conversation using speech. On the face of it this not only reduces friction in the user experience, but mirrors the shift seen in smartphone apps towards asking for permissions 'just in time'.

But the key difference between smartphones and voice assistants - the use of speech as an interaction modality - fundamentally changes the nature of the consent-granting process. In this position paper we outline a research agenda for developing usable and effective voice-based consent for voice assistants, including our own early-stage work on the ethical issues around verbal consent for voice assistants. In this work we draw on literature from HCI and Ubicomp, as well as key data protection regulations including the European General Data Protection Regulation (GDPR), in order to distil out guidelines for ethical verbal consent in voice assistants and other similar technologies. A key motivation for this work is promoting transparency around data collection and use within voice assistant ecosystems; VAs already suffer from a lack of transparency due to the use of speech as an interaction modality, and this is further impacted by a fragmented user experience across assistants, companion apps, and web interfaces.

---
title: Identity integration overview
description: Independent Software Vendors (ISVs) can integrate their solutions with Azure Active Directory to adopt a Zero Trust model and provide solutions that keep their customers secure in a hybrid and cloud environment. In this way ISVs can support the Zero Trust principles of verify explicitly, use least privileged access, and assume breach, and save their customers the significant time required to implement a solution on their own.
ms.date: 04/20/2021
ms.service: security
author: knicholasa
ms.author: nichola
ms.topic: conceptual
---

# Identity integration overview

:::image type="icon" source="../media/icon-identity-medium.png":::

The modern workplace has changed. Applications have moved into the cloud and employees need to work from home, use their own devices, and collaborate with partners who are outside of their organization. Companies can no longer rely on traditional network security solutions that assume everyone is working in a protected corporate environment. Instead, they must implement solutions that support hybrid and cloud-first work environments.

Independent Software Vendors (ISVs) can integrate their solutions with Azure Active Directory to adopt a Zero Trust model and provide solutions that keep their customers secure in a hybrid and cloud environment. In this way ISVs can support the Zero Trust principles of verify explicitly, use least privileged access, and assume breach, and save their customers the significant time required to implement a solution on their own.

## Identity integrations with Azure Active Directory

Identities represent people, services, and devices and the permissions that they obtain to access protected data. Identity solutions are the key control plane for managing access in the modern workplace and are essential to implementing a Zero Trust architecture. Identity solutions enable customers to verify explicitly using strong authentication and access policies, use least privileged access with granular permission and access, and assume breach with controls and policies that manage access to secure resources and minimize the blast radius of attacks.

Azure Active Directory (Azure AD) is Microsoft’s cloud enterprise identity service. It provides single sign-on authentication, conditional access, passwordless and multi-factor authentication, automated user provisioning and many more features that enable companies to protect and automate identity processes at scale.

As an ISV, you can integrate with many of Azure AD’s features by using [Microsoft Graph](/graph/overview) and the [Microsoft identity platform](/azure/active-directory/develop/app-resilience-continuous-access-evaluation). You can also gain access to the risk signals Azure AD calculates based on myriad data sources and policies and feed your own information back into the system to create a safer environment for all.


:::image type="content" source="../media/diagram-conditional-access-policies-small.png" alt-text="Diagram of conditional access, showing machine learning, policies, and a real time evaluation engine making decisions about how to allow access." lightbox="../media/diagram-conditional-access-policies-white-background.png":::

In addition, there are other ways to provide value on top of Azure AD - such as publishing your app to the Azure AD gallery or becoming an approved passwordless hardware vendor.

## Integration guidance

We have included the following guidance to help you on the journey to integrating your solutions with Azure AD. We have also included examples of existing partnerships that have allowed Microsoft and strategic partners to build strong solutions together.

<br/>
<table border="0">
   <tbody>
      <tr>
         <td>
            <p><strong>Getting started with Zero Trust identity integrations</strong> </p>
            <p>How to get started integrating with Azure AD on Zero Trust identity solutions</p>
         </td>
      </tr>
      <tr>
         <td>
            <p><strong>Secure hybrid access integrations</strong> </p>
            <p>Create solutions that provide modern cloud authentication for legacy on-premises applications </p>
         </td>
      </tr>
      <tr>
         <td>
            <p><strong>Become a Microsoft-compatible FIDO2 security key vendor</strong> </p>
            <p>Partner with Microsoft to enable hardware based authentication solutions for customers</p>
         </td>
      </tr>
    </tbody>
</table>

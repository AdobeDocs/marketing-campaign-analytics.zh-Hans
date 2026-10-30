---
title: 管理
description: 了解如何管理Marketing Campaign Analytics。
feature: Administration
exl-id: 76d6d15d-a838-4ee2-9929-e55ea8946b80
autotag-review: '2026-05-01T09:07:55.299Z'
TQID: 'https://experienceleague.adobe.com/GZOR-NsylnAmpFEuZNDpvF0Br8eL-HKGYIPUBs00sNQ'
product_v2:
  - id: b88c80e3-31df-4609-989d-d4dac0e6d973
    internal-label: Marketing Campaign Analytics
feature_v2:
  - id: a567f0f7-0057-4079-8ded-5b24cc25af15
    internal-label: Harmonized data
  - id: d822825b-9821-40d5-9b0d-42a9e3f317c5
    internal-label: Plans
  - id: e0abf868-dae2-4c1c-83e9-b21799232845
    internal-label: Datasets
  - id: f40f1683-8300-4054-aab8-77da06ad63ff
    internal-label: Models
  - id: f6633d1c-3d2d-4f48-95d4-4bbc9913db52
    internal-label: Data governance
  - id: fbd94e4b-f9b8-42a4-8df5-3f917aabae24
    internal-label: Schemas
  - id: fe2edbb1-46f9-4347-a27c-577cab3640cb
    internal-label: Administration
subfeature_v2:
  - id: abe9e290-7d2f-4131-b71e-ef9900865044
    internal-label: Access control
  - id: a6da0571-746e-4d59-89a4-7b691b1c3b9a
    internal-label: Architecture
role_v2:
  - id: b69b2659-1057-424e-8fc5-ed9e016dc554
    internal-label: User
  - id: c66ffd68-0f65-42bb-aa23-b4020f12e0bd
    internal-label: Admin
topic_v2:
  - id: b23e006f-0a29-4f1d-8fd0-77aa56f3d12b
    internal-label: Data modeling
  - id: c7d04a2c-412a-4c9d-9d7a-4456eaa5adeb
    internal-label: Governance
  - id: ebde5b41-29c9-4f5e-9ef6-1197e85409e3
    internal-label: Data management
  - id: eddd9b14-83bd-4ff4-9072-54a4a484abb7
    internal-label: Administration
  - id: f4e6943a-c91a-4134-a2c7-f4f20cfff2f0
    internal-label: Privacy
source-git-commit: 9d6bd798e97d36d49b7753dc9574b102efb3d6bf
workflow-type: tm+mt
source-wordcount: '201'
ht-degree: 6%
---
# 管理

{{mm-mca-rebranding}}

使用[Adobe Admin Console](https://helpx.adobe.com/cn/enterprise/using/admin-console.html)管理Marketing Campaign Analytics产品和用户。

要使Marketing Campaign Analytics正常运行，您必须设置正确的权限。

在Adobe Experience Cloud UI中：

1. 从左边栏中选择&#x200B;**[!UICONTROL ADMINISTRATION]**&#x200B;下的&#x200B;**[!UICONTROL Permissions]**。

1. 从左侧面板中选择![用户](/help/assets/icons/User.svg) **[!UICONTROL Roles]**。

1. 选择现有角色，或使用&#x200B;**[!UICONTROL Create role]**&#x200B;创建角色（例如，**Marketing Campaign Analytics**）。 如果选择现有角色，请选择![编辑](/help/assets/icons/Edit.svg) **[!UICONTROL Edit]**&#x200B;以编辑该角色的权限。 有关详细信息，请参阅[管理角色](https://helpx.adobe.com/cn/enterprise/using/admin-console.html)。

1. 确保您为角色选择了一个或多个沙箱。

1. 将&#x200B;**Adobe Marketing Campaign Analytics**&#x200B;资源添加到角色的资源列表中。

1. 请确保为您配置的角色选择正确的&#x200B;**[!UICONTROL Adobe Marketing Campaign Analytics]**&#x200B;权限。 您可以选择以下一个或多个角色：

   - **[!UICONTROL View Adobe Marketing Campaign Analytics Harmonized Data]**
   - **[!UICONTROL Manage Adobe Marketing Campaign Analytics Harmonized Data]**
   - **[!UICONTROL View Adobe Marketing Campaign Analytics Models Configuration]**
   - **[!UICONTROL Manage Adobe Marketing Campaign Analytics Models Configuration]**
   - **[!UICONTROL View Adobe Marketing Campaign Analytics Plans Configuration]**
   - **[!UICONTROL Manage Adobe Marketing Campaign Analytics Plans Configuration]**

     ![Marketing Campaign Analytics RBAC](/help/assets/mix-modeler-rbac.png)


1. 请确保为该角色选择其他权限。 例如，要查看或管理数据集和架构，您可以选择：

   - **[!UICONTROL Data Management]**：选择相关选项： **[!UICONTROL View Datasets]**&#x200B;或&#x200B;**[!UICONTROL Manage Datasets]**。

   - **[!UICONTROL Data Modeling]**：选择相关选项： **[!UICONTROL Manage Schemas]**&#x200B;或&#x200B;**[!UICONTROL View Schemas]**。

   <!--
    * **[!UICONTROL Data Governance]**: ensure you select **[!UICONTROL View User Activity Log]** and **[!UICONTROL View Data Usage Policies]**.
    -->

   <!--![Permissions](assets/permissions-including-privacy.png)-->

   选择&#x200B;**[!UICONTROL Save]**&#x200B;以保存权限。

1. 在&#x200B;**[!UICONTROL Role]**&#x200B;内的&#x200B;**[!UICONTROL Details]**&#x200B;中，添加相应的&#x200B;**[!UICONTROL Users]**&#x200B;或&#x200B;**[!UICONTROL User groups]**&#x200B;以授予用户访问Marketing Campaign Analytics的权限。

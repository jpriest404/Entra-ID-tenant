<h1>Creating an Entra ID Tenant</h1>

<h2>How To</h2>
<b>Step 1</b>
<br />
<br />
Select the Create a resource option in the Azure portal.
<p align="center">
<img src="https://imgur.com/ZxF1RQt.png" height="85%" width="85%" alt="Create a resource"/>
</p>

<b>Step 2</b>
<br />
<br />
Search for **Microsoft Entra ID** in the Create a resource page.

<sub>Please note that you have the option to select either Azure AD or Azure AD B2C tenants. If your goal is to develop applications that are externally-facing and allow sign-ins from both social and local accounts, you’ll need to establish an Azure AD B2C tenant. However, the subsequent steps will concentrate on Azure AD, not Azure AD B2C.</sub>
<p align="center">
<img src="https://imgur.com/fXeRgAt.png" height="85%" width="85%" alt="Search MS Entra ID"/>
</p>

<b>Step 3</b>
<br />
<br />
Select the **Create** option to create Microsoft Entra ID.
<p align="center">
<img src="https://imgur.com/tAX7vpR.png" height="85%" width="85%" alt="Create Entra ID"/>
</p>

<b>Step 4</b>
<br />
<br />
Select the **Next: Configuration** option.
<p align="center">
<img src="https://imgur.com/8DDoEm7.png" height="85%" width="85%" alt="Next: Configuration"/>
</p>

<b>Step 5</b>
<br />
<br />
Provide information such as the **organization name**, **initial domain**, and **country or region**. You cannot edit or delete the initial domain. You can add a customized domain name later.
<p align="center">
<img src="https://imgur.com/2dKidvl.png" height="85%" width="85%" alt="Configuration"/>
</p>

<b>Step 6</b>
<br />
<br />
Once your tenant is created, link it with a subscription. Navigate to your Microsoft Entra ID Overview Page in the Azure portal, select the Manage Tenants option, and proceed according to the provided instructions.
<p align="center">
<img src="https://imgur.com/WvZvGvM.png" height="85%" width="85%" alt="Configuration"/>
</p>

<h2>Summary</h2>
You’ve discovered that to construct applications that utilize the Microsoft identity platform for identity and access management, you require a Microsoft Entra ID tenant. For this purpose, you can either employ an existing Microsoft Entra ID tenant or establish a new one. You’ve also learned that you need to link the tenant with a subscription to begin using Microsoft Entra ID.
<!--

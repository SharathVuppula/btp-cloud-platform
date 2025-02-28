<!-- loioa6a00728e8c54efea8f7e60f6270b1d1 -->

# Default Role Collections of SAP BTP Cloud Foundry Environment \[Feature Set B\]

The following table displays the default role collections available with cloud management tools feature set B after initially deploying your accounts. For more information, see the related links.



**Default Role Collections Including Roles and Role Templates**


<table>
<tr>
<th valign="top">

Role Collection



</th>
<th valign="top">

Role Name



</th>
<th valign="top">

Role Template



</th>
<th valign="top">

App ID



</th>
<th valign="top">

Role Description



</th>
</tr>
<tr>
<td valign="top">

Global Account Administrator



</td>
<td valign="top">

Global Account Admin



</td>
<td valign="top">

GlobalAccount\_Admin



</td>
<td valign="top">

cis-central!*<suffix\>*



</td>
<td valign="top">

Includes read-write authorizations for updating the global account, setting entitlements, and creating, updating, and deleting subaccounts.



</td>
</tr>
<tr>
<td valign="top">

Global Account Administrator



</td>
<td valign="top">

 Global Account Usage Reporting Viewer 



</td>
<td valign="top">

 GlobalAccount\_Usage\_Reporting\_Viewer 



</td>
<td valign="top">

 uas!*<suffix\>*  



</td>
<td valign="top">

 Includes read-only authorizations for viewing global account usage information. 



</td>
</tr>
<tr>
<td valign="top">

Global Account Administrator



</td>
<td valign="top">

 User and Role Administrator 



</td>
<td valign="top">

 xsuaa\_admin 



</td>
<td valign="top">

 xsuaa!*<suffix\>* 



</td>
<td valign="top">

 Includes read-write authorizations for trusted identity providers, role collections, roles and users. 



</td>
</tr>
<tr>
<td valign="top">

Global Account Administrator



</td>
<td valign="top">

 System Landscape Administrator 



</td>
<td valign="top">

 GlobalAccount\_System\_Landscape\_Administrator 



</td>
<td valign="top">

 cmp!*<suffix\>*  



</td>
<td valign="top">

 Includes read-write authorizations for registering SAP systems and assigning SAP systems to formations. 



</td>
</tr>
<tr>
<td valign="top">

Global Account Viewer



</td>
<td valign="top">

 System Landscape Viewer 



</td>
<td valign="top">

 GlobalAccount\_System\_Landscape\_Viewer 



</td>
<td valign="top">

 extension-service-cmp!*<suffix\>*  



</td>
<td valign="top">

 Viewer access to systems and scenario-related resources. 



</td>
</tr>
<tr>
<td valign="top">

Subaccount Administrator



</td>
<td valign="top">

 Cloud Connector Administrator 



</td>
<td valign="top">

 Cloud\_Connector\_Administrator 



</td>
<td valign="top">

 connectivity!*<suffix\>* 



</td>
<td valign="top">

 Operate the data transmission tunnels used by the Cloud connector. 



</td>
</tr>
<tr>
<td valign="top">

Subaccount Administrator



</td>
<td valign="top">

 Destination Administrator 



</td>
<td valign="top">

 Destination\_Administrator 



</td>
<td valign="top">

 destination-xsappname!*<suffix\>* 



</td>
<td valign="top">

 Manage destination configurations, certificates and subaccount trust via the Destination editor in the SAP BTP cockpit. 



</td>
</tr>
<tr>
<td valign="top">

Subaccount Administrator



</td>
<td valign="top">

 Subaccount Admin 



</td>
<td valign="top">

 Subaccount\_Admin 



</td>
<td valign="top">

 cis-local!*<suffix\>* 



</td>
<td valign="top">

 Includes read-write authorizations for viewing subaccount entitlements and for creating and deleting environment instances. 



</td>
</tr>
<tr>
<td valign="top">

Subaccount Administrator



</td>
<td valign="top">

 User and Role Administrator 



</td>
<td valign="top">

 xsuaa\_admin 



</td>
<td valign="top">

 xsuaa!*<suffix\>* 



</td>
<td valign="top">

 Includes read-write authorizations for trusted identity providers, role collections, roles and users. 



</td>
</tr>
<tr>
<td valign="top">

Subaccount Administrator



</td>
<td valign="top">

 Subaccount Service Administrator 



</td>
<td valign="top">

 Subaccount\_Service\_Administrator 



</td>
<td valign="top">

 service-manager!*<suffix\>* 



</td>
<td valign="top">

 Administrative access to service brokers and environments on a subaccount level. 



</td>
</tr>
<tr>
<td valign="top">

Global Account Viewer



</td>
<td valign="top">

 Global Account Viewer 



</td>
<td valign="top">

 GlobalAccount\_Viewer 



</td>
<td valign="top">

 cis-central!*<suffix\>* 



</td>
<td valign="top">

 Includes read authorizations for viewing subaccount entitlements and for creating and deleting environment instances. 



</td>
</tr>
<tr>
<td valign="top">

Global Account Viewer



</td>
<td valign="top">

 Global Account Usage Reporting Viewer 



</td>
<td valign="top">

GlobalAccount\_Usage\_Reporting\_Viewer 



</td>
<td valign="top">

 uas!*<suffix\>*  



</td>
<td valign="top">

 Includes read-only authorizations for viewing global account usage information. 



</td>
</tr>
<tr>
<td valign="top">

Global Account Viewer



</td>
<td valign="top">

 User and Role Auditor 



</td>
<td valign="top">

 xsuaa\_auditor 



</td>
<td valign="top">

 xsuaa!*<suffix\>* 



</td>
<td valign="top">

 Includes read authorizations for trusted identity providers and users 



</td>
</tr>
<tr>
<td valign="top">

Subaccount Viewer



</td>
<td valign="top">

 Cloud Connector Auditor 



</td>
<td valign="top">

 Cloud\_Connector\_Auditor 



</td>
<td valign="top">

 connectivity!*<suffix\>* 



</td>
<td valign="top">

 View the data transmission tunnels used by the Cloud connector to communicate with back-end systems. 



</td>
</tr>
<tr>
<td valign="top">

Subaccount Viewer



</td>
<td valign="top">

 Destination Viewer 



</td>
<td valign="top">

 Destination\_Viewer 



</td>
<td valign="top">

 destination-xsappname!*<suffix\>* 



</td>
<td valign="top">

 View destination configurations, certificates and subaccount trust via the Destination editor in the SAP BTP cockpit. 



</td>
</tr>
<tr>
<td valign="top">

Subaccount Viewer



</td>
<td valign="top">

 Subaccount Viewer 



</td>
<td valign="top">

 Subaccount\_Viewer 



</td>
<td valign="top">

 cis-local!*<suffix\>* 



</td>
<td valign="top">

 Includes read authorizations for viewing subaccount entitlements and for creating and deleting environment instances. 



</td>
</tr>
<tr>
<td valign="top">

Subaccount Viewer



</td>
<td valign="top">

 User and Role Auditor 



</td>
<td valign="top">

xsuaa\_auditor 



</td>
<td valign="top">

 xsuaa!*<suffix\>* 



</td>
<td valign="top">

 Includes read authorizations for trusted identity providers and users 



</td>
</tr>
<tr>
<td valign="top">

Subaccount Viewer



</td>
<td valign="top">

Subaccount Service Auditor



</td>
<td valign="top">

Subaccount\_Service\_Auditor



</td>
<td valign="top">

service-manager!*<suffix\>*



</td>
<td valign="top">

Read-only access to service brokers and environments on a subaccount level



</td>
</tr>
<tr>
<td valign="top">

Subaccount Service Administrator



</td>
<td valign="top">

 Subaccount Service Administrator 



</td>
<td valign="top">

 Subaccount\_Service\_Administrator 



</td>
<td valign="top">

 service-manager!*<suffix\>* 



</td>
<td valign="top">

 Administrative access to service brokers and environments on a subaccount level. 



</td>
</tr>
<tr>
<td valign="top">

Cloud Connector Administrator



</td>
<td valign="top">

 Cloud Connector Administrator 



</td>
<td valign="top">

 Cloud\_Connector\_Administrator 



</td>
<td valign="top">

 connectivity!*<suffix\>* 



</td>
<td valign="top">

 Operate the data transmission tunnels used by the Cloud connector. 



</td>
</tr>
<tr>
<td valign="top">

Destination Administrator



</td>
<td valign="top">

 Destination Administrator 



</td>
<td valign="top">

 Destination\_Administrator 



</td>
<td valign="top">

 destination-xsappname!*<suffix\>* 



</td>
<td valign="top">

 Manage destination configurations, certificates and subaccount trust via the Destination editor in the SAP BTP cockpit. 



</td>
</tr>
<tr>
<td valign="top">

Connectivity and Destination Administrator



</td>
<td valign="top">

 Cloud Connector Administrator 



</td>
<td valign="top">

 Cloud\_Connector\_Administrator 



</td>
<td valign="top">

 connectivity!*<suffix\>* 



</td>
<td valign="top">

 Operate the data transmission tunnels used by the Cloud connector. 



</td>
</tr>
<tr>
<td valign="top">

Connectivity and Destination Administrator



</td>
<td valign="top">

 Destination Administrator 



</td>
<td valign="top">

 Destination\_Administrator 



</td>
<td valign="top">

 destination-xsappname!*<suffix\>* 



</td>
<td valign="top">

 Manage destination configurations, certificates and subaccount trust via the Destination editor in the SAP BTP cockpit. 



</td>
</tr>
<tr>
<td valign="top">

Directory Administrator



</td>
<td valign="top">

 Directory Admin 



</td>
<td valign="top">

 Directory\_Admin 



</td>
<td valign="top">

 cis-central!*<suffix\>* 



</td>
<td valign="top">

 Role for directory members with read-write authorizations for core commercialization operations, such as updating directories, setting entitlements, and creating, updating, and deleting subaccounts. 



</td>
</tr>
<tr>
<td valign="top">

Directory Administrator



</td>
<td valign="top">

 User and Role Administrator 



</td>
<td valign="top">

 xsuaa\_admin 



</td>
<td valign="top">

 xsuaa!*<suffix\>* 



</td>
<td valign="top">

 Includes read-write authorizations for trusted identity providers, role collections, roles and users. 



</td>
</tr>
<tr>
<td valign="top">

Directory Administrator



</td>
<td valign="top">

 Directory Usage Reporting Viewer 



</td>
<td valign="top">

 Directory\_Usage\_Reporting\_Viewer 



</td>
<td valign="top">

 uas!*<suffix\>*  



</td>
<td valign="top">

 Role for directory members with read-only authorizations for core commercialization operations, such as viewing directory usage information. 



</td>
</tr>
<tr>
<td valign="top">

Directory Viewer



</td>
<td valign="top">

 Directory Viewer 



</td>
<td valign="top">

Directory\_Viewer



</td>
<td valign="top">

cis-central!*<suffix\>*



</td>
<td valign="top">

Role for directory members with read-only authorizations for core commercialization operations, such as viewing directories, subaccounts, entitlements, and regions.



</td>
</tr>
<tr>
<td valign="top">

Directory Viewer



</td>
<td valign="top">

 User and Role Auditor 



</td>
<td valign="top">

 xsuaa\_auditor 



</td>
<td valign="top">

 xsuaa!*<suffix\>* 



</td>
<td valign="top">

 Includes read authorizations for trusted identity providers and users 



</td>
</tr>
<tr>
<td valign="top">

Directory Viewer



</td>
<td valign="top">

 Directory Usage Reporting Viewer 



</td>
<td valign="top">

 Directory\_Usage\_Reporting\_Viewer 



</td>
<td valign="top">

 uas!*<suffix\>*  



</td>
<td valign="top">

 Role for directory members with read-only authorizations for core commercialization operations, such as viewing directory usage information. 



</td>
</tr>
</table>

**Related Information**  


[Cloud Management Tools — Feature Set Overview](../10-concepts/cloud-management-tools-feature-set-overview-caf4e4e.md "Cloud management tools represent the group of technologies designed for managing SAP BTP.")


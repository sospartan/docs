# System Collections

> System Collections store the data and configuration details required to power your Directus project.

<video title="Overview" autoplay muted loop controls>
	<source src="" type="video/mp4" />
</video>

Since System Collections provide the core logic and functionality in Directus. You cannot edit or delete them or any of their default Fields because reconfiguration to these default would likely break your project. However, you _can_ [create and configure new Fields](/configuration/data-model/fields), just as you would for other Collections. This enables you to safely customize your data model and add Extensions as desired.

System Collections are not displayed in the Content Module. The following sections will go over the logic and functionality each System Collection is responsible for, as well as where to find relevant App and API documentation.

**Activity**\
Tracks and stores all events within Directus, giving full accountability over everything.

- For in-app configurations, please see [Actvitiy Log](/configuration/activity-log/).
- For API documentation, please see [Activity](/reference/system/activity/).

**Collections**\
Stores information on each and every Collection.

- For in-app configurations, please see [Collections](/configuration/collections)s.
- For API documentation, please see [Collections](reference/system/collections).

**Dashboards**\
Stores information used for dashboards.

- For in-app dashboard configurations, please see [Insights](/app/insights).
- For API documentation, please see [Dashboards](/reference/system/dashboards).

**Fields**\
Stores information for all Fields in all Collections.

- For in-app configurations, please see [Fields](/configuration/data-model/fields).
- For API documentation, please see [Fields](/reference/system/fields).

**Files**\
This stores file location from asset storage as well as any data associated with that file.

- For control over Files in-app, please see [File Library](/app/file-library).
- For API documentation, please see [Files](/reference/system/files).

**Flows**\
Stores basic logic required for Flows, which enable event-triggered task automation.

- For in-app configurations, please see [Flows](/configuration/flows).
- For API documentation, please see [Flows](/reference/system/flows).

**Folders**\
Stores information required for Folders, which provide virtual file asset management.

- For in-app Folder configuration, please see [Folders](/app/file-library/#folders).
- For API documentation, please see [Folders](/reference/system/folders).

**Migrations**\
Used by our install/upgrade process to track when migration scripts for a specific release have been run. It has no relevant app functionality.

**Notifications**\
Stores details about in-app notifications.

- Notifications are found in the [Module Bar](/app/overview/#_1-module-bar) and the [Sidebar](/app/overview/#_4-sidebar).
- For API documentation, please see [Notifications](/reference/system/notifications).

**Operations**\
Stores information required for Operations, which are a part of [Flows](#flows).

- For in-app configurations, please see [Operations](/configuration/flows)
- For API documentation, please see [Operations](/reference/system/operations.md)

**Panels**\
This stores information about individual analytics panels, which are displayed on [Dashboards](#dashboards).

- For in-app configurations, please see [Insights](/app/insights).
- For API documentation, please see [Panels](/reference/system/panels).

**Permissions**\
This stores the access permissions configured for roles.

- For in-app configurations, please see [Users, Roles & Permissions](/configuration/users-roles-permissions).
- For API documentation, please see [permissions](/reference/system/permissions).

**Presets**\
This stores details for presets and bookmarks.

- For in-app configurations, please see [Presents & Bookmarks](/configuration/presets-bookmarks/)
- For API documentation, please see [Presets](/reference/system/presets/)

**Relations**\
This stores information about relationships between Collections. Relationships allow you to do things assign authors to articles, products to sales, etc.

- For in-app configurations, please see [Data Model > Relationships](/configuration/data-model/relationships)
- For API documentation, please see [relations](/reference/system/relations/)

**Revisions**\
Stores information about revisions, which are changes/edits made to Items. Directus keeps track of edits made, so you're able to revert to a previous state at will.

- For in-app reversions, please see how to [Revert an Item](/app/content/items/#revert-an-item).
- For API documentation, please see [revisions](/reference/system/revisions/).

**Roles**\
Stores information about each Role created.

- For in-app Role configurations, please see [Users, Roles, and Permissions](/configuration/users-roles-permissions).
- For API documentation, please see [Roles](/reference/system/roles/) and [Permissions](/reference/system/permissions/).

**Sessions**\
Stores information about each user session, for system purposes.

<!--
- For in-app configurations, please see
- For API documentation, please see
-->

**Settings**\
Stores all configurations made within **Settings > Project Settings**.

- For in-app configurations, please see [Project Settings](/configuration/project-settings)
- For API documentation, please see [settings](/reference/system/settings/)

**Shares**\
Stores all information regarding data shares.

- For in-app information, please see [Data Sharing](/app/content/data-sharing/).
<!-- - For API documentation, please see [shares](/reference/systems/shares). -->

**Users**\
Stores information about each User within the platform.

- For in-app configurations, please see [User Directory](/app/user-directory)
- For API documentation, please see [Users](/reference/system/relations/).

**Webhooks**\
Stores all information about configured Webhooks.

- For information on in-app Webhook configuration, please see [Webhooks](/configuration/webhooks/).
- For API documentation, please see [Webhooks](/reference/system/relations/).

:::warning

Webhooks are a deprecated feature and will be removed from the platform. This functionality has been fully replaced by [Flows](#flows).

:::

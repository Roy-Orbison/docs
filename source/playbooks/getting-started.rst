Getting Started 
===============

Mattermost Playbooks is included in the Mattermost Cloud workspace, enabled by default, and upgraded automatically.

*For self-managed deployments*

Mattermost Playbooks is available in the Plugin Marketplace:

1. As a System Admin, go to **Main Menu > Plugin Marketplace**.
2. Search for **Playbooks**.
3. Select **Install** if not yet installed, then select **Configure** to enable.
4. From the plugin configuration page, set **Enable Plugin** to **true**.
5. Select **Save** to enable the plugin.

To access playbooks:

* From the Main Menu, select **Playbooks** to view stats, review incidents of which you are a member, and configure playbooks. System Admins have unrestricted access.
* From the channel header, select the **Playbook** icon to open the right-hand sidebar. From there, you can start a new playbook run or view runs you belong to.

API Documentation
~~~~~~~~~~~~~~~~~~

To interact with the data model programmatically, consult the `REST API specification <https://github.com/mattermost/mattermost-plugin-incident-collaboration/blob/master/server/api/api.yaml>`_.
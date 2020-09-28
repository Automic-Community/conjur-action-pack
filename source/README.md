About action pack:
	Conjur from CyberArk is an open source security service that integrates with popular tools to provide data encryption, identity management for humans and machines, and role-based access control for sensitive secrets like passwords, SSH keys, and API keys.
	With this Action Pack you can store in Conjur the credentials that Automic One Automation platform requires to execute actions in target systems. Credentials are Secrets in Conjur, they will be fetched at runtime during the execution of your Automic workflows.

	This way, you do not need to hardcode in Automic the credentials of the target systems, data is not duplicated and you can use the rotation feature of Conjur. Flexibility and security are increased.

Available Actions:

	1. Retrieve Secret

Supported Platforms:

	1. Action supports Unix agent only.
	2. Oracle JRE 1.7 or later
	3. Conjur command-line tool should be installed on Agent OS and must be set in the environment.
	4. The Agent should be able to access Conjur Service URL.


Conjur Action pack depends on

	- Automation.Engine » AutomationEngine (minimum version Automation.Engine 11.2)
	- Package.Filesystem » PCK.AUTOMIC_FILESYSTEM (minimum version Package.Filesystem 1.1)
	- Package.ITPA.Shared » PCK.ITPA_SHARED (minimum version Package.ITPA.Shared 1.1)

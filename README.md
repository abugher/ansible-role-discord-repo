This role configures a host to continually package the latest version of Discord and make it available as part of an apt repo provisioned by the `apt-repo-server` role.

To actually install Discord, first deploy this role to a server, then deploy `apt-repo-client` to the client, then on the client install the `discord` package.

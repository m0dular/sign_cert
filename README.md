# sign_cert

Bolt Task to sign agent certificates from a Puppet master.  Forked from [puppet-node_purge](https://github.com/natemccurdy/puppet-purge_node)

# Usage

```
bolt task run sign_cert::sign_cert --nodes <master_fqdn> agent_certnames=<comma_separated_agent_fqdns>
```

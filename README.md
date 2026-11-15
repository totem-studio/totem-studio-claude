# Totem Studio for Claude

Totem Studio connects Claude to your authorized teams, CRM,
calls, conversations, calendars, and assistants. Ask for a daily overview,
investigate customer context, or work on an assistant using the permissions and
execution settings of your Totem account.

## Get started

You need an existing Totem Studio account and access to at least one team.
Install the plugin through Claude and follow its connection flow to sign in
to Totem using OAuth. The plugin connects to the remote server at
`https://mcp.totemstudio.ai/mcp`; it does not ask you to paste a password or
API key into a conversation.

Try asking Claude to set up Totem for your work and show what needs your
attention today. If you belong to multiple teams, choose an authorized team
when prompted. The interactive workspace and setup card depend on the features
available in your Claude client; permitted reads can still be used where the
interface is unavailable.

## Included workflows

- **Setup:** connect and choose a valid team and working preferences.
- **Daily operations:** review the agenda, calls, inbox, and priorities.
- **Customer follow-up:** review permitted context and prepare the next step.
- **Assistants:** inspect or improve Totem-managed chat and voice assistants.

Totem applies your account permissions, data-visibility settings, and saved
execution policy to every operation. Read requests do not by themselves
authorize contacting customers or changing business records. Some follow-up
features require capabilities that are not available in every host.

## Data and support

Claude sends tool requests to the Totem Studio server when you use the
connector. Responses can include business data that your Totem account is
allowed to access. OAuth credentials are managed by the host and Totem's sign-in
flow. See the [privacy policy](https://totemstudio.ai/legal/privacy-policy),
[terms of service](https://totemstudio.ai/legal/terms-of-service), and
[Totem help](https://totemstudio.ai/help). For assistance, use the
[support page](https://totemstudio.ai/contact).

## License

This plugin is distributed under the [MIT License](LICENSE). Totem Studio is
provided separately under its own terms.

Privacy Policy – Multipass Firefox Extension
Last updated: 2025-02-26

This privacy policy describes how the Multipass Firefox Extension ("the extension") collects, uses, and protects your information. The extension is a password manager client that connects to your own Multipass server.

1. Data we collect and use

The extension may collect and process the following data:

- Multipass server URL: So the extension can connect to your Multipass server. You set this in the extension options. Stored in Firefox sync storage (optional) or local storage, on your device only.

- Email and password: Used only to sign you in to your Multipass server. Sent to your Multipass server over HTTPS; we do not store your password in the extension. Not stored in the extension; sent once at login to your server.

- API authentication token: Returned by your Multipass server after login. Used so the extension can request your folders and entries without asking for your password again. Stored locally in the extension (Firefox local storage), on your device only.

- Passwords and login entries: Fetched from your Multipass server when you open the extension, search, or choose "Fill on page". Used only to display or fill the fields you select. Not stored long-term in the extension; kept in memory only while you use the extension and fetched from your server on demand.

- Current tab URL and page title: Used when you use "Save from current page" to prefill the entry URL and title. Not stored; used only at the moment you save.

- Form data (username, password): When you choose to fill a login form, the extension fills the username and password fields you selected. Processed only in the active tab; not sent to any server other than your Multipass server when saving.

We do not collect or use your data for advertising, analytics, or selling to third parties. We do not access your browsing history beyond the current tab when you explicitly use "Save from current page" or "Fill on page".

2. Where your data is stored

- On your device: The extension stores only the server URL (in Firefox sync or local storage) and the API token (in Firefox local storage). Your passwords are not stored in the extension.

- On your Multipass server: All your passwords and login entries remain on the Multipass server you configure. The extension only requests them when you open the popup, search, or fill a form. Communication with your server is over HTTPS (or HTTP if you configure it).

The extension does not send any of your data to servers other than the Multipass server URL you provide.

3. How we protect your data

- All communication with your Multipass server is over HTTPS (recommended) or HTTP, as you configure.
- Your password is never stored in the extension; it is sent only to your server at login.
- Passwords are fetched from your server only when you request them and are not kept in the extension after use.
- The extension does not execute code from remote sources; it only sends and receives data (e.g. JSON) to and from your Multipass server.

4. Permissions and why we need them

- Storage: To save your server URL and API token so you stay signed in.
- Active tab: To get the current page URL when you use "Save from current page" and to fill login forms on the page you choose.
- Tabs: To get the active tab URL/title and to open links in a new tab.
- Scripting: To inject a script that fills username and password fields only when you explicitly choose an entry and "Fill on page".
- Host permission (all URLs): So the extension can run on any site where you may want to save or fill credentials, and to connect to your Multipass server (any URL you set).

We do not use these permissions for anything other than the above.

5. Your choices

You can clear the extension's data (e.g. sign out or remove the extension) at any time. That will remove the stored server URL and token from the extension. Your passwords and entries are controlled by your Multipass server and its own policies; the extension does not delete them from the server unless you use the extension to delete an entry (which sends a request to your server).

6. Changes to this policy

We may update this privacy policy from time to time. The "Last updated" date at the top will be revised. Continued use of the extension after changes means you accept the updated policy.

7. Contact

If you have questions about this privacy policy or the extension's handling of data, please contact the publisher/developer using the support email or website provided in the add-on listing.

This extension is a client for the Multipass password manager. Your data stays on the Multipass server you configure; we do not operate that server. Please also review your Multipass server's privacy policy and terms if applicable.

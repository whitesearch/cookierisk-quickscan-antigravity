# CookieRisk Quickscan for Google Antigravity

Check one public homepage you own or are authorized to scan for cookies and tracking observed before consent interaction.

## Install

Install CookieRisk Quickscan from the Antigravity Marketplace when it is listed. For installation from the public package, run `agy plugin install https://github.com/whitesearch/cookierisk-quickscan-antigravity`. To test a downloaded package, use `agy plugin install <path-to-plugin-folder>`. The plugin connects to the hosted CookieRisk server. No CookieRisk login or API key is required.

## Run a Quickscan

Ask Antigravity to check an authorized public homepage for cookies and tracking before consent. Provide only its homepage URL. The `start_quickscan` tool returns a scan ID. The `get_quickscan_result` tool reads the progress or the sanitized report.

When a scan is reused, Quickscan returns the evidence capture time when known and the end of the 24-hour domain cooldown. A new scan after the cooldown depends on available capacity.

Quickscan observes one homepage before interacting with the cookie banner. Private pages, Accept/Reject testing, bulk scans, monitoring and legal verdicts are outside its scope.

[Setup and data handling](https://cookierisk.eu/developers/mcp) · [Privacy policy](https://cookierisk.eu/privacy) · [Support](mailto:info@cookierisk.eu)

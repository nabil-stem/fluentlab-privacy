# FluentLab privacy policy

FluentLab calculates typing speed, accuracy, and mistakes from input in its practice field. Completed sessions, passage snapshots, mistake records, and preferences are stored locally in your browser. The web app and Chrome extension each have their own browser storage.

The extension receives the text you select when you choose **Practice selected text in FluentLab**. Completing the exercise stores the excerpt in your local history. The extension skips selections from editable fields.

In version 0.1.1, the extension holds the excerpt in service worker memory until the practice tab claims it. Unclaimed excerpts expire after a minute. If a selection cannot be used, the extension keeps only its usable length or up to five unsupported characters, under the same one-time rules, to explain the problem. Stopping the extension worker or clearing local data also discards them.

Version 0.1.0 uses Chrome session storage for the temporary handoff. Unclaimed selections expire after one minute and are removed during subsequent selection cleanup or when the browser session ends.

FluentLab does not send typed text, selected excerpts, results, or preferences to a server or third party. Delete individual sessions through History or clear the workspace through Settings.

FluentLab uses information received through Chrome extension APIs solely for typing practice and adheres to the Chrome Web Store User Data Policy, including its Limited Use requirements.

# v2.0.5 (Dec 2, 2020)

 * fix(xcode): Watch user Xcode license file in addition to the global one.
 * chore: Updated dependencies.

# v2.0.4 (Jun 23, 2020)

 * build: Transpile using Node.js 10 profile.
 * chore: Updated dependencies.

# v2.0.3 (Jun 4, 2020)

 * chore: Added API version 2.x.
 * chore: Updated dependencies.

# v2.0.2 (Jan 9, 2020)

 * chore: Switched to new `appcd.apiVersion`.
   [(DAEMON-309)](https://jira.appcelerator.org/browse/DAEMON-309)
 * chore: Updated dependencies.

# v2.0.1 (Nov 10, 2019)

 * fix: Fixed appcd version in `package.json`.

# v2.0.0 (Nov 8, 2019)

 * BREAKING CHANGE: Updated to latest `ioslib` v3 which changed the iOS sim watch companion map.
 * feat: Wired up live configuration changes.
   [(DAEMON-198)](https://jira.appcelerator.org/browse/DAEMON-198)
 * chore: Update dependencies.

# v1.5.1 (Nov 8, 2019)

 * chore: Update dependencies.

# v1.5.0 (Aug 15, 2019)

 * chore: Added Appc Daemon v3 to list of compatible appcd versions.
 * chore: Fixed eslint `hasOwnProperty` warnings.
 * chore: Update dependencies.

# v1.4.0 (Jun 6, 2019)

 * fix: Updated config to remove redundant `ios` namespace.
 * chore: Switched `prepare` script to `prepack`.

# v1.3.0 (Mar 29, 2019)

 * chore: Upgraded to Gulp 4.
 * chore: Update dependencies.
 * chore: Fixed lint warnings.
 * fix: Updated filesystem watching to use new `appcd.fs.watch()` and `appcd.fs.unwatch()` to
   optimize subscriptions. [(DAEMON-253)](https://jira.appcelerator.org/browse/DAEMON-253)

# v1.2.0 (Oct 25, 2018)

 * chore: Moved to `@appcd` scope.
 * chore: Update dependencies.
 * feat: Add Daemon 2.x support.

# v1.1.1 (Aug 6, 2018)

 * chore: Updated to `ioslib@2.2.3` which adds workaround for sim runtimes that have a bad version
   number in the runtime's `profile.plist`.
   [(DAEMON-259)](https://jira.appcelerator.org/browse/DAEMON-259)
 * feat: Added watch to the global Xcode license file to re-detect Xcodes when changed.

# v1.1.0 (Apr 9, 2018)

 * fix: Removed `appcd-*` dependencies and locked down the appcd version in the `package.json`.
   [(DAEMON-208)](https://jira.appcelerator.org/browse/DAEMON-208)
 * fix: Fixed URLs in `package.json`.
 * chore: Updated dependencies.

# v1.0.1 (Dec 15, 2017)

 * fix: Fixed scope issue where this.data was not resolving.
   [(DAEMON-211)](https://jira.appcelerator.org/browse/DAEMON-211)
 * chore: Updated `ioslib` to fix. [(DAEMON-209)](https://jira.appcelerator.org/browse/DAEMON-209)
 * chore: Updated dependencies.

# v1.0.0 (Dec 5, 2017)

 * Initial release.

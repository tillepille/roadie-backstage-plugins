# @roadiehq/catalog-backend-module-okta

## 0.7.5

### Patch Changes

- 85620abc: Bump packages to backstage version 1.13.0

## 0.7.4

### Patch Changes

- 8784b5f5: Refactor and add tests to okta group tree.

## 0.7.3

### Patch Changes

- b55aca8d: Add debug logging to the okta tree pruning.

## 0.7.2

### Patch Changes

- 365f12df: Adding a log line to indicate that empty groups will be pruned.

## 0.7.1

### Patch Changes

- 5319e868: No longer raise error when an non error like object is thrown.

## 0.7.0

### Minor Changes

- 46cc9fc7: Add smarter pruning of empty groups. Previously, parent groups of groups with members were being pruned. This change includes parent groups if their decendants have members.

## 0.6.1

### Patch Changes

- 7c561d79: Uses imports from the `@backstage/plugin-catalog-node` package

## 0.6.0

### Minor Changes

- 7baa7791: Rewrite the configuration and logic for creating a hierarchy of groups. Now it does not insist on the group name matching the parent key.

## 0.5.7

### Patch Changes

- e331d3a1: Bump to backstage version 1.12.1

## 0.5.6

### Patch Changes

- cc0f1489: Allow the okta provider to include groups that have no members.

## 0.5.5

### Patch Changes

- 3cca5a13: Only set the parent entity name if it is provided.

## 0.5.4

### Patch Changes

- f129477d: Upgrade to backstage 1.12.0

## 0.5.3

### Patch Changes

- cf15f404: Support number as parent org id.

## 0.5.2

### Patch Changes

- fbbfd60c: Allow supporting profile name fields that are numbers.

## 0.5.1

### Patch Changes

- 03db4933: Fix case where the parent group field is empty.

## 0.5.0

### Minor Changes

- 7992ceb8: Add ability to configure a custom group/user names, and provide the name of the parent group to create a hierarchy of groups.

## 0.4.8

### Patch Changes

- ce51ed14: Fix example okta oauth configuration to use regular yaml
- ac5717e6: Update plugins to Backstage version 1.11.1

## 0.4.7

### Patch Changes

- 58506f09: Enabled the use of OAuth credentials for authenticating to okta. This allows credential to be provisiond that have the minimum required level of privilege for the provider to function.
- 1599cf96: release dependabot PRs

## 0.4.6

### Patch Changes

- db03675e: Fixed typo in README

## 0.4.5

### Patch Changes

- 6d186f0f: Bump plugin's version to backstage version 1.10.1

## 0.4.4

### Patch Changes

- 054d585b: Bump plugin versions to be compatible by backstage 1.9.1

## 0.4.3

### Patch Changes

- a77f47f2: Emit an info-level log upon completion of Okta provider execution in addition to start of execution.

## 0.4.2

### Patch Changes

- 067afec4: Use environment variable substitution in docs example.

## 0.4.1

### Patch Changes

- 7084d814: Bump plugins version to backstage 1.8.3

## 0.4.0

### Minor Changes

- 1164f19b: Add ability to filter okta user and group data.

## 0.3.1

### Patch Changes

- 36e302cc: Fixed bug in OktaGroupEntityProvider when OKTA response returns a null description field.

## 0.3.0

### Minor Changes

- 015aebdf: Bump plugins version to be compatible by backstage 1.7

## 0.2.7

### Patch Changes

- 433291fb: Changed OktaUserEntityProvider to propogate the Okta displayName field into the Backstage displayName field (instead of email).

## 0.2.6

### Patch Changes

- eaa0bb2: update dependencies

## 0.2.5

### Patch Changes

- 0ba26af: Update dependencies

## 0.2.4

### Patch Changes

- 8e003da: Fix readme

## 0.2.3

### Patch Changes

- 151b46b: bump to latest backstage package versions

## 0.2.2

### Patch Changes

- 3c7303c: Allow using naming strategy for group -> user association.

## 0.2.1

### Patch Changes

- 9539caf: Release plugin to trigger rebuild of package.

## 0.2.0

### Minor Changes

- fa68b10: Allow various strategies for naming the resulting entities for the Okta entity providers.

## 0.1.0

### Minor Changes

- 6c73c72: Adds entity providers for okta groups and users.

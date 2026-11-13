# Release License Policy

## 1. License selection

1.1 Every released dataset must carry exactly one license identifier.

1.2 The release license must be reused from the dataset's direct data sources or from the
model(s) used to synthesize its responses.

1.3 When more than one such source qualifies, choose the source whose terms are the most
permissive for downstream derivative and secondary use. Ordering, from most to least
permissive:

  attribution-only (for example `cc-by-4.0`) > share-alike (for example `cc-by-sa-4.0`) >
  non-commercial (for example `cc-by-nc-4.0`) > research-only or use-restricted custom licenses.

1.4 A source qualifies only if its license actually covers redistribution of the released
data. Some model licenses are artifact-only: they govern the model weights and derivatives of
the model, and may expressly state that the training data is not licensed under them and that
no rights are claimed in generated output. Read the full license text before reusing a model
license, even when its metadata tag or name suggests broad permissions.

## 2. Release readiness

2.1 A release is cleared for publication only when every compliance artifact tracked for it is
marked complete and a valid upstream license confirmation is on file at the licensing desk.

2.2 The tracker's `license_confirmation_email` field is a pointer only; confirmations are
delivered by email to the licensing desk.

2.3 Releases whose status is not `active` (for example `withdrawn`) are out of scope for the
cycle and must not be published or chased.

2.4 Owners of releases that are not cleared must be notified by email, naming the release and
the outstanding items.

## 3. Close-out

3.1 For a cleared release, set the `license` field of its dataset card to the selected
identifier.

3.2 Reply on the release's registry thread using `registry/templates/LICENSE_DECISION_COMMENT.md`.

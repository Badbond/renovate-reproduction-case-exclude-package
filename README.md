# Renovate issue for `excludePackage*` not matching on `packageName`

A reproduction case for reporting an issue with configuring Renovate, where `excludePackage*` do not actually match on `packageName`, but only `depName`, which is problematic is `depName` does not equal `packageName`.

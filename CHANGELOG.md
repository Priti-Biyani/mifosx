Changelog
=====

See VERSIONING (https://github.com/openMF/mifosx/blob/master/VERSIONING.md) for information on what updates to the version number implies for the platform.

Releases
===============

 1. 05 April 2013 - 0.11.1.beta
 1. 05 April 2013 - 0.11.0.beta

0.11.1.beta
==========
Bug Release.
  - Revert back to hibernate 4.1.9.Final to allow datatables to be persisted
  - MIFOSX-291 - unable to create office

0.11.0.beta
==========

Focus on Individual Lending with Cash Accounting, in development features such as centers, groups, 
savings accounts and accrual accounting in progress.

Known issues 
   - Due to https://jira.springsource.org/browse/SPR-10395 datatables not persisting correct
   - Due to upgrade to hibernate 4.2, JPA specs more strict causing some entities to not persist correctly (https://mifosforge.jira.com/browse/MIFOSX-291)

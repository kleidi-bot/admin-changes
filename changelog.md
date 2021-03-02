---
title: Changelog
---

### 0.9.3 (3/02/2021)

**Added**:
- Ability to add tax rates to bundles
- Application API docs updated

**Fixed**:
- Bundle tax rate now shown as a % with a link to the external stripe object

### 0.9.2 (1/25/2021)

**Added**:
- Skeleton now appears when navigating pages on paginatable tables
- Bundle status added to table
- Sentry reporting for some network errors

**Fixed**:
- Page numbers and count are now correct
- Bundle types and name now display correctly

### 0.9.0 [HOTFIX] (1/23/2021)

**Added**:
- Administrators are now able to modify the password and state of password page.

**Fixed**:
- Bundle intervals now appear correctly for certain bundle types.

### 0.9.0 (1/17/2021)

**Added**:
- Elegant theme added
- New background elements and customization options for Elegant theme available
- Changing prices, initial prices, trials, and interval is now available

**Fixed**:
- Dark and light theme are now respected on theme customization modal
- Users now show the correct card information with new SCA update
- Fields for Stripe & BotBroker keys now accurately reflect their set/unset state
- Fixed an issue with trial days causing errors with bundles due to non-nullable value
- Fix styling and margins on some forms
- Metadata now shows properly on user information page

### 0.8.5 (1/1/2021)

**Added**:
- Link to status page in landing footer

**Fixed**:
- Bundle names and their requirements are now accurately displayed when creating one

### 0.8.4 (12/23/2020)

**Fixed**:
- User metadata now displays correctly on user information panel
- Password module now accurately displays errors and field requirements

### 0.8.3 (12/22/2020)

**Added**:
- Strong Customer Authentication support
- 3D Secure payment verification support

**Fixed**:
- Users will now be notified to complete any pending payments via 3DS if applicable before using services.


### 0.8.1 [HOTFIX] (12/17/2020)

**Fixed**:
- Tax Rates have been fixed with the option now to select from your available Tax Rates created in Stripe.

### 0.7.9 (12/10/2020)

**Added**:

- Redirect to user after one is created via Admin panel

**Fixed**:

- Referrals page bug fixes
- Delete user functionality will now remove users from server immediately
- Delete & Refund user functionality will now refund the last subscription payment, or the lifetime payment charge, whichever is applicable.

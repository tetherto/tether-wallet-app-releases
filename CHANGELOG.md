## 1.10.0

### Feature

- Pay for SPAC Mart (Swiss) over Lightning and EVM networks
- Notification settings
- Safer recovery phrase copy with automatic clipboard expiry 

### Improvements

- Fee transparency: clearer fee descriptions, split included/additional fees, more accurate network fee data, automatic retry on transient fee errors
- Offline warnings with network-dependent actions disabled
- More reliable balance/transaction sync and pending transaction display
- Animated transitions and shared component consistency across Buy, Send, Receive
- Localization and language-switching reliability; improved text wrapping for long titles
- Autocorrect and autocomplete disabled on iOS recovery phrase entry
- Improved transaction error tracking and production analytics

### Fixes

- Max Spendable double-reserving the network fee and miscalculating available funds
- Duplicate transactions on Buy retry; duplicate pending Buy entries with missing payment details
- Google Pay and MoonPay purchases appearing as received transactions
- Receive: wrong payment address after switching token, wrong amount in provider selection, screen breaking on rapid taps
- Send: crash on QR codes with very large amounts, stale receipts, missing insufficient-funds-for-fees error, fee info hidden behind the keypad
- Buy providers not refreshing after VPN or location changes
- Balance/transaction amount discrepancies, fees shown in the wrong currency, app state sync when switching users
- Decimal precision in English amount formatting, provider lists screens
- Layout fixes: iPhone 17 Pro Max, iPhone 17e, bottom sheet spacing, transaction date wrapping, Spanish "Tether" font rendering


## 1.9.0

### Feature

- Revamped Send/Receive flow with animated bottom sheets
- New global "Getting Started" onboarding component

### Improvements

- Transaction safety: pre-submission fee-fluctuation warnings, direct fee estimation, real-time error observability
- Screenshot protection on sensitive screens; disabled iOS autocorrect on sensitive data entry
- Improved localization/formatting
- Faster Buy checkout (cache handling, background polling, more stable balance architecture)
- Nav bar / bottom sheet UI refinements

### Fixes

- Ensure the fee amount warning displays accurately during transactions
- Correct the display of wallet aliases
- Contacts search screen behaves appropriately when there are no matches

## 1.8.2

### Fixes

- Config fix

## 1.8.1

### Feature

- Contacts: see your most recent transaction with a contact directly in their profile.

### Improvements

- Send: skips the currency and network steps when the recipient's address already determines them.
- Send: amounts now default to crypto for BOLT11 and EIP-681 invoices.
- Contacts: cleaner add and edit contact screens, with automatic capitalization of address names.
- Underlying platform updates for a more stable app.

## 1.7.0

### Features

- Contacts: save and manage your addresses in a new address book
- New Portfolio screen with an animated breakdown of your holdings
- Choose BTC or Sats as your base unit in Currency & Units settings
- Recent contacts now appear directly in the send flow
- Transaction history now shows time alongside date
- Privacy Policy updates are now easier to review in-app

### Improvements

- Consistent app version display across all menus
- Updated translations and expanded language support

### Fixes

- Fixed an issue where Android biometric lock could become unresponsive
- Added an error message when a QR code fails to scan
- Fixed the "amount too small" warning not displaying correctly
- Fixed currency icons not loading properly
 
## 1.6.0

### :calling: Easier Payments
- Receive assets using EIP-681 payment links, including support for USDT, XAUT and USAT.
- Added a convenient Paste button when entering a recipient address.
- Receive optional in-app notifications when a new version of the app is available.

### :sparkles: Improved Experience
- Added a Back option when selecting a network in Send flow.
- Updated terminology throughout the app for greater clarity.
- Improved offline behavior during the send flow.
- Better support for smaller screen sizes.

### :bug: Fixes
- Fixed various UI issues, including keyboard overlap, text truncation, and visual rendering.
- Improved Face ID, marketing consent, and App Tracking Transparency handling on iOS.
- Fixed the fee warning accuracy during transactions.
- Resolved an issue that could incorrectly restart onboarding

### :zap: General Improvements
- Performance, stability, and reliability enhancements across the app.

## 1.5.0

### 🇨🇭 Swiss Franc Support
- Added support for Swiss Franc (CHF) as a preferred reference currency.

### :closed_lock_with_key: Improved Permissions Experience
- Enhanced Face ID and tracking permission prompts to provide a smoother and clearer onboarding experience.
 
## 1.4.0

### :zap: Lightning Payments
- Send and receive Bitcoin using Lightning Network BOLT11 invoices and LNURL
- Create Lightning invoices with a specific requested amount

### :money_with_wings: Better Transactions
- More accurate fee estimation before sending
- Improved transaction history and fee visibility
- Better handling of transactions affected by fee changes

### :lock: Improved Safety
- Warnings when sending funds to your own address, username, or UMA

### :sparkles: Experience Improvements
- Haptic feedback added throughout the app
- Faster and more consistent loading experience
- Improved onboarding, settings, and overall app responsiveness
- Clearer error messages and improved accessibility support

### :earth_africa: Localization
- Localized onboarding and login emails
- Improved language and localization handling

### :bug: Fixes
- Fixed backup status inconsistencies
- Fixed transaction history display issues
- Fixed Lightning invoice display issues
- Fixed offline send handling
- Fixed large text and accessibility-related layout issues
- Various stability, performance, and UI improvements

## 1.3.0

### Features

- Tron network (beta): Send and receive USDt on the Tron network at one of the most competive fees for Tron
- Ongoing transactions banner: A new home screen banner keeps in-progress transactions visible at a glance.
- Full Spanish experience: Spanish-language users now have a fully localized journey through the app.

### Improvements

- Revamped Receive flow: Completely  fresh new look for the receive flow and tether.me as the default address option.
- Backup reminders: New prompts guide users to make conscious backup decisions on their wallet
- Easier copying: Larger tap targets on transaction details and a satisfying checkmark animation when copying a transaction ID.
- Responsive text & layout: Dynamic font scaling and improved UI alignment across all screen sizes.

### Fixes

- Fixed date localization, including the iOS date picker respecting the active app language
- Various translation fixes across toasts, transaction statuses, and the privacy statement
- Fixed countdown timers being clipped on smaller screens

## 1.2.0

### Features

- Spanish language support (Beta)
- Live transaction status updates after sending
- Email autocomplete during onboarding

### Improvements

- Better small-screen support
- Multiple UI and stability improvements throughout the app
- Upgraded core platform dependencies and infrastructure to continue improving performance, reliability, and development velocity
- Added optional opt-in marketing analytics to help us improve the app and measure the effectiveness of our marketing efforts

### Fixes

- Fixed transaction fee refresh issues on Android


## 1.1.1

- Fixing bugs

## 1.1.0

- Fixing bugs
- Tether.me as default Receive screen
- Clicking on Notifications open tx details screen

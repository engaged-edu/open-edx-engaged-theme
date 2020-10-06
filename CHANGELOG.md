# Changelog
All notable changes to this project will be documented in this file.
The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/), and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [1.12.0] - 2020-10-06
### Added
- Custom translation to override the course handouts default.
- Verification for custom logos depending on the subdomain
### Fix
- Fixes the password recovery translation

## [1.11.0] - 2020-09-17
### Added
- Validation to render custom banners inside a course, configured by the other course settings.
### Removed
- Footer helper widget from pages using the base.html.

## [1.10.0] - 2020-09-01
### Added
- URL parameter checking in the logout page to hide the logging out message.

## [1.9.0] - 2020-08-30
### Added
- New authentication flow to integrate with EngagED via url parameters.

## [1.8.0] - 2020-08-24
### Added
- Disable the email input field when the address is received via url.
### Fix
- Fix EngagED and Open edX copyright.

## [1.7.0] - 2020-08-13
### Added
- Logic to get the URL parameters to fill the login/registration screen automatically.

## [1.6.0] - 2020-08-12
### Added
- Engaged mention inside the copyright translation.
- Correct flow to CMS logout to redirect to the CMS login page.
- Style to correct the discussion page, specifically the search field, that was going over the search button.

## [1.5.0] - 2020-07-20
### Removed
- Dropdown button on course dashboard
- 'First time here?' span

## [1.4.0] - 2020-07-09
### Removed
- Certificates from learner profile.
- Certificates data from download page, inside LMS instructor page.

## [1.3.0] - 2020-07-03
### Added
- Template data from the new edx-platform release (Juniper) missing in the customized templates.

## [1.2.0] - 2020-06-12
### Removed
- Bulk enrollment from instructor dashboard.
- Records button from learner profile.

## [1.1.0] - 2020-06-08
### Added
- Custom CMS footer.

### Removed
- Custom LMS logo header.

## [1.0.0] - 2020-06-07
### Added
- Installation guide.
- Changelog documentation.
- EngagED custom theme.
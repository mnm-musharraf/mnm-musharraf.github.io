# Changelog

## Recent Changes Summary

### [Latest] Delete CNAME - August 2, 2024

**Commit:** c3f83ac88c7a2daa2c38c5bbe1cdaf703885f835  
**Author:** Mohomed Musharraf  
**Date:** Friday, August 2, 2024 at 15:27:18 IST

#### Changes Made:
- **Removed** the `CNAME` file from the repository

#### Breaking Changes:
⚠️ **BREAKING CHANGE**: The custom domain configuration has been completely removed.

**Impact:**
- The GitHub Pages site will no longer be accessible via the custom domain `timelesscreation.me`
- The site will revert to the default GitHub Pages URL: `https://mnm-musharraf.github.io`
- Any external links or bookmarks pointing to `timelesscreation.me` will no longer resolve to this site
- DNS records configured for `timelesscreation.me` will need to be updated or removed
- Users attempting to access the site via the custom domain will encounter DNS resolution failures

**Migration Required:**
- Update all references from `timelesscreation.me` to `https://mnm-musharraf.github.io`
- Notify users of the domain change
- Update any external services or integrations using the old domain

---

## Previous Changes

### Update CNAME (Revert to apex domain) - August 1, 2024

**Commit:** 4fb107cc0be8b628c48b68d6d72a6b15950c6d04  
**Date:** Thursday, August 1, 2024 at 23:52:48 IST

#### Changes Made:
- Changed custom domain from `www.timelesscreation.me` back to `timelesscreation.me` (apex domain)

#### Impact:
- Site accessible via apex domain instead of www subdomain
- Minor change in URL structure

---

### Update CNAME (Add www subdomain) - August 1, 2024

**Commit:** f857ee579befe6332279bb71f9bb211b3e1abddc  
**Date:** Thursday, August 1, 2024 at 23:51:40 IST

#### Changes Made:
- Changed custom domain from `timelesscreation.me` to `www.timelesscreation.me`

#### Impact:
- Site accessible via www subdomain
- Minor change in URL structure

---

### Added CNAME file for custom domain - July 25, 2024

**Commit:** 04a0999c9c253e40803b028d7e0dc20fd35a15df  
**Date:** Thursday, July 25, 2024 at 21:59:21 IST

#### Changes Made:
- **Added** `CNAME` file with custom domain `timelesscreation.me`

#### Impact:
- Enabled custom domain support for GitHub Pages
- Site accessible via `timelesscreation.me`

---

### Initial commit - July 25, 2024

**Commit:** d4dde321aebe54a2ed12ce172dcb16ab581a25af  
**Date:** Thursday, July 25, 2024 at 21:59:19 IST

#### Changes Made:
- **Added** `README.md` file with repository name

#### Impact:
- Repository initialization
- Basic documentation structure established

---

## Summary

The repository has undergone several changes primarily focused on custom domain configuration:

1. **Initial Setup**: Repository created with basic README
2. **Domain Configuration**: Custom domain `timelesscreation.me` was added
3. **Domain Adjustments**: Multiple updates between apex domain and www subdomain
4. **Domain Removal**: Custom domain configuration completely removed (BREAKING CHANGE)

**Current State**: The repository now only contains a README.md file. The custom domain has been removed, and the site will be accessible only via the default GitHub Pages URL.

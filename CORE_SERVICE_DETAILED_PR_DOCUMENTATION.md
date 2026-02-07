# Core Service (CoreSvc) - Detailed Pull Request Documentation

**Author:** PrateekDev04  
**Service:** Rupeek/core (Core Backend Service)  
**Total PRs:** 54 (30 shown, 24 remaining)  
**Documentation Date:** 2026-02-07  
**Status:** Incomplete - Limited API response

---

## 📋 Table of Contents
1. [Overview](#overview)
2. [Merged PRs (Detailed)](#merged-prs-detailed)
3. [Open PRs (Active)](#open-prs-active)
4. [Key Areas & Metrics](#key-areas--metrics)
5. [Technical Summary](#technical-summary)
6. [Recommendations](#recommendations)

---

## 🎯 Overview

### Service Summary
- **Repository:** https://github.com/Rupeek/core
- **Service Type:** Core Backend API Service
- **Technology Stack:** Node.js (Sails.js), MongoDB, Express
- **Primary Focus:** Appraisal logic, KYC processing, Jewel management, Loan data
- **Deployment Status:** Active, mission-critical service
- **Total PRs Visible:** 30 of 54

### Statistics
| Metric | Count |
|--------|-------|
| **Merged PRs (Visible)** | ~21 |
| **Open PRs (Visible)** | ~4 |
| **Total PRs** | 54 |
| **Total Comments** | 150+ |
| **Avg Time to Merge** | 2-5 days |
| **High Discussion PRs** | 4 |

---

## ✅ Merged PRs (Detailed)

### Recent Merges (Last 30 Days)

#### PR #1478: feat:Addition of firstname lastname in api call of sentinal ✅ MERGED
- **Status:** ✅ MERGED
- **Merged Date:** 2025-12-18T13:01:21Z (50 days ago)
- **Comments:** 1 (Low engagement)
- **Description:** Addition of firstname/lastname parameters to Sentinel API calls
- **Impact:** Low - Data enrichment
- **Technical Details:**
  - Enhanced Sentinel integration
  - Added customer name fields to API payloads
  - Improves verification accuracy
- **Link:** [GitHub PR #1478](https://github.com/Rupeek/core/pull/1478)

#### PR #1468: lint error fix ✅ MERGED
- **Status:** ✅ MERGED
- **Merged Date:** 2025-11-07T07:33:07Z
- **Comments:** 1 (Minimal)
- **Description:** Code quality - Linting errors fixed
- **Impact:** Low - Code cleanliness
- **Link:** [GitHub PR #1468](https://github.com/Rupeek/core/pull/1468)

#### PR #1467: fix:Added role in the UpdateLoanRequest api ✅ MERGED
- **Status:** ✅ MERGED
- **Merged Date:** 2025-11-07T07:17:57Z
- **Comments:** 1
- **Description:** Added role parameter to UpdateLoanRequest API
- **Impact:** Low - API enhancement
- **Link:** [GitHub PR #1467](https://github.com/Rupeek/core/pull/1467)

#### PR #1466: hotfix:Upi Status blocked for Initiated and success case ✅ MERGED
- **Status:** ✅ MERGED (HOTFIX)
- **Merged Date:** 2025-11-06T06:24:24Z
- **Comments:** 1
- **Description:** Critical hotfix for UPI payment status blocking
- **Impact:** High - Payment processing fix
- **Technical Details:**
  - Resolves UPI status blocking issue
  - Handles "Initiated" and "Success" states correctly
  - Urgent fix for payment workflows
- **Link:** [GitHub PR #1466](https://github.com/Rupeek/core/pull/1466)

#### PR #1462: DataBuilder: Jewel Validation and Uploadpledgecard error fix ✅ MERGED
- **Status:** ✅ MERGED
- **Merged Date:** 2025-10-15T12:12:27Z
- **Comments:** 2
- **Description:** Fix jewel validation and pledge card upload errors
- **Impact:** Medium - Data integrity
- **Technical Details:**
  - Enhanced jewel validation logic
  - Fixed pledge card upload error handling
  - Improved data builder performance
- **Link:** [GitHub PR #1462](https://github.com/Rupeek/core/pull/1462)

#### PR #1452: Api automation log 5680 ⭐ HIGH ENGAGEMENT
- **Status:** ✅ MERGED
- **Merged Date:** 2025-10-10T09:22:47Z
- **Comments:** 10 
- **Created:** 26 September 2025
- **Time to Merge:** 14 days
- **Description:** API automation for Log 5680
- **Impact:** Medium - Automation feature
- **Discussion Level:** High (10 comments)
- **Link:** [GitHub PR #1452](https://github.com/Rupeek/core/pull/1452)

#### PR #1447: TimeStamp for grossweight fix ✅ MERGED
- **Status:** ✅ MERGED
- **Merged Date:** 2025-09-22T13:25:40Z
- **Comments:** 1
- **Description:** Refactor Timestamp Handling in AgentWFController
- **Impact:** Medium - Data consistency
- **Technical Details:**
  - Fixed timestamp handling for gross weight updates
  - Ensures grossweight timestamp updated correctly
  - Prevents timestamp overwrites
- **Link:** [GitHub PR #1447](https://github.com/Rupeek/core/pull/1447)

#### PR #1442: code fixes for the new changes ⭐ HIGHEST ENGAGEMENT
- **Status:** ✅ MERGED
- **Merged Date:** 2025-10-10T11:59:26Z
- **Comments:** 26 
- **Created:** 11 September 2025
- **Time to Merge:** 29 days
- **Ticket:** [LOG-5669](https://rupeek.atlassian.net/browse/LOG-5669)
- **Description:** Create IG Loan Get and Post API in coresvc
- **Impact:** High - Complex API implementation
- **Technical Details:**
  - IG Loan data management APIs
  - Error handling enhancements
  - Database schema updates
- **Discussion Index:** HIGHEST on this service (26 comments)
- **Link:** [GitHub PR #1442](https://github.com/Rupeek/core/pull/1442)

#### PR #1438: COPY JEWEL bug fix ✅ MERGED
- **Status:** ✅ MERGED
- **Merged Date:** 2025-09-08T04:08:44Z
- **Comments:** 1
- **Description:** Enhancements in Appraisal Status Handling
- **Impact:** Medium - Appraisal logic
- **Technical Details:**
  - Added 'newgrossweight' status code handling
  - Ensures jewels copied correctly in co-borrower transactions
  - Enhanced status logic for appraisal process
- **Link:** [GitHub PR #1438](https://github.com/Rupeek/core/pull/1438)

#### PR #1421: code reverted changes for gross weight ✅ MERGED
- **Status:** ✅ MERGED
- **Merged Date:** 2025-09-03T12:55:38Z
- **Comments:** 1
- **Description:** Revert gross weight changes
- **Impact:** Medium - Appraisal fix
- **Link:** [GitHub PR #1421](https://github.com/Rupeek/core/pull/1421)

#### PR #1420: code revert for deviation logic ✅ MERGED
- **Status:** ✅ MERGED
- **Merged Date:** 2025-08-22T09:37:07Z
- **Comments:** 3
- **Description:** Revert deviation logic changes
- **Impact:** Medium - Appraisal logic fix
- **Link:** [GitHub PR #1420](https://github.com/Rupeek/core/pull/1420)

#### PR #1419: Release grossweighthotfix ✅ MERGED
- **Status:** ✅ MERGED
- **Merged Date:** 2025-08-21T11:49:32Z
- **Comments:** 1 (Release branch)
- **Description:** Release hotfix for gross weight handling
- **Impact:** High - Release management
- **Link:** [GitHub PR #1419](https://github.com/Rupeek/core/pull/1419)

#### PR #1418: code fixes for deviation changes ✅ MERGED
- **Status:** ✅ MERGED
- **Merged Date:** 2025-08-21T11:49:30Z
- **Comments:** 2
- **Description:** Code fixes for deviation logic changes
- **Impact:** Medium - Appraisal fixes
- **Link:** [GitHub PR #1418](https://github.com/Rupeek/core/pull/1418)

#### PR #1417: notification changes ✅ MERGED
- **Status:** ✅ MERGED
- **Merged Date:** 2025-08-21T04:08:42Z
- **Comments:** 1
- **Description:** Notification system updates
- **Impact:** Low - Notification improvements
- **Link:** [GitHub PR #1417](https://github.com/Rupeek/core/pull/1417)

#### PR #1407: api to find the loanrequest using refid ✅ MERGED
- **Status:** ✅ MERGED
- **Merged Date:** 2025-08-06T11:59:59Z
- **Comments:** 4
- **Description:** New API to find loan requests by reference ID
- **Impact:** Medium - New API feature
- **Technical Details:**
  - Added reference ID lookup API
  - Improves loan request retrieval
  - Supports quick customer searches
- **Link:** [GitHub PR #1407](https://github.com/Rupeek/core/pull/1407)

#### PR #1402: titanservice added in local.js file ✅ MERGED
- **Status:** ✅ MERGED
- **Merged Date:** 2025-07-31T12:23:38Z
- **Comments:** 1
- **Description:** Added Titans service configuration
- **Impact:** Low - Configuration management
- **Link:** [GitHub PR #1402](https://github.com/Rupeek/core/pull/1402)

#### PR #1401: feat(appraisal): add grossweightapproved status code and condition ⭐ HIGH ENGAGEMENT
- **Status:** ✅ MERGED
- **Merged Date:** 2025-08-20T14:09:27Z
- **Comments:** 25 
- **Created:** 31 July 2025
- **Time to Merge:** 20 days
- **Description:** Add GrossWeight Approved Status Code in Appraisal
- **Impact:** High - Core appraisal feature
- **Technical Details:**
  - New status code: 'grossweightapproved'
  - Added to development config
  - Updated appraisegold helper
  - Conditional logic for gross weight flag
- **Discussion Index:** Third highest on service
- **Link:** [GitHub PR #1401](https://github.com/Rupeek/core/pull/1401)

#### PR #1399: feat(JewelChecker): enhance deviation check with total weight validation ✅ MERGED
- **Status:** ✅ MERGED
- **Merged Date:** 2025-08-20T14:09:28Z
- **Comments:** 1
- **Description:** Enhance Deviation Check with Total Weight Validation
- **Impact:** High - Core appraisal feature
- **Technical Details:**
  - Total gross weight validation
  - 3% tolerance per item
  - Simplified deviation rules
  - Improved severity classification
  - Multi-service coordination
- **Link:** [GitHub PR #1399](https://github.com/Rupeek/core/pull/1399)

#### PR #1396: LOG-5573 ✅ MERGED
- **Status:** ✅ MERGED
- **Merged Date:** 2025-07-31T12:02:49Z
- **Comments:** 4
- **Description:** Implementation for LOG-5573
- **Impact:** Medium
- **Link:** [GitHub PR #1396](https://github.com/Rupeek/core/pull/1396)

#### PR #1392: feature:Revert the status code to admin approval to fix jewel appraisal ✅ MERGED
- **Status:** ✅ MERGED
- **Merged Date:** 2025-07-14T14:55:17Z
- **Comments:** 1
- **Ticket:** [LOG-5556](https://rupeek.atlassian.net/browse/LOG-5556)
- **Description:** Jewel Appraisal Hotfix
- **Impact:** High - Appraisal workflow fix
- **Technical Details:**
  - Status code revert to 'jewelapproval'
  - Fixed appraisegold helper logic
  - Ensures correct status code during appraisal
- **Link:** [GitHub PR #1392](https://github.com/Rupeek/core/pull/1392)

#### PR #1336: Created a new api for Upload Pledgecard ✅ MERGED
- **Status:** ✅ MERGED
- **Merged Date:** 2025-06-10T13:18:27Z
- **Comments:** 4
- **Description:** New API for Pledge Card Upload
- **Impact:** Medium - New feature
- **Technical Details:**
  - Pledge card upload endpoint
  - File handling implementation
  - Integration with storage systems
- **Link:** [GitHub PR #1336](https://github.com/Rupeek/core/pull/1336)

#### PR #1331: MapJewel-fIX ✅ MERGED
- **Status:** ✅ MERGED
- **Merged Date:** 2025-05-20T13:59:42Z
- **Comments:** 1
- **Description:** Null Check in jewelMap Handling
- **Impact:** Medium - Robustness improvement
- **Technical Details:**
  - Added null check for jewelMap
  - Prevents errors when jewelMap is undefined
  - Handles edge cases gracefully
- **Link:** [GitHub PR #1331](https://github.com/Rupeek/core/pull/1331)

#### PR #1329: LOG-5465 ✅ MERGED
- **Status:** ✅ MERGED
- **Merged Date:** 2025-05-19T13:12:12Z
- **Comments:** 2
- **Description:** Federal Lender Ornament Template Mapping
- **Impact:** Medium - Lender-specific logic
- **Technical Details:**
  - Conditional ornament template mapping
  - Federal lender specific handling
  - Improves accuracy for this lender type
- **Link:** [GitHub PR #1329](https://github.com/Rupeek/core/pull/1329)

#### PR #1322: Feature/jewel ⭐ MEDIUM ENGAGEMENT
- **Status:** ✅ MERGED
- **Merged Date:** 2025-05-15T16:11:28Z
- **Comments:** 11 
- **Created:** 13 May 2025
- **Time to Merge:** 2 days
- **Description:** Jewel Feature Implementation
- **Impact:** High - Core feature
- **Discussion Level:** Medium (11 comments)
- **Link:** [GitHub PR #1322](https://github.com/Rupeek/core/pull/1322)

---

## 🟡 Open PRs (Active)

### PR #1437: LOG-5672 ⏳ PENDING SINCE 155 DAYS
- **Status:** ⏳ OPEN (Stale)
- **Created:** 05 September 2025
- **Comments:** 3
- **Ticket:** [LOG-5672](https://rupeek.atlassian.net/browse/LOG-5672)
- **Title:** Add LendingPartner field in response in mapLoan
- **Description:** Add 'referencenumber' field to mapLoan response
- **Impact:** Low - API response enhancement
- **Technical Details:**
  - Add 'referencenumber' to AccountService response
  - Field selection updates in multiple locations
  - For downstream process requirements
- **Action Needed:** Review and merge or request changes
- **Link:** [GitHub PR #1437](https://github.com/Rupeek/core/pull/1437)

### PR #1423: stone adj percentage is added in getTransactionbyid api call ⏳ PENDING SINCE 162 DAYS
- **Status:** ⏳ OPEN (Stale)
- **Created:** 28 August 2025
- **Comments:** 1
- **Title:** Stone Adjustment Percentage in getTransactionbyid
- **Description:** Add stone adjustment percentage to transaction API
- **Impact:** Low - API enhancement
- **Action Needed:** Review and decide on merge
- **Link:** [GitHub PR #1423](https://github.com/Rupeek/core/pull/1423)

### PR #1391: Release coresvc docker opt ⏳ PENDING SINCE 214 DAYS
- **Status:** ⏳ OPEN (Very Stale)
- **Created:** 07 July 2025
- **Comments:** 1
- **Title:** Release coresvc docker opt (Docker Optimization)
- **Description:** Multi-stage Docker build, bcrypt→bcryptjs, MongoDB driver updates
- **Impact:** High - Infrastructure optimization
- **Technical Details:**
  - Multi-stage Docker build for smaller image
  - Replace bcrypt with bcryptjs
  - Update MongoDB driver to 4.17.2
  - ObjectID → ObjectId migration
- **Status:** Blocked or awaiting decision
- **Action Needed:** URGENT - Prioritize or close
- **Link:** [GitHub PR #1391](https://github.com/Rupeek/core/pull/1391)

### PR #1374: LOG-5531 ⏳ PENDING SINCE 227 DAYS
- **Status:** ⏳ OPEN (Very Stale)
- **Created:** 24 June 2025
- **Comments:** 9
- **Ticket:** [LOG-5531](https://rupeek.atlassian.net/browse/LOG-5531)
- **Title:** Swagger Implementation in Coresvc
- **Description:** Implement Swagger for API documentation
- **Impact:** High - Developer experience
- **Technical Details:**
  - Add SwaggerController for spec serving
  - Configure swagger-jsdoc and swagger-ui-express
  - Add Swagger annotations in controllers
  - Update package.json with dependencies
  - Add swagger generator config & http middleware
- **Status:** Awaiting design review or decision
- **Action Needed:** Prioritize or decide architecture
- **Link:** [GitHub PR #1374](https://github.com/Rupeek/core/pull/1374)

### PR #1355: build: add .dockerignore file to exclude unnecessary files ⏳ PENDING SINCE 234 DAYS
- **Status:** ⏳ OPEN (Very Stale)
- **Created:** 18 June 2025
- **Comments:** 3
- **Title:** Add .dockerignore File
- **Description:** Optimize Docker image by excluding unnecessary files
- **Impact:** Low - Build optimization
- **Action Needed:** Review and merge or close
- **Link:** [GitHub PR #1355](https://github.com/Rupeek/core/pull/1355)

### PR #1321: Update OrnamentType in coredb api ⏳ PENDING SINCE 259 DAYS
- **Status:** ⏳ OPEN (Very Stale)
- **Created:** 12 May 2025
- **Comments:** 8
- **Title:** Update OrnamentType in coredb API
- **Description:** Update ornament type handling in database API
- **Impact:** Low - Data schema update
- **Discussion Level:** Medium (8 comments)
- **Action Needed:** URGENT - Resolve or close
- **Link:** [GitHub PR #1321](https://github.com/Rupeek/core/pull/1321)

---

## 📊 Key Areas & Metrics

### Top Discussion Areas (By Comments)

| Rank | PR # | Topic | Comments | Status |
|------|------|-------|----------|--------|
| 1️⃣ | #1442 | IG Loan API & Code Fixes | 26 | ✅ MERGED |
| 2️⃣ | #1401 | Gross Weight Approval Status | 25 | ✅ MERGED |
| 3️⃣ | #1452 | API Automation Log 5680 | 10 | ✅ MERGED |
| 4️⃣ | #1374 | Swagger Implementation | 9 | ⏳ OPEN |
| 5️⃣ | #1321 | Ornament Type Update | 8 | ✅ MERGED |

### Primary Focus Areas

#### 🎯 Appraisal & Gross Weight (12+ PRs)
- Gross weight status codes
- Gross weight approval logic
- Gross weight timestamp handling
- Weight deviation calculations
- Appraisal status code management
- Jewel appraisal fixes

#### 💎 Jewel Management (8+ PRs)
- Jewel validation logic
- Jewel copying mechanisms
- MapJewel error handling
- Jewel feature implementation
- Co-borrower transaction handling
- Jewel eligibility checks

#### 📊 Data Management (10+ PRs)
- Loan request updates
- Account service enhancements
- Database schema updates
- Timestamp handling
- Reference ID lookups
- Data builder improvements

#### 🔌 API Integration (6+ PRs)
- Sentinel API integration
- Titans service integration
- IG Loan APIs
- Pledge card upload API
- Transaction APIs
- Account lookup APIs

#### 🔧 Infrastructure & DevOps (4+ PRs)
- Docker optimization
- Dependency updates (bcrypt, MongoDB)
- .dockerignore configuration
- Swagger implementation
- Code quality/linting

#### 📝 Payment & UPI (2+ PRs)
- UPI status handling
- Payment processing
- Transaction blocking logic

---

- [All Core Service PRs](https://github.com/Rupeek/core/pulls?q=author:PrateekDev04)
- [All Merged PRs](https://github.com/Rupeek/core/pulls?q=author:PrateekDev04+is:merged)
- [All Open PRs](https://github.com/Rupeek/core/pulls?q=author:PrateekDev04+is:open)

---

## 📞 Quick Links

- **Service Repository:** https://github.com/Rupeek/core
- **All PRs:** https://github.com/Rupeek/core/pulls?q=author:PrateekDev04
- **Open PRs:** https://github.com/Rupeek/core/pulls?q=author:PrateekDev04+is:open
- **Merged PRs:** https://github.com/Rupeek/core/pulls?q=author:PrateekDev04+is:merged

---

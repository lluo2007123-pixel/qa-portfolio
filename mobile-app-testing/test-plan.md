# WUVO Spot – Test Plan

---

## 1. Introduction

### 1.1 Project Overview
WUVO Spot is a Bluetooth-based mobile application that allows users to track and locate personal items such as keys, wallets, and bags. The app uses proximity tracking, last-known location, and community-based recovery features.

### 1.2 Objective
The purpose of this test plan is to:
- Validate application functionality and performance
- Identify defects before release
- Ensure a smooth and user-friendly experience
- Reduce production risks

---

## 2. Scope

### 2.1 In Scope
The following modules will be tested:

- Dashboard (Item overview)
- Device Pairing / Add Device
- Find Item (Radar / Proximity tracking)
- Map View (Last known location)
- Lost Mode (Community tracking)
- Alerts & Notifications
- Find My Phone (Reverse tracking)
- Item Detail Management
- Lost & Found (Contact owner)

### 2.2 Out of Scope
- Hardware/firmware testing of tracking device
- Third-party map service reliability
- Network provider performance

---

## 3. Test Strategy

### 3.1 Testing Types

#### Functional Testing
- Verify all features work as expected
- Validate end-to-end user flows

#### Usability Testing
- Evaluate UI/UX and ease of navigation
- Identify confusing or inefficient flows

#### Performance Testing
- API response time (via Postman)
- App loading time
- Map loading speed

#### Compatibility Testing
- iOS and Android devices
- Different screen sizes and OS versions

#### Negative Testing
- Invalid inputs
- Permission denial scenarios
- Network interruptions

#### Exploratory Testing
- Simulate real-world usage
- Identify edge cases and hidden bugs

---

## 4. Test Environment

### 4.1 Devices
- iPhone (iOS 15+)
- Android devices (Android 10+)

### 4.2 Network Conditions
- Wi-Fi (strong/weak)
- Mobile data (4G/5G)
- Offline mode

### 4.3 Tools

- Test Case Management: Excel / Google Sheets
- API Testing: Postman
- Bug Tracking: Jira / Trello
- Screen Recording: Loom / OBS

---

## 5. Entry and Exit Criteria

### 5.1 Entry Criteria
- Requirements are defined
- App build is available and stable
- Test environment is ready

### 5.2 Exit Criteria
- All critical and high-priority bugs are resolved
- Test cases executed ≥ 95%
- Pass rate ≥ 90%
- No blocker defects remain

---

## 6. Test Deliverables

- Test Plan Document
- Test Cases (Excel)
- Bug Reports
- API Test Report
- Test Execution Summary

---

## 7. Risk Analysis

| Risk                         | Impact | Mitigation |
|------------------------------|--------|-----------|
| Bluetooth instability        | High   | Test on multiple devices |
| Location inaccuracies        | Medium | Real-world movement testing |
| Notification delays          | Medium | Test under different networks |
| App crashes                  | High   | Perform stress testing |

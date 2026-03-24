# WUVO Spot – Test Plan

## 1. Introduction

### 1.1 Project Overview
WUVO Spot is a Bluetooth-based mobile application that allows users to track and locate personal items such as keys, wallets, and bags. The app uses proximity tracking, last-known location, and community-based recovery features.

### 1.2 Objective
The purpose of this test plan is to:
- Validate application functionality and performance
- Identify defects before release
- Ensure a smooth and user-friendly experience
- Reduce production risks


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


## 4. Test Environment

### 4.1 Devices
- iPhone (iOS 26)

### 4.2 Network Conditions
- Wi-Fi 
- Mobile data (5G)
- Offline

### 4.3 Tools
- API Testing: Postman
- Bug Tracking: Jira
- Screen Recording: Loom 

## 5. Entry and Exit Criteria

### 5.1 Entry Criteria
- Requirements are defined
- App build is available and stable

### 5.2 Exit Criteria
- All critical and high-priority bugs are resolved
- Test cases executed ≥ 95%
- Pass rate ≥ 90%
- No blocker defects remain

## 6. Test Deliverables

- Test Plan Document
- Test Cases (Excel)
- Bug Reports
- API Test Report
- 
## 7. Risk Analysis

| Risk                         | Impact | Mitigation |
|------------------------------|--------|-----------|
| Bluetooth instability        | High   | Test on multiple devices |
| Location inaccuracies        | Medium | Real-world movement testing |
| Notification delays          | Medium | Test under different networks |
| App crashes                  | High   | Perform stress testing |

## 8. High-Level Test Scenarios

### Dashboard
- View all items
- Check connection status
- Navigate to other features

### Device Pairing
- Add new device
- Handle connection failures
- Prevent duplicate pairing

### Find Item
- Radar accuracy
- Sound trigger functionality
- Signal strength updates

### Map View
- Display last known location
- Timestamp accuracy
- Navigation integration

### Lost Mode
- Enable/disable lost mode
- Receive updates
- Ensure privacy

### Alerts
- Trigger out-of-range alerts
- Customize distance
- Notification delivery

### Find My Phone
- Trigger phone ring
- Work in silent mode

### Lost & Found
- Enter valid/invalid Spot ID
- Contact owner securely

## 9. Defect Management

### Severity Levels
- Critical: App crash, data loss
- Major: Core feature not working
- Minor: UI/UX issues

### Bug Lifecycle
New → Assigned → In Progress → Fixed → Retest → Closed

---

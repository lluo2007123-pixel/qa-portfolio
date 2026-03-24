# WUVO Spot –  Bug Reports 


##  BUG-013: Device Does Not Reconnect Automatically After Returning to Range

**Module:** Connectivity / Dashboard  
**Severity:** Major  
**Priority:** High  
**Environment:** iPhone 13, iOS 17, Bluetooth enabled  

### Description
After a tracked device goes out of Bluetooth range and then comes back into range, the app fails to automatically reconnect.

### Preconditions
- Device is paired and working  
- Bluetooth is ON  

### Steps to Reproduce
1. Open WUVO Spot app  
2. Ensure device is connected  
3. Move out of Bluetooth range  
4. Wait until status shows “Disconnected”  
5. Move back into range  

### Expected Result
- Device should automatically reconnect  
- Status updates to “Connected”  

### Actual Result
- Device remains in “Disconnected” state  
- Requires manual refresh or app restart  

### Impact
- Breaks core functionality (real-time tracking)  
- Reduces user trust in reliability  

### Notes
- Common issue in Bluetooth tracking apps  

## BUG-021: Incorrect Last Known Location Displayed on Map

**Module:** Map View  
**Severity:** Critical  
**Priority:** High  
**Environment:** Android 12, Google Pixel 6  

### Description
The app shows an outdated or incorrect location for the tracked item on the map.

### Preconditions
- Location permissions enabled  
- Device moved to a new location  

### Steps to Reproduce
1. Connect a Spot device  
2. Move to Location A  
3. Disconnect device  
4. Move to Location B with device  
5. Open Map View  

### Expected Result
- Map shows Location B (latest known position)  

### Actual Result
- Map still shows Location A  

### Impact
- Users cannot accurately recover lost items  
- Critical failure of core feature  

### Notes
- Possibly due to delayed location sync or caching issue  

---

## 🐞 BUG-053: Out-of-Range Alert Not Triggered Reliably

**Module:** Alerts & Notifications  
**Severity:** Major  
**Priority:** High  
**Environment:** iPhone 13, iOS 17 (Background mode)  

### Description
Out-of-range alerts fail to trigger consistently when the user moves away from the tracked item.

### Preconditions
- Alerts enabled  
- App running in background  

### Steps to Reproduce
1. Enable “Out of Range Alert”  
2. Leave device behind  
3. Walk beyond set distance  

### Expected Result
- User receives push notification immediately  

### Actual Result
- No alert received OR delayed by several minutes  

### Impact
- Users may lose items without warning  
- Core preventive feature fails  

### Notes
- Likely related to background execution limits  


## BUG-132: “Find My Phone” Feature Fails in Silent Mode

**Module:** Find My Phone  
**Severity:** Major  
**Priority:** Medium  
**Environment:** iPhone 13, iOS 17

### Description
Phone does not ring when triggered via Spot device if the phone is in silent mode.

### Preconditions
- Phone set to silent mode  
- Device connected  

### Steps to Reproduce
1. Set phone to silent  
2. Double press Spot device button  
3. Wait for response  

### Expected Result
- Phone should ring regardless of silent mode  

### Actual Result
- No sound is emitted  

### Impact
- Feature becomes unreliable  
- Reduces usefulness in real scenarios  

### Notes
- Silent mode override not functioning  

---


### AtChats – Real-time Messaging App
##### Tech Stack: Flutter, Riverpod, Node.js, Express.js, Socket.IO, MongoDB, WebRTC

Built a cross-platform Flutter chat application supporting real-time 1-to-1 and group messaging with Socket.IO. Implemented file sharing, emoji reactions, and presence indicators. Integrated WebRTC mesh architecture for low-latency, high-quality video calls. Designed scalable MongoDB schemas and Express.js APIs to handle thousands of concurrent users.

---

### Chat Page
- Real-time 1-to-1 messaging with typing indicators and read receipts.  
- Online/offline presence and smooth message pagination.  

### Group Chat Page
- Group creation and real-time group messaging.  
- Supports reactions, media messages, and presence indicators.

### Image & File Messaging
- Send and preview images, videos, and documents.  
- Background upload with retry logic and file-type detection.

### Reactions
- Add emoji reactions to individual messages.  
- Real-time synchronization across all connected devices.

### Continue Video Call
- Seamlessly switch between chat and ongoing video call.  
- Mini floating video preview for multitasking.

### Video Calling Screen
- High-quality video calling using WebRTC.  
- Mute/unmute, camera toggle, switch camera, and end-call controls.  
- Adaptive bitrate for stable video on slow networks.

### In-Video Screen (During Call)
- Grid layout for multiple participants.  
- Live network quality indicators and picture-in-picture support.

### Video Receiving Popup
- Incoming call popup with Accept/Reject options.  
- Distinct ringtone and vibration alerts.  
- Auto-timeout if unanswered.

### Login Page
- Clean email/password login form with real-time validation.  
- Error prompts and smooth redirection to chat dashboard.

### Sign Up Page
- Registration with Name, Email, and Password fields.  
- Strong password validation and duplicate email detection.  
- Auto-login after successful registration.
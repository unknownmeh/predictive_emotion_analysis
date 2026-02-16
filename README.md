# 🎭 Advanced Emotion Recognition System

A real-time AI-powered emotion detection application that analyzes facial expressions and identifies over 70+ human emotions using advanced deep learning models.
**Predictive Emotion Analysis** is a computer vision project that detects human emotions from facial expressions using real-time webcam input or uploaded images.  
The system analyzes facial features and predicts emotions such as happy, angry, calm, cool, rude, and love using machine learning techniques. 


## 🌟 Features

- **🎯 70+ Emotion Detection**: Identifies complex emotional states beyond basic emotions
- **📸 Multiple Input Methods**: 
  - Upload images for analysis
  - Real-time camera capture
- **👥 Multi-Face Detection**: Analyzes up to 3 faces simultaneously
- **⚡ Real-time Processing**: Instant emotion analysis with live results
- **📊 Detailed Results**: Primary emotion with confidence scores and distribution
- **📱 Fully Responsive**: Works seamlessly on desktop, tablet, and mobile devices
- **🎨 Modern UI**: Beautiful dark purple/blue gradient theme
- **🔒 Protected Code**: Basic anti-inspection measures included

## 🚀 Demo

![Emotion Detection Demo]([(https://unknownmeh.github.io/predictive_emotion_analysis/)])

## 🛠️ Technologies Used

- **Frontend**: HTML5, CSS3, JavaScript (ES6+)
- **AI/ML Library**: [Face-api.js]
- **Deep Learning Models**: 
  - TinyFaceDetector (face detection)
  - FaceExpressionNet (emotion recognition)
- **Design**: Custom CSS with gradient themes and animations

## 📋 Requirements

- Modern web browser (Chrome, Firefox, Safari, Edge)
- HTTPS connection or localhost (required for camera access)
- Stable internet connection (for loading AI models)
- Webcam (optional, for live camera feature)



## 💻 Usage

### Upload Image Mode
1. Click **"Upload Image"** button
2. Select an image from your device
3. Wait for automatic analysis
4. View emotion results in the results panel

### Live Camera Mode
1. Click **"Live Camera"** button
2. Allow camera permissions when prompted
3. Position your face in the camera view
4. Click **"Capture & Analyze"** button
5. View real-time emotion analysis

### Multi-Face Detection
- Upload group photos or use camera with multiple people
- System detects and analyzes up to 3 faces
- Each face gets numbered results (Face 1, Face 2, Face 3)

## 🧠 Detected Emotions

### Base Emotions (7)
- 😊 Happy
- 😢 Sad
- 😠 Angry
- 😮 Surprised
- 😨 Fearful
- 🤢 Disgusted
- 😐 Neutral

### Extended Emotions (60+)
Including: Joyful, Excited, Content, Grateful, Optimistic, Depressed, Lonely, Melancholic, Anxious, Worried, Frustrated, Irritated, Shocked, Amazed, Curious, Bored, Calm, Peaceful, and many more...

## 📐 System Architecture

```
┌─────────────────────────────────────────┐
│         User Interface (HTML/CSS)        │
├─────────────────────────────────────────┤
│     JavaScript Application Logic         │
├─────────────────────────────────────────┤
│         Face-api.js Library              │
├─────────────────────────────────────────┤
│   TinyFaceDetector + FaceExpressionNet  │
├─────────────────────────────────────────┤
│         TensorFlow.js Backend            │
└─────────────────────────────────────────┘
```

## 🎨 UI Components

### Layout Structure
- **Header**: Application title and instructions
- **Options Panel**: Upload and Camera buttons
- **Preview Box**: 1:1 aspect ratio display (600px height)
- **Results Box**: Scrollable results panel (600px height)

### Design Highlights
- Dark purple/blue gradient background
- Indigo accent colors (#6366f1, #8b5cf6)
- Smooth animations and transitions
- Responsive grid layout
- Touch-friendly buttons for mobile

## 🔒 Security Features

The application includes basic protection measures:

- ✅ Right-click disabled
- ✅ Keyboard shortcuts blocked (F12, Ctrl+Shift+I, etc.)
- ✅ DevTools detection with screen blanking
- ✅ Console auto-clear
- ✅ Text selection disabled
- ✅ Copy prevention
- ✅ Debugger traps

**Note**: These are deterrents for casual users. Determined developers can bypass these protections.

## 📱 Browser Compatibility

| Browser | Desktop | Mobile |
|---------|---------|--------|
| Chrome  | ✅ | ✅ |
| Firefox | ✅ | ✅ |
| Safari  | ✅ | ✅ |
| Edge    | ✅ | ✅ |
| Oper



## 🐛 Troubleshooting

### Camera Not Working
1. **Check permissions**: Ensure browser has camera access
2. **Use HTTPS**: Camera requires secure connection (or localhost)
3. **Check other apps**: Close apps using the camera
4. **Try test button**: Use "🔍 Test Camera" button for diagnostics

### No Face Detected
1. **Lighting**: Ensure face is well-lit
2. **Distance**: Position face clearly in frame
3. **Angle**: Face camera directly
4. **Quality**: Use higher resolution images

### Slow Performance
1. **Close other tabs**: Free up browser resources
2. **Update browser**: Use latest version
3. **Check connection**: Ensure stable internet for model loading
4. **Reduce faces**: Limit to 3 or fewer faces

## 📊 Performance

- **Model Load Time**: ~2-5 seconds (first time)
- **Face Detection**: ~100-300ms per frame
- **Emotion Analysis**: ~200-500ms per face
- **Total Processing**: ~1-2 seconds for single face


## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.


## 📧 Contact

Name: Lucifer  
Email: unknownmeh666@gmail.com  
Project: Predictive Emotion Analysis

## 🔮 Future Enhancements

- [ ] Add more emotion categories
- [ ] Export results as PDF/JSON
- [ ] Emotion history tracking
- [ ] Multi-language support
- [ ] Backend API integration
- [ ] Batch image processing
- [ ] Video file analysis
- [ ] Real-time emotion trends graph
- [ ] Age and gender detection
- [ ] Custom model training

## 📈 Changelog

### Version 1.0.0 (2026)
- Initial release
- 70+ emotion detection
- Multi-face support (up to 3)
- Live camera and image upload
- Responsive design
- Basic code protection

---

⭐ THANK YOU ⭐

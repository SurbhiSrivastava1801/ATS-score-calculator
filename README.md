# ATS Score Calculator

A comprehensive web application that analyzes resumes and provides detailed recommendations to achieve 95%+ ATS (Applicant Tracking System) scores. Built with modern web technologies and advanced scoring algorithms.

## 🚀 Features

### Core Functionality
- **File Upload Support**: PDF, DOC, DOCX, and TXT files
- **Drag & Drop Interface**: Modern, intuitive file upload experience
- **Real-time Analysis**: Instant resume scoring and feedback
- **Comprehensive Scoring**: 8 different criteria analyzed

### ATS Analysis Criteria
1. **Formatting & Structure** (20 points)
   - Line breaks and proper formatting
   - Bullet points usage
   - Consistent section headers
   - ATS-friendly characters

2. **Keyword Optimization** (20 points)
   - Industry-relevant keywords
   - Action verbs usage
   - Technical terminology

3. **Contact Information** (20 points)
   - Email address presence
   - Phone number format
   - Location information
   - Professional profile links

4. **Professional Experience** (20 points)
   - Experience section structure
   - Job titles clarity
   - Company names
   - Employment dates

5. **Education Section** (20 points)
   - Education section presence
   - Degree information
   - Institution names

6. **Skills & Competencies** (20 points)
   - Skills section organization
   - Technical skills listing
   - Soft skills inclusion

7. **Resume Length** (20 points)
   - Optimal word count (300-800 words)
   - Page length considerations

8. **Achievements & Impact** (20 points)
   - Quantified achievements
   - Action verb usage
   - Results-oriented language

### Advanced Features
- **Industry-Specific Keywords**: Analysis for Software, Marketing, Finance, Healthcare, and General industries
- **Detailed Recommendations**: Specific suggestions to improve each area
- **Progress Tracking**: Visual score representation with animated progress
- **Report Generation**: Downloadable detailed analysis report
- **Responsive Design**: Works on desktop, tablet, and mobile devices

## 🎯 How to Use

1. **Upload Your Resume**
   - Drag and drop your resume file or click to browse
   - Supported formats: PDF, DOC, DOCX, TXT

2. **View Analysis Results**
   - Overall ATS score with visual progress circle
   - Detailed breakdown of each scoring criteria
   - Specific issues and suggestions for improvement

3. **Review Recommendations**
   - Prioritized recommendations to reach 95%+ score
   - Industry-specific keyword suggestions
   - Best practices for ATS optimization

4. **Download Report**
   - Get a detailed text report of your analysis
   - Save recommendations for future reference

## 🏆 Achieving 95%+ ATS Score

### Essential Requirements
- **ATS-Friendly Format**: Use simple fonts (Arial, Calibri, Times New Roman)
- **Standard Sections**: Experience, Education, Skills, Contact Information
- **Keyword Optimization**: Include relevant industry keywords
- **Quantified Achievements**: Use numbers, percentages, and metrics
- **Consistent Formatting**: Uniform headers, bullet points, and spacing

### Pro Tips
1. **Research Job Descriptions**: Use keywords from your target job postings
2. **Use Action Verbs**: Start bullet points with strong action verbs
3. **Quantify Everything**: Include specific numbers and results
4. **Keep It Simple**: Avoid graphics, tables, and complex formatting
5. **Optimize Length**: Aim for 1-2 pages maximum
6. **Include Contact Info**: Make sure all contact information is easily findable

## 🛠️ Technical Details

### Built With
- **HTML5**: Semantic markup and modern structure
- **CSS3**: Advanced styling with Flexbox and Grid
- **Vanilla JavaScript**: No dependencies, fast and lightweight
- **Font Awesome**: Professional icons
- **Google Fonts**: Inter font family for modern typography

### Browser Support
- Chrome 60+
- Firefox 55+
- Safari 12+
- Edge 79+

### File Processing
- **Text Files**: Direct text extraction
- **PDF Files**: Simulated text extraction (in production, use PDF.js)
- **Word Documents**: Simulated text extraction (in production, use mammoth.js)

## 📊 Scoring Algorithm

The ATS Score Calculator uses a sophisticated algorithm that evaluates resumes across multiple dimensions:

```
Overall Score = (Formatting + Keywords + Contact + Experience + Education + Skills + Length + Achievements) / 8
```

Each category is scored from 0-100, with specific criteria for each score range:
- **90-100**: Excellent - ATS optimized
- **80-89**: Good - Minor improvements needed
- **70-79**: Fair - Several improvements needed
- **Below 70**: Poor - Major improvements required

## 🎨 Design Features

- **Modern UI**: Clean, professional interface
- **Responsive Design**: Works on all device sizes
- **Smooth Animations**: Engaging user experience
- **Color-Coded Results**: Easy to understand scoring
- **Progress Visualization**: Animated score circles
- **Accessibility**: Screen reader friendly

## 🔧 Customization

The application is highly customizable:

### Adding New Industries
```javascript
// Add to industryKeywords object in script.js
'your-industry': ['keyword1', 'keyword2', 'keyword3']
```

### Modifying Scoring Criteria
```javascript
// Adjust scoring weights in analyzeResume method
analysis.breakdown.yourCategory = this.analyzeYourCategory(text);
```

### Styling Customization
- Modify `styles.css` for visual changes
- Update color scheme in CSS variables
- Adjust responsive breakpoints

## 📈 Future Enhancements

- **Real PDF/DOC Parsing**: Integration with PDF.js and mammoth.js
- **Job Description Matching**: Compare resume against specific job postings
- **Industry Templates**: Pre-built resume templates for different industries
- **A/B Testing**: Compare different resume versions
- **Integration APIs**: Connect with job boards and ATS systems
- **Advanced Analytics**: Detailed keyword density analysis

## 🤝 Contributing

This is a standalone application that can be easily extended. To contribute:

1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Test thoroughly
5. Submit a pull request

## 📄 License

This project is open source and available under the MIT License.

## 🆘 Support

For questions or issues:
1. Check the browser console for error messages
2. Ensure your file format is supported
3. Try with a different resume file
4. Contact support for technical issues

---

**Built with ❤️ to help job seekers optimize their resumes and land more interviews.**

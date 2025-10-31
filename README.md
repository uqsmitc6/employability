# EmployAbility Toolkit Website

## File Structure

```
employability-website/
├── index.html                          # Main homepage
├── video-case-studies.html             # Video case studies page
├── images/
│   ├── logo.png                        # PNG-Australia Partnership logo
│   └── illustration.jpg                # Header illustration
└── downloads/
    ├── EmployAbility_Toolkit.pdf       # Main toolkit PDF
    ├── Case_Studies.pdf                # Case studies PDF
    └── wdigs/                          # WDIGS grant application documents
        ├── Application_Guidelines.pdf
        ├── Eligibility_Checklist.pdf
        ├── Application_Form.docx
        ├── Project_Costings_Template.xlsx
        ├── Workplan_Template.docx
        ├── Selection_Criteria_Guide.pdf
        └── Supporting_Documents_Checklist.pdf
```

## Deployment Instructions

### For Web Server Deployment:

1. **Upload all files and folders** to your web server, maintaining the folder structure exactly as shown above.

2. **Ensure file permissions** are set correctly:
   - HTML files: 644 (readable by all)
   - PDF/DOCX/XLSX files: 644 (readable by all)
   - Directories: 755 (accessible by all)

3. **Set index.html** as your default/home page (most web servers do this automatically).

4. **Test the website** by:
   - Opening index.html in a browser
   - Clicking all download links to verify they work
   - Clicking the video case studies button
   - Checking that videos load properly

### Video Case Studies:

The video case studies page contains two embedded Vimeo videos:
- Video 1: https://vimeo.com/1116935285/ac2b43f0c1
- Video 2: https://vimeo.com/1116947783/3ef80c3eda

These are embedded and will stream directly from Vimeo (no download required).

### Notes:

- All file paths are relative, so the structure must be maintained
- The website is fully responsive and works on mobile devices
- All downloads are set to download directly when clicked
- Colours match the official EmployAbility Toolkit branding (#3B7C7C)

## Browser Compatibility

The website works on all modern browsers:
- Chrome/Edge (recommended)
- Firefox
- Safari
- Mobile browsers

## Contact

For questions about the EmployAbility Project:
APEP EmployAbility Team

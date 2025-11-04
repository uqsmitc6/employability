# EmployAbility Toolkit Website

A responsive website for the EmployAbility Project, an initiative supporting Papua New Guinea to increase participation of people with disabilities in the employment market.

## About

The EmployAbility project is implemented by the Australia Papua New Guinea Economic Partnership (APEP) and supported by the Australian Government. This website provides access to:

- The EmployAbility Toolkit (PDF guide for employers)
- Case studies showcasing workplace inclusion initiatives
- Video case studies featuring real stories from PNG
- Workplace Disability Inclusion Grant Scheme (WDIGS) application materials

## File Structure

```
employability-website/
├── index.html                          # Homepage
├── grants.html                         # WDIGS grant application page
├── video-case-studies.html             # Video case studies page
├── .htaccess                           # HTTPS redirect and security headers
├── images/
│   ├── logo.png                        # PNG-Australia Partnership logo
│   ├── hero-main.jpg                   # Homepage hero image
│   ├── hero-grants.jpg                 # Grants page hero image
│   └── hero-video-case-studies.jpg     # Video page hero image
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

## Pages

### 1. Homepage (index.html)
- Hero section with EmployAbility Toolkit branding
- Four main action buttons:
  - Download the EmployAbility Toolkit (PDF)
  - Apply for a Workplace Disability Inclusion Grant
  - View the EmployAbility Case Studies (video page)
  - Download the Case Studies (PDF)
- Acknowledgement section
- PNG-Australia Partnership branding

### 2. Grants Page (grants.html)
- Information about the Workplace Disability Inclusion Grant Scheme (WDIGS)
- Application deadline: 30 November 2025
- Contact information: info@cufa.org.au
- Downloadable application forms:
  - Application Form (DOCX)
  - Project Costings Template (XLSX)
  - Work Plan Document (DOCX)
- Downloadable supporting documents:
  - Eligibility Checklist (PDF)
  - Application Guidelines (PDF)
  - Selection Criteria Guide (PDF)
  - Supporting Documents Checklist (PDF)

### 3. Video Case Studies Page (video-case-studies.html)
Six embedded Vimeo videos showcasing real stories of workplace inclusion in PNG:

1. **Building pathways to inclusive employment** – Cheshire Disability Services PNG
2. **From inclusive education to employment** – The University of Goroka
3. **Work experience internships for people with disability** – The Stanley Hotel & Suites
4. **Accessibility and inclusion in the workplace** – Brenda Lombange
5. **Employment and entrepreneurship as a Deaf woman** – Clare Guria
6. **Rejoining the workforce after acquiring disability** – Nelsie Kofiaba

## Design & Branding

### Colour Scheme
- **Primary Green**: #067771 (headings, links, CTA button)
- **Purple**: #49274B (action buttons, subpage headings)
- **Background**: #f5f9f9 (light grey-blue)
- **White**: #ffffff (content sections)

### Typography
- Headings: Large, bold typography with mixed weights
- Body: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif
- Responsive sizing for mobile devices

### Layout
- Desktop: Two-column grid with text left, image right
- Mobile: Single column, stacked layout
- Fully responsive design

## Deployment Instructions

### Prerequisites
- Web hosting with cPanel access (e.g., Namecheap)
- Domain name configured
- SSL certificate installed (free via Let's Encrypt/AutoSSL)

### Step 1: Enable SSL (if not already enabled)
1. Log into your hosting cPanel
2. Navigate to **SSL/TLS Status** in the Security section
3. Enable **AutoSSL** for automatic free SSL certificate
4. Wait 10-20 minutes for activation

### Step 2: Upload Files
1. In cPanel, open **File Manager**
2. Navigate to `public_html` (or your domain's root directory)
3. Upload all files maintaining the exact folder structure shown above
4. Ensure the `.htaccess` file is uploaded to the root directory
   - **Note**: Enable "Show Hidden Files" in File Manager settings to see `.htaccess`

### Step 3: Set File Permissions
- HTML files: 644
- PDF/DOCX/XLSX files: 644
- Image files: 644
- Directories: 755
- .htaccess: 644

### Step 4: Test the Website
1. Visit your domain (https://yourdomain.com)
2. Verify HTTPS redirect is working (HTTP should redirect to HTTPS)
3. Test all download links
4. Check video embedding on the case studies page
5. Test navigation between all pages
6. Verify mobile responsiveness

## Technical Features

### Security
- HTTPS forced via .htaccess
- Security headers configured:
  - Strict-Transport-Security
  - X-Content-Type-Options
  - X-Frame-Options
  - X-XSS-Protection

### Video Integration
- Videos embedded from Vimeo
- Responsive 16:9 aspect ratio
- No external hosting required
- Videos stream directly from Vimeo

### Accessibility
- Semantic HTML structure
- Alt text on images
- Readable colour contrast
- Keyboard navigation support
- Mobile-friendly touch targets

## Browser Compatibility

Tested and compatible with:
- Google Chrome/Edge (latest)
- Mozilla Firefox (latest)
- Safari (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

Minimum browser versions:
- Chrome 90+
- Firefox 88+
- Safari 14+
- Edge 90+

## Maintenance

### Updating Content
- **PDF files**: Upload new versions to `/downloads/` directory
- **Video case studies**: Update Vimeo embed codes in `video-case-studies.html`
- **Grant deadline**: Update date in `grants.html`
- **Contact information**: Update email in `grants.html`

### Adding New Documents
1. Upload files to appropriate `/downloads/` subdirectory
2. Add download link in relevant HTML file
3. Maintain consistent styling with existing links

## Contact & Support

**EmployAbility Project Team**  
Email: info@cufa.org.au

**Project Information**  
Website: employabilitytoolkit.org  
Partnership: Australia Papua New Guinea Economic Partnership (APEP)

## Version History

- **v2.0** (November 2025) - Updated layout, added HTTPS, added 6 video case studies
- **v1.0** (October 2025) - Initial website launch

## License

© 2025 EmployAbility Project | Australia Papua New Guinea Economic Partnership (APEP)

This website is part of an initiative supported by the Australian Government.

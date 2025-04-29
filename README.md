### connected_corpus
Repo for connected corpus work

## Note for future assistants/people that will work on this:
- We have the HTML files uploaded in the HTML folder --  this contains all the HTML from the original pubpub website (About Page, Books 1-10, etc); everything except for the annotations
- We also have a CSS template to go alongside with the HTML provided
- We have the scraping jupyter notebook that was able to scrape the annotations from the pubpub books; the JSON file should be provided elsewhere, but if needed, you can download it onto your local computer using this notebook
  

## Next Steps:
# 1. Organize the Repository Structure
```
connected_corpus/
├── index.html              # Main landing page
├── about/                  # About section
├── books/                  # All book content
│   ├── book1/
│   ├── book2/
│   └── ...
├── annotations/            # Processed annotations
├── css/
│   └── style.css           # Main stylesheet
├── js/                     # JavaScript files
├── assets/                 # Images, fonts, etc.
└── _config.yml             # GitHub Pages config
```

# 2. Process the Annotations
Review the scraped annotations JSON:
Ensure the JSON is properly structured
Validate that all annotations are captured correctly
Check for any missing data
Create an annotation display system:
Design how annotations will appear alongside text
Decide on interaction patterns (popups, sidebars, etc.)
Implement JavaScript to handle annotation display

# 3. Integrate HTML Content with GitHub Pages
Set up GitHub Pages:
Enable GitHub Pages in repository settings
Choose the main branch as source
Add a basic _config.yml file

Standardize HTML files:
Ensure consistent structure across all HTML files
Add proper meta tags and accessibility attributes
Make sure all internal links work correctly

# Personal Fan Works Website

A Streamlit-based personal website for showcasing and managing fan works, collections, and creative logs.

## Features

### 1. Works Showcase
- Display fan art, fan fiction, and handmade works
- Support for multiple file formats:
  - Images (JPG, PNG, JPEG)
  - Text files (TXT)
  - Word documents (DOC, DOCX)
- Preview functionality for all file types
- Organized display with 2 works per row
- Category-based filtering

### 2. Collections
- Curated collection of fan works from various sources
- Categories:
  - Fan Art
  - Fan Fiction
  - Fan Videos
- Detailed information for each collection:
  - Title
  - Author
  - Source
  - Tags
  - Collection date
  - Direct links to original content

### 3. Creative Log
- Document creative process and inspiration
- Log types:
  - Creative Plan
  - Creative Process
  - Creative Thoughts
  - Other
- Chronological display of entries
- Rich text support

### 4. About Me
- Personal information section
- Contact details
- Creative preferences
- Favorite works
- Dislikes

## Technical Requirements

### Python Dependencies
```
streamlit
pillow
python-docx
pandas
plotly
```

### Installation
1. Clone the repository
2. Install required packages:
```bash
pip install streamlit pillow python-docx pandas plotly
```

### Running the Website
```bash
streamlit run "个人网站 copy.py"
```

## File Structure
- `个人网站 copy.py`: Main application file
- Image files: Stored in specified directories
- Document files: Stored in specified directories

## Features in Detail

### Works Management
- Add new works with titles, descriptions, and dates
- Upload various file types
- Preview functionality for all supported formats
- Automatic file type detection and appropriate display

### Collections Management
- Add new collections with detailed metadata
- Categorize collections by type
- Link to original sources
- Tag system for easy organization

### Creative Log
- Add new log entries
- Categorize entries by type
- Chronological organization
- Rich text support for detailed documentation

### User Interface
- Clean, modern design
- Responsive layout
- Easy navigation
- Category-based filtering
- Preview functionality

## Customization
The website can be customized by modifying:
- CSS styles in the main file
- Categories and types
- Display layouts
- File handling methods

## Notes
- All file paths should be updated according to your system
- Image and document files should be placed in the correct directories
- The website uses session state to maintain data between runs

## License
© 2025 Algae's Kingdom | Made with ❤️ 
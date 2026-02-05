# pdf-annotation-extractor
Extract PDF highlights and comments into CSV just for reading pdf not really a serious qualitative research - a free alternative to NVivo/ATLAS.ti
# PDF Annotation Extractor for Research

A simple Python tool to extract highlights and comments from annotated PDFs and organize them into CSV files for qualitative analysis. Think of it as a free, lightweight alternative to NVivo that you actually own and control.

## Why I Built This

I'm a PhD student working with 600+ papers for my dissertation. I wanted:
- A system I could understand and modify
- Something that works offline
- No ongoing subscription costs
- Complete ownership of my data
- A tool that researchers anywhere in the world could use

[Read the full story on my Substack →](your-substack-link-here)

## What It Does

- 📝 Extract highlights from PDFs (Mendeley, Adobe, any PDF reader)
- 🏷️ Organize quotes by themes and subcodes
- 📊 Output everything to CSV/Excel
- 🔄 Support nested coding up to 5 levels (like `Theory>Antecedent>Signaling>Quality>Emotional`)
- 💾 Keep all your data in simple, portable formats

## Quick Start

### Prerequisites
- Python 3.7+
- PyMuPDF: `pip install PyMuPDF`
- A CSV file with your article metadata (must include DOI column)

### Usage

1. **Find your highlight colors** (different PDF readers use different codes):
```bash
   python find_my_colors.py
```

2. **Annotate your PDFs:**
   - Add a comment on page 1: `DOI: 10.1177/your-doi-here`
   - Highlight text and add comments like: `Theory>Institutional>Legitimacy`

3. **Run the extraction:**
```bash
   python extract_annotations.py
```

4. **Open the output CSV** in Excel and see your coded data!

## Example

**Your highlight comment:** `Antecedent>Emotionality>Negative`

**Highlighted text:** "Social media amplifies negative emotions during crises"

**Result in CSV:** 
- Column: `Antecedent_Emotionality_Negative`
- Value: "Social media amplifies negative emotions during crises"

## Files Included

- `extract_annotations.py` - Main extraction script
- `find_my_colors.py` - Diagnostic tool to find your PDF reader's color codes
- `README.md` - This file with complete instructions

## Detailed Instructions

See [INSTRUCTIONS.md](link-to-full-instructions) for step-by-step setup guide.

## Who This Is For

- PhD students and researchers doing literature reviews
- Anyone tired of expensive qualitative analysis software
- Researchers who want to own their data and workflow
- People in regions where software costs are prohibitive
- Anyone who wants a simple, transparent coding system

## Cost

Free. Forever. No subscriptions, no licenses, no limits.

## License

MIT License - use it, modify it, share it.

## Questions?

Open an issue or leave a comment on [my Substack post](your-link).

## Support This Project

If this saved you time or money, consider:
- ⭐ Starring this repository
- 📢 Sharing with other researchers
- ✍️ Writing about your experience using it

---

Built with ❤️ by a PhD student who just wanted a simpler way to build a second brain/simple cataloguing.
```

### Step 5: Get Your Share Link

Your repository URL will be something like:
```
https://github.com/yourusername/pdf-annotation-extractor

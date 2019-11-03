# extract_bib
A simple script to extract bibtex of papers in top conferences.

## Motivation
To accelerate the process of downloading bibtex files from official websites.

## Usage
1. Download `extract_bib.py`.
2. Modify the keywords and target websites.
3. Run `python extract_bib.py`.
4. You will get a `.bib` file in which papers' titles match at least one keyword.

## Known Issues
1. The result is not very accurate. For example, `keyword=gan`, it returns `gan`, `gang`.

## Current Applicable Conferences
- ICCV
- ECCV
- CVPR

## To Do
- [ ] Fix issues.
- [ ] Download corresponding pdf files meanwhile.
- [ ] Support ICML, ICLR, NeurIPS.

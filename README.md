mkdir sanjeevani-3-0-release-decision && cd sanjeevani-3-0-release-decision
cp /path/to/README.md .
cp /path/to/UST_AITPM_Week4_Ex2_Answer_Workbook_Parts1-4_v2.docx .
git init && git add . && git commit -m "Week 4 Ex2: Sanjeevani 3.0 release decision"
git branch -M main
git remote add origin https://github.com/<your-username>/sanjeevani-3-0-release-decision.git
git push -u origin main

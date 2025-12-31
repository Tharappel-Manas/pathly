# pathly
AI Verse Hackathon Project

Resume parsing is completely functional and supports both PDF and image files.
The resume is parsed into structured JSON with skills, tools, and experience details successfully.
A pipeline relating working roles/jobs with TF-IDF and Cosine Similarity is used.
Matching takes place against a “local roles database” as well as real job postings through “the Adzuna API,” presumably based on search parameters established .
System provides Top-N role/jobs suggestions based on similarity scores.
End-to-end pipeline starting from uploading a resume to extraction, matching, and result is functioning well in the prototype.

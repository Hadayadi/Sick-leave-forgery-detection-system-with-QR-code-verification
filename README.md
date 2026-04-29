# Sick-leave-forgery-detection-system-with-QR-code-verification
Seha Sick Leave Authenticity Checker 

Forgery checks it runs (in order):

QR Code destination — should link to seha.sa/#/inquiries/slenquiry
Leave ID format — must be PSL + 14 digits
Document structure — required sections, logos, branding
Date consistency — admission ≤ discharge ≤ issue date
Leave duration match — stated days must match date range
Hospital license number — 16-digit format starting with 38
Verification URL present — the seha.sa link must appear in the doc
Print timestamp — generation date vs issue date gap (>7 days = suspicious)
Visual integrity — font inconsistencies, overlaid text, edits
Seha branding — National Health Information Centre logo, Kingdom header

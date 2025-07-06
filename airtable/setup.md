# TLDR

Info regarding setting up Airtable

## High Level Description

1. Create an Airtable account
1. Create a Base in your account
1. Create tables in you base: `Scripts`, `Script Segments`, `Characters`
    - check out the `diagrams/airtable_hierarachy.png` file for reference

## `Scripts` Table Schema

- Script ID (Autonumber) [Primary field]
- Script (Long text)
- Narrated Audio (Attachment)
- Narrated Audio URL (URL)
- Script Segments (Link to Script Segments)
    - Used to see which records in the Script Segments table belong to which script

## `Script Segments` Table Schema

- Row ID (Number) [Primary field]
- Script (Single line text)
- Start Time (Duration)
    - Precision: Hours or smaller
    - Duration Format: h:mm:ss.ss
    - Thousands and decimal separators: Local
- End Time (Duration)
    - Precision: Hours or smaller
    - Duration Format: h:mm:ss.ss
    - Thousands and decimal separators: Local
- Image (Attachment)
- Image URL (URL)
- Image Prompt (Long text)
- Video Prompt (Long text)
- Video URL (URL)
- Full Script (Link to Scripts)
- B Roll (Checkbox)

## `Characters` Table Schema

- Name (Number) [Primary field]
- Images (Attachment)

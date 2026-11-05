# Check-In: Youth Mental Health Survey Analysis

What are South Texas teens really carrying with them? During my remote internship with the Mid Rio Grande Border Area Health Education Center (MRGB AHEC), I analyzed 266 anonymous responses collected at youth mental health outreach events in Laredo, Texas, and turned them into an interactive data story.

**[View the live page](https://cejastephanie2006-cell.github.io/ahec-check-in/)**

> **Content note:** this project covers stress, grief and self-worth. Concerns appear only as counts, never as quotes. If you or someone you know is struggling, call or text **988**, the Suicide & Crisis Lifeline.

## Key findings

1. **Almost half of all responses raised a concern.** 129 of 266 answers (48%) flagged stress, sadness, worry or something heavier.
2. **Concern outweighed positive answers at 4 of 5 high schools.** Alexander High School was the only exception.
3. **The weight is internal as much as academic.** Mental health struggles (32) and confidence and self-worth (30) came up as often as school stress (26).
4. **People opened up when given the chance.** 86% of answers to "Is there a problem you want to vent about?" raised a concern.
5. **People showed up for each other.** 28 responses were notes of encouragement written for someone else, like "You're worth it" and "Hang in there."
6. **One response needed action right away.** It was flagged for immediate follow-up and is counted but never shown.

## The data

- **266 anonymous responses** from 6 outreach events between May 1 and May 20, 2026
- **Events:** Mental Health & Substance Abuse Symposium, LBJ High School, Nixon High School, Alexander High School, United High School and United South High School
- **Questions asked** (each event used a different mix):
  - Is there a problem you want to vent about?
  - How are you feeling today?
  - How do you practice self-care?
  - Is there anything on your mind you want to put into words?
  - When school feels overwhelming, what signs do you notice?
  - How comfortable do you feel talking about mental health?
- **7 responses** were written in Spanish and translated to English

## How I built it

1. **Excel:** compiled the responses, gave each one a sentiment (positive, concern, mixed or neutral), and tagged it with one or more theme codes like school stress, family stress, prayer and faith, or encouragement.
2. **Analysis:** compared sentiment and themes across events and questions to find the patterns that mattered most.
3. **Claude:** designed the interactive page around the AHEC logo, including its star, sun and river.

## What's on the page

- **A star made of 266 dots,** one per response, colored by sentiment. It rearranges into groups by event or by question.
- **A mood chart** balanced on a center line, with concern on the left and positive on the right
- **A theme map** showing how often each concern came up at each event
- **A "What helps" section** with the coping strategies people shared and a rotating set of encouraging quotes
- **Filters** that update every chart for one event, plus a switch that hides school names
- Light and dark mode, plus a phone layout

## Protecting the people who answered

- Every response was anonymous. No names or IDs were collected.
- Only positive and encouraging responses are quoted. Concerns are shown as counts.
- The response flagged for follow-up is counted but never displayed.
- A content note and the 988 Suicide & Crisis Lifeline appear at the top of the page.

## Tools

Excel · Data Analysis · Data Visualization · Claude (AI-assisted design) · HTML · CSS · JavaScript · D3.js

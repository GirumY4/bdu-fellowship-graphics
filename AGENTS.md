# BDU Fellowship Graphics Design System

## Project Overview

This repository contains reusable HTML/CSS templates for Bahir Dar University (BDU) Fellowship graphics.

The goal is NOT to generate random posters.

The goal is to build a professional, reusable, maintainable graphics system that shares one visual identity across all fellowship announcements.

Every graphic should feel like it belongs to the same organization.

The reference folder contains sample designs that represent the desired quality and design direction.

---

## Current Graphics

1. Online Fellowship Announcement
2. Program Announcement
3. Program Speaker
4. Bible Verse Card

Future graphics should reuse the same design language.

---

## Design Philosophy

Professional

Modern

Youth-oriented

Spiritually uplifting

Minimal but expressive

Readable on mobile

Suitable for Instagram and Telegram

Print-ready and when used as image it must fit for instagram and telegram posters cleanly

---

## Technology

HTML

Custom CSS

SVG Icons

Local Fonts

No UI Frameworks

---

## Required Workflow

Before designing ANY graphic:

1. Inspect the entire assets folder.

2. Discover every available font.

3. Discover every SVG icon.

4. Discover the VLM logo.

5. Discover every image that could be used as background.

6. Discover the reference folder.

7. Read this AGENTS.md completely.

8. Build assets/theme.css first.

Only after theme.css and typography.css are finished may any graphic be designed.

---

## Theme

theme.css should become the single source of truth.

Never duplicate colors.

Never duplicate shadows.

Never duplicate font names.

Never duplicate spacing.

Every graphic imports theme.css.

---

## Color Palette

Primary

#3B1E8F

Secondary

#2563EB

Accent Gold

#FBBF24

Accent Emerald

#22C55E

White

#FFFFFF

Background

#F8FAFC

Dark

#111827

Muted

#64748B

Danger

#DC2626

---

## Typography

Latin Heading

use from assets/fonts/latin-text-fonts/Professional-Sans-Serif

Latin Body

use from assets/fonts/latin-text-fonts/Professional-Sans-Serif

Amharic

use from assets/fonts/amharic-text-fonts

Handwritten Highlight

use from assets/fonts/latin-text-fonts/Handwrittenlike-Fonts

Elegant Verse

use from assets/fonts/latin-text-fonts/Elegant-Serif

Never substitute these fonts.

---

## Icons

Only use the local SVG icons stored inside assets/icons.

Keep icon sizes visually consistent.

---

## Logo

Always use the VLM logo.

Respect clear space around the logo.

Do not distort the logo.

Prefer SVG over PNG(but not mandatory).

---

## Images

Use local images whenever possible.

Prefer fellowship photographs over stock photography.

Images should never overpower the text.

---

## Layout

Every poster should have:

Strong hierarchy

Large heading

Supporting subtitle

Readable Amharic typography

Good whitespace

Consistent margins

Balanced alignment

Professional spacing

---

## Components

theme.css should support reusable components including:

Buttons

Date badge

Time badge

QR block

Logo container

Speaker card

Verse card

Image overlay

Footer

Section titles

---

## Accessibility

Ensure readable contrast.

Do not place text directly over busy images.

Use overlays when necessary.

---

## Quality Checklist

Before completing any task:

✓ Typography is consistent.

✓ Colors follow theme.css.

✓ Icons come from assets/icons.

✓ Fonts come from assets/fonts.

✓ Logo is correctly positioned.

✓ Mobile readability is verified.

✓ Layout is visually balanced.

✓ Text never overlaps.

✓ All reusable styles belong in theme.css.

✓ Graphic-specific styles belong only in stylesX.css.

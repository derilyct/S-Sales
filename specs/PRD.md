---
title: S-Sales Product Requirements Document
description: Requirements for a personal shoe sales listing page
ms.date: 2026-04-24
---

## Overview

S-Sales is a single-page website where Derick can list shoes he wants to sell from his personal collection in Staley Hills. Visitors browse available kicks, filter by brand or size, and see key details like condition, pricing, and lot number at a glance. A future admin page will let Derick create and manage shoe entries that appear on this public listing.

## Features

### 1. Hero Introduction Section

The page opens with a bold, personal greeting that introduces the seller and location. A "Scroll Down" call-to-action link in a contrasting color (blue) guides visitors to the shoe listings below. The text should be large, uppercase, and high-impact.

### 2. Brand Filter Dropdown

A collapsible dropdown labeled "BRANDS" lets visitors filter the shoe listings by brand name. Selecting a brand narrows the visible cards to only shoes from that brand. The dropdown displays with a chevron indicator showing its expand/collapse state.

### 3. Size Filter Dropdown

A collapsible dropdown labeled "SIZES" lets visitors filter listings by shoe size. This works alongside the brand filter so visitors can combine both to narrow results. The dropdown sits directly below the brand filter.

### 4. Shoe Listing Cards

Each shoe displays as a card containing a large image area at the top and a details section below. Cards are stacked vertically in a single-column layout. The image area should support placeholder states when no photo is available.

### 5. Shoe Detail Fields

Below each shoe image, the card displays four labeled data points in a horizontal row:

- SIZE: the shoe size (e.g., "10 / 10.5")
- WEAR: a numeric wear rating indicating condition
- LOT #: a lot or inventory number for tracking
- PRICE: the asking price, displayed with a dollar sign and bolded

A "DISC" label sits above these fields with a short text description of the shoe.

### 6. Responsive Mobile-First Layout

The page is designed mobile-first with a single-column card layout. All text, filters, and cards should scale cleanly on phone screens and remain usable on tablets and desktops without horizontal scrolling.

### 7. Contact Section

A persistent contact button is fixed to the bottom-right corner of the screen so it remains visible as visitors scroll. Tapping or clicking the button expands a small panel that displays Derick's contact information (name, phone, email, or other preferred channels). Tapping the button again or clicking outside the panel collapses it back to the compact button state. The button and panel must not obscure shoe cards when collapsed and should be styled to complement the page's existing color palette.

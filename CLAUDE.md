# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

This repository contains a single-page application presentation built as a static HTML file (`presentazine.html`) for Landoor, a translation services company. The presentation showcases strategic value and acquisition arguments for business stakeholders.

## Project Structure

The repository contains only one main file:
- `presentazine.html` - A comprehensive business presentation with multiple interactive sections including overview, revenue calendar, strategic value, AI leadership, trade shows, and integration planning

## Architecture

**Single-File Application**: The entire presentation is contained within one HTML file that includes:
- Embedded CSS styling with modern design patterns (glassmorphism, gradients, animations)
- Vanilla JavaScript for page navigation and interactivity
- Responsive design with mobile-first approach
- Multi-page navigation simulation using CSS classes

**Key Features**:
- Fixed navigation with smooth page transitions
- Interactive stat cards and hover effects
- Timeline visualization for trade shows
- Grid-based layouts for content organization
- Professional color scheme with purple/blue gradients

## Development Commands

Since this is a static HTML file, no build tools or package managers are required:

**Local Development**:
- Open `presentazine.html` directly in any web browser
- No server required for basic functionality
- For development with live reload, use any static file server

**Testing**:
- Visual testing: Open in different browsers and screen sizes
- Functionality testing: Navigate through all sections using the top navigation
- Mobile testing: Test responsive behavior on mobile devices

## Content Structure

The presentation is organized into six main sections:
1. **Overview** - Key metrics and value proposition
2. **Revenue Calendar** - Monthly sector-focused campaigns
3. **Strategic Value** - Contract terms and consultant positioning
4. **AI Leadership** - Thought leadership content and positioning
5. **Trade Shows** - Annual event calendar and management
6. **Integration Plan** - Acquisition value proposition and risk mitigation

## Styling Guidelines

- Uses modern CSS with custom properties and gradients
- Consistent spacing using 40px base unit
- Card-based design pattern with rgba backgrounds
- Hover animations and smooth transitions
- Mobile-responsive breakpoints at 768px

## Modification Guidelines

When updating content:
- Maintain consistent visual hierarchy and spacing
- Preserve the existing color scheme and gradient patterns
- Ensure all navigation links remain functional
- Test responsiveness after any layout changes
- Keep the professional tone and business-focused messaging

## Browser Compatibility

The code uses modern CSS features including:
- CSS Grid and Flexbox
- CSS Custom Properties (variables)
- Backdrop-filter effects
- Advanced selectors and pseudo-elements

Target browsers: Modern versions of Chrome, Firefox, Safari, and Edge.
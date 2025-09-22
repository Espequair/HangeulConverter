# Korean Hangeul Practice

## Overview

This is a Korean Hangeul (한글) practice application designed to help users learn and practice Korean vocabulary through romanization conversion. The application is a single-page web application built with vanilla HTML, CSS, and JavaScript, focusing on providing an interactive learning experience with real Korean vocabulary words.

The application features two practice modes: converting Hangeul to romanization and converting romanization to Hangeul, using a curated database of common Korean vocabulary words with their English meanings displayed for context.

## User Preferences

Preferred communication style: Simple, everyday language.

## System Architecture

### Frontend Architecture
- **Technology Stack**: Single-page static HTML with embedded CSS and JavaScript
- **Design Pattern**: Tab-based interface with two practice modes (Hangeul→Romanization and Romanization→Hangeul)
- **Styling Approach**: Modern responsive CSS with purple gradient theme and mobile-first design
- **Layout Strategy**: Centered container layout optimized for learning across devices

### Core Features
- **Dual Practice Modes**: Convert Hangeul to romanization or romanization to Hangeul
- **Vocabulary Database**: 50+ common Korean words across categories (colors, numbers, family, verbs, nouns, adjectives, days)
- **Real-time Feedback**: Input validation with supportive feedback that doesn't immediately reveal answers
- **User Experience Enhancements**: Autofocus on inputs, prevention of immediate word repetition, normalized input matching
- **Educational Context**: Each word displays English meaning alongside the practice prompt

### Technical Implementation
- **Input Validation**: Smart feedback system with partial matching hints for romanization input
- **Accessibility**: Keyboard support (Enter to advance), focus management, clear visual feedback states
- **Deployment Ready**: Single HTML file with no external dependencies, optimized for GitHub Pages
- **Responsive Design**: Mobile-optimized interface with touch-friendly controls

## External Dependencies

### Browser APIs
- Standard web APIs for DOM manipulation and user interaction
- CSS3 features for modern styling (gradients, flexbox, border-radius, box-shadow)
- Responsive design capabilities through viewport meta tag

### Font Resources
- System font stack leveraging native OS fonts (no external font dependencies)
- Supports multiple platforms: Apple system fonts, Windows Segoe UI, Android Roboto

### No External Services
- Self-contained application with no apparent third-party service integrations
- No database connections or external API calls visible in the current structure
- Likely stores learning progress and preferences in browser localStorage
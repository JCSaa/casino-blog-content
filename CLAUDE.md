# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

This is a casino industry blog content repository containing markdown articles organized by category. The content focuses on casino operations, gaming regulations, table games, slot operations, and industry best practices.

## Repository Structure

```
articles/
├── marketing-player-development/  # Marketing and player development content
├── performance-analysis/          # Casino performance and analytics
├── regulatory-updates/           # Gaming regulation changes and compliance
├── slot-operations/             # Slot machine operations and management
├── strategy/                    # Casino strategy and business practices
├── table-games/                # Table game operations and procedures
└── team-building/              # Staff training and team development

assets/
└── images/                     # Image assets for blog articles
```

## Article Format

All articles follow a consistent frontmatter structure:
- `title`: Article title
- `category`: Matches directory structure (e.g., "regulatory-updates", "table-games")
- `author`: Content author
- `date`: Publication date (YYYY-MM-DD format)
- `tags`: Array of relevant tags
- `premium`: Boolean for premium content designation
- `reading_time`: Estimated reading time in minutes
- `summary`: Brief article description
- `featured_image`: Path to article image in assets/

## Content Guidelines

- Articles focus on legitimate casino operations and industry practices
- Content covers regulatory compliance, operational efficiency, and best practices
- Target audience includes casino managers, operators, and industry professionals
- All content should be professional and industry-appropriate

## Development Notes

This is a content-only repository with no build process or dependencies. All articles are static markdown files that can be edited directly.
# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

This repository contains a comprehensive padel court business financial model and presentation materials for a proposed 8-court padel facility in Limassol, Cyprus. The project includes:

- **Financial Analysis Document**: Comprehensive business plan with market research, cost analysis, revenue projections, and ROI calculations
- **Interactive Financial Model**: HTML-based financial calculator with dynamic inputs and visualizations
- **Branding Materials**: Multiple logo design options in SVG format

## Project Structure

- `Comprehensive Financial Model for Padel Court Busi.md` - Detailed business plan and market analysis
- `padel_financial_model.html` - Interactive web-based financial calculator with dark/light theme support
- `padel_logo.svg`, `logo_option2.svg` through `logo_option5.svg` - Logo design variations

## Technical Details

The interactive financial model (`padel_financial_model.html`) is a standalone HTML application featuring:

- **Frontend Framework**: Vanilla JavaScript with modern ES6+ features
- **Styling**: CSS custom properties (CSS variables) with light/dark theme support
- **Charts**: Integrated charting library for financial visualizations
- **Responsive Design**: Mobile-friendly layout with CSS Grid and Flexbox
- **Interactive Elements**: Real-time calculation updates based on user input parameters

## Key Business Parameters

The financial model uses these core assumptions:
- Initial investment: €380,000 for 8 courts
- Court construction cost: €35,000 per court (fully equipped)
- Annual operating costs: €230,600
- Target occupancy: 50% (base case)
- Pricing: €28/hour average rate
- Break-even occupancy: 20.2%

## Development Notes

- This is a static project with no build system or dependencies
- The HTML file can be opened directly in a browser for testing
- SVG logos are optimized and ready for web/print use
- All financial calculations are client-side JavaScript

## Usage

To view the interactive model:
```bash
open padel_financial_model.html
```

The model includes sensitivity analysis for various scenarios (Conservative, Base Case, Optimistic, Premium) with adjustable parameters for occupancy rates, pricing, and operational costs.
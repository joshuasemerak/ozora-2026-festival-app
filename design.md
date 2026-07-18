# DESIGN.md - Apple Human Interface System for Web

## Core Design Tokens
- Primary Background: #FFFFFF (Light Mode), #000000 (Dark Mode) [True Pure Black]
- Secondary Background: #F2F2F7 (Light Mode), #1C1C1E (Dark Mode) [Elevated Grouped Gray]
- Text Primary: #1D1D1F (Light), #F5F5F7 (Dark)
- Text Secondary: #86868B (Light), #8E8E93 (Dark)
- Accent Tint: #007AFF (iOS System Blue) or #0066CC (Interactive Blue)
- System Borders: 1px solid rgba(0, 0, 0, 0.1) / rgba(255, 255, 255, 0.1)

## Typography Hierarchy (SF Pro Scale)
- Large Title: 34px, Bold, Tracking: 0.37
- Title 1: 28px, Semi-Bold, Tracking: 0.36
- Title 2: 22px, Regular, Tracking: 0.35
- Headline: 17px, Semi-Bold, Tracking: -0.41
- Body: 17px, Regular, Tracking: -0.41
- Callout: 16px, Regular, Tracking: -0.32
- Subhead: 15px, Regular, Tracking: -0.24

## Component Layout Constraints
- Interactive Target Size: Minimum 44px x 44px spacing for all buttons/links.
- Grid Layout: Strict 8-point spatial grid system (Padding scales: 8px, 16px, 24px, 32px, 48px).
- Border Radius:
  - Default Buttons / Input Fields: 12px
  - Content Cards / Large Modals: 16px to 20px
  - Form Groups: 10px

## UI Elements & Materials
- Blurs: Backdrop-filter: blur(20px) alpha-blended with 70% opacity white/black for navigation headers.
- Lists: Grouped list structure with uniform rounded edges. Nested link lists must conclude with an asset-matching right chevron (›).
- Icons: Use only standardized, clean typography weights matching SF Symbols naming styles. No abstract box icons.

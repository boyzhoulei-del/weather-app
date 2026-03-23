# Weather App Specification - Hangzhou

## Project Overview
- **Project Name**: Hangzhou Weather
- **Type**: Single-page weather dashboard
- **Core Functionality**: Display real-time weather for Hangzhou with forecast
- **Target Users**: Local residents checking daily weather

## Visual & Rendering Specification

### Aesthetic Direction
**Moody Atmospheric** - 深色渐变背景配合雨滴氛围，让人联想到江南烟雨

### Color Palette
- **Background**: Deep navy to charcoal gradient (#0a0f1a → #1a1f2e)
- **Primary Accent**: Soft cyan (#7dd3fc)
- **Secondary**: Warm amber (#fbbf24) for temperature
- **Text**: Off-white (#f1f5f9) with muted gray (#94a3b8)
- **Rain Effect**: Translucent cyan drops

### Typography
- **Display Font**: "Playfair Display" (elegant serif for temperature)
- **Body Font**: "DM Sans" (clean, modern)

### Layout
- Centered card layout with glassmorphism
- Current weather hero section
- Animated rain particles in background
- Subtle floating clouds

## Weather Data (Hangzhou - 2026-03-23)
- **Current**: 13°C, Light Rain
- **Feels Like**: 13°C
- **Humidity**: 82%
- **Wind**: 7 km/h (ENE)
- **Pressure**: 1018 hPa
- **Visibility**: 10 km
- **Sunrise**: 06:00
- **Sunset**: 18:12

## Animation Specification
- Rain drops falling with CSS animation
- Temperature number counter animation on load
- Gentle card entrance animation
- Weather icon pulse effect

## Acceptance Criteria
1. Page loads with smooth entrance animation
2. Rain particles animate continuously
3. All weather data displayed correctly
4. Responsive on mobile and desktop
5. Glassmorphism card effect visible

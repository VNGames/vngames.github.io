# Reusable CSS Classes Documentation

This document explains the reusable CSS classes available in `common.css`.

## Feature Cards

Use for feature overview cards with icons:

```html
<div class="feature-card">
    <div class="feature-icon">
        <svg><!-- icon --></svg>
    </div>
    <h3>Feature Title</h3>
    <p>Feature description</p>
</div>
```

## Feature Sections (Screenshot with Description)

Use for alternating image/text sections:

```html
<!-- Left image, right text -->
<div class="feature-section">
    <div class="feature-image">
        <div class="phone-frame max-w-2xl mx-auto">
            <img src="screenshot.png" alt="Description">
        </div>
    </div>
    <div class="feature-content">
        <h3 class="feature-title">Feature Name</h3>
        <p class="feature-description">Description text</p>
        <ul class="check-list">
            <!-- Check items here -->
        </ul>
    </div>
</div>

<!-- Right image, left text (alternating) -->
<div class="feature-section feature-section-reverse">
    <!-- Same structure as above -->
</div>
```

## Checkmark Lists

Use for bullet points with checkmarks:

```html
<ul class="check-list">
    <li class="check-item">
        <svg class="check-icon" fill="none" stroke="currentColor" viewBox="0 0 24 24">
            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M5 13l4 4L19 7"></path>
        </svg>
        <span class="check-text">List item text</span>
    </li>
</ul>
```

## Video Cards

Use for YouTube video links:

```html
<a href="https://youtu.be/..." target="_blank" class="video-card">
    <div class="video-thumbnail">
        <h4 class="text-xl font-bold text-white">Video Title</h4>
        <div class="flex flex-col items-center gap-1">
            <svg class="youtube-icon" viewBox="0 0 159 110">
                <!-- YouTube icon SVG -->
            </svg>
            <span class="youtube-link">Watch on YouTube</span>
        </div>
    </div>
    <div class="video-content">
        <p class="text-gray-600">Video description</p>
    </div>
</a>
```

## Section Containers

Use for page sections:

```html
<section class="page-section">
    <div class="section-header">
        <h2 class="section-title">Section Title</h2>
        <p class="section-subtitle">Section subtitle or description</p>
    </div>
    <!-- Section content -->
</section>
```

## Content Cards

Use for cards with white background and shadow:

```html
<div class="content-card">
    <!-- Card content -->
</div>
```

## Phone Frame

Use for app screenshots:

```html
<div class="phone-frame max-w-xl mx-auto">
    <img src="screenshot.png" alt="App Screenshot">
</div>
```

# Flipkart Accessibility Audit Report

## 1. Project Overview

Website: https://www.flipkart.com/

Purpose: Evaluate website accessibility and performance.

## 2. Audit Methods

- Google PageSpeed Insights mobile audit.
- Manual keyboard navigation testing.
- Inspection of visible interface elements.

## 3. Lighthouse Results

Audit date: 9 October 2026

Device: Mobile

- Performance: 46/100
- Accessibility: 82/100
- Best Practices: 96/100
- SEO: 92/100

## 4. Accessibility Findings

### Finding 1: Keyboard Navigation

Status: Pending manual verification.

Recommendation: Ensure interactive elements are keyboard accessible and have visible focus indicators.

Priority: High if a keyboard accessibility barrier is confirmed.

### Finding 2: Image Alternatives

Status: Pending manual verification.

Recommendation: Provide suitable alternative text for meaningful images.

Priority: High if meaningful images lack alternatives.

### Finding 3: Color Contrast

Status: Lighthouse identified a contrast warning.

Recommendation: Check text and background colors against WCAG contrast requirements.

Priority: High if insufficient contrast is confirmed.

### Finding 4: Form Labels

Status: Pending manual verification.

Recommendation: Ensure search fields and other form controls have accessible names.

Priority: High if controls cannot be identified by assistive technology.

### Finding 5: Heading Structure

Status: Pending manual verification.

Recommendation: Use meaningful headings in a logical hierarchy.

Priority: Medium if heading structure causes navigation difficulties.

## 5. Performance Observations

The mobile Lighthouse report showed:

- Performance score: 46.
- First Contentful Paint: 2.4 seconds.
- Largest Contentful Paint: 18.3 seconds.
- Total Blocking Time: 870 milliseconds.

Recommended improvement: Investigate image delivery, JavaScript execution, and main-thread work.

## 6. Conclusion

The initial mobile audit recorded an accessibility score of 82/100 and a performance score of 46/100.

Manual testing is still required to verify the five accessibility findings. Final priorities should be based on observed issues and their impact on users.

## 7. Evidence

Audit screenshots and the Lighthouse report PDF are stored in the screenshots folder.

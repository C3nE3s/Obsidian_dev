---
author: 'Addy Osmani'
date: 2021-05-21
tags: ['image', 'performance']
aliases: []
createdAt: 2021-12-26
---
# Image Optimization Strategies

## For a fast Largest Contentful Paint
- Request your key image early
- Use ``<picture>``, srcset + efficient modern image formats
- Compress picture, don't serve overly high DPR images
- Lazy load off-screen images
## For a low Cumulative Layout Shift
- Set dimensions for your images
- Use CSS aspect-ratio to reserve space otherwise

## For low impact on First Input Delay
- Avoid images causing network contention 

https://www.youtube.com/watch?v=w6TiSuQkqvY

https://web.dev/fast/#optimize-your-images
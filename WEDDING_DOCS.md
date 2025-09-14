# Wedding Website Documentation

## Overview
This is a simple, elegant wedding information website designed to be private and not indexed by search engines.

## Features
- Clean, responsive design suitable for wedding information
- Comprehensive crawler protection to prevent search engine indexing
- Placeholder sections for wedding details that can be easily customized

## Files
- `index.html` - Main wedding information page
- `robots.txt` - Search engine crawler restrictions
- `.htaccess` - Additional server-side protections (for Apache servers)

## Crawler Protection
The website implements multiple layers of protection against web crawlers:

1. **robots.txt** - Disallows all crawlers from indexing any part of the site
2. **Meta tags** - HTML meta tags prevent indexing by major search engines
3. **HTTP headers** - Server-side headers (via .htaccess) for additional protection

## Customization
To add actual wedding information, edit the placeholder text in `index.html`:
- Date & Time section
- Location details
- RSVP information
- Additional celebration details

## Deployment
The website can be deployed to any web hosting service that supports static HTML files. The crawler protection will work on most standard web servers.
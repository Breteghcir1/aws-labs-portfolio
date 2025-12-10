# Phase 3 – S3 Static Website & Storage

## Overview
Deployed a static website using Amazon S3 with public access controlled through bucket policies.

## What I built
- Created an Amazon S3 bucket for static website hosting
- Enabled static website hosting with an index document
- Configured bucket policies to allow public read access
- Disabled block public access at the bucket level
- Uploaded and served an HTML file from the bucket
- Enabled bucket versioning
- Implemented lifecycle rules to delete noncurrent object versions

## Skills demonstrated
- S3 bucket configuration
- Static website hosting
- Public access management using bucket policies
- Object ownership awareness
- Versioning and lifecycle management
- Troubleshooting S3 access errors (403 / NoSuchKey)

## Notes
AWS S3 Object Ownership defaults require public access to be managed via bucket policies rather than individual object permissions.

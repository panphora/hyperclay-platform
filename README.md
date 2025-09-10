# Hyperclay Platform - Issue Tracker

## About Hyperclay

Hyperclay is a platform and frontend JS library that enables HTML pages to update their DOM and then replace their own `.html` source with the updated version. When users interact with a Hyperclay app (clicking checkboxes, editing content, etc.), the app serializes its entire DOM state and POSTs it to a `/save` endpoint, persisting changes directly in the HTML file itself.

Think of it as a self-modifying HTML file. The UI, logic, and data all live in one portable file that can be edited live, forked by other users, and tracked with automatic versioning. It's designed for building malleable web apps where the developer and content editor are often the same person.

## Purpose

This repository tracks issues, bugs, and feature requests encountered by developers using the Hyperclay SaaS platform.

## Reporting Issues

When creating an issue, please include:

- **Environment**: Browser, OS, and relevant versions
- **Steps to Reproduce**: Clear, numbered steps to recreate the issue
- **Expected Behavior**: What should happen
- **Actual Behavior**: What actually happens
- **Screenshots/Logs**: If applicable
- **Site URL**: If the issue is specific to a site

## Issue Labels

- `bug` - Something isn't working as expected
- `enhancement` - Feature request or improvement
- `documentation` - Documentation improvements needed
- `performance` - Performance-related issues
- `security` - Security vulnerabilities
- `ui/ux` - User interface or experience issues
- `api` - API-related issues
- `critical` - Requires immediate attention

## Support

For general questions or discussions, please contact support@hyperclay.com

## Security

For security vulnerabilities, please email security@hyperclay.com directly instead of creating a public issue.
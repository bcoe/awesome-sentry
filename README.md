<div align='center'>

<!-- title -->

<!--lint ignore no-dead-urls-->

# Awesome Sentry [![Awesome](https://awesome.re/badge.svg)](https://awesome.re) [![lint](https://github.com/bcoe/awesome-sentry/actions/workflows/lint.yaml/badge.svg)](https://github.com/bcoe/awesome-sentry/actions/workflows/lint.yaml)

<!-- subtitle -->

A collection of awesome, articles, videos, and tools, that help you solve common development problems with Sentry. 😎

<!-- image -->

<a href='https://sentry.io' target='_blank' rel='noopener noreferrer'>
  <img src='./sentry-logo.png' />
</a>

<!-- description -->

Sentry instruments your application with observability, such as error tracking and tracing, making it easy to debug and improve your application for real users.

</div>

<!-- TOC -->

## Contents

- [Mobile Development](#mobile-development)
- [Full-Stack Development](#full-stack-development)
- [Sentry using Sentry](#sentry-using-sentry)

<!-- CONTENT -->

## Mobile Development

### Improving User Experience

#### Videos

- [Tracking Critical Paths in React Native](https://www.youtube.com/watch?v=4s8BlzwWiIA) - Using sentry to monitor and improve important user flows in your apps.

#### Tools

- [FaultOrdering](https://github.com/getsentry/FaultOrdering) - Order files can reduce app startup time by co-locating symbols that are accessed during app launch, reducing the number of page faults from the app.

## Full-Stack Development

### Debugging / Monitoring Applications

#### Articles / Docs

- [Logs are Generally Available](https://blog.sentry.io/logs-generally-available/) - Launch announcement for logs. Includes examples for getting started.
- [How Sentry could stop npm from breaking the Internet](https://blog.sentry.io/how-sentry-could-stop-npm-from-breaking-the-internet/) - Using tracing and alerts to catch traffic anomalies before they break an application.
- [Configuring alerts from dashboards in Sentry](https://blog.sentry.io/use-sentry-insights-trigger-alerts-debug-issues/) - Creating alerts from the widgets shown on Sentry [Inights](https://docs.sentry.io/product/insights/) and [Dashboards](https://docs.sentry.io/product/dashboards/custom-dashboards/).
- [Sentry vs. Logging](https://sentry.io/vs/logging/) - Clear overview of how Sentry’s debugging signals differ from traditional logging with guidance on how to use it.
- [Improving browser tracing](https://blog.sentry.io/improving-browser-tracing-step-by-step) - Recent (_Fall 2025_) quality of life improvements for tracing in the browser.
  - Manually end pageload spans with `Sentry.reportPageLoaded();`.
  - Standalone LCP and CLS spans.
  - A slick API for ignoring spans.

#### Videos

- [Setting up Sentry Logs for Next.js](https://www.youtube.com/watch?v=m3zuWITW-yI) - Walkthrough of setting up Sentry logging to debug Next.js applications.
- [Setting up Sentry Logs for Laravel](https://www.youtube.com/watch?v=isyAwH9t68M&t=1s) - Walkthrough of setting up Sentry logging to debug Laravel applications.
- [Fixing issues faster with anomaly detection](https://www.youtube.com/watch?v=-d1phmfnsOU) - Using anomaly detection to catch strange application behaviour before it's an error.

### Improving User Experience

#### Articles / Docs

- [Web Vitals](https://web.dev/articles/vitals) - Introduction to Web Vitals metrics and why they're important.
- [Missing indexes are slowing down your application](https://blog.sentry.io/missing-indexes-are-slowing-down-your-database-heres-how-to-find-and-fix/) - How to find / fix missing indices in JavaScript applications. Using Sentry to find missing indices and to verify fixes.
- [Your poor LCP score might be a backend issue](https://blog.sentry.io/your-bad-lcp-score-might-be-a-backend-issue/) - Slow rendering on your website might be caused by backend issues.
- [Core KPIs for LLM Performance](https://blog.sentry.io/core-kpis-llm-performance-how-to-track-metrics/) - What should you monitor in your applications that talk to LLMs?

#### Videos

- [Fixing Web Vitals problems with AI](https://www.youtube.com/watch?v=CAcgTvB1aXs) - Using Sentry's AI tool Seer to root cause and fix user experience problems.
  - [Seer *can* fix web vitals] - Follow up showing the updated [webvitals.com](https://webvitals.com) site and the actual application of a fix from Seer.

#### Tools

- [webvitals.com](https://webvitals.com/) - Interactive tool that demonstrates and explains each Web Vital.

## Sentry using Sentry

Examples of how we've used Sentry to find and fix problems with Sentry :infinity:.

- [How we decreased P99s on our backend API requests by 3 seconds](https://blog.sentry.io/how-we-decreased-p99s-on-our-backend-api-requests-by-3-seconds/) - Using tracing, profiling, and Insights dashboards Sentry's API P99 performance.

<!-- END CONTENT -->

## Contributing

[Contributions of any kind welcome, just follow the guidelines](contributing.md)!

### Contributors

[Thanks goes to these contributors](https://github.com/bcoe/awesome-sentry/graphs/contributors)!

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

- [Logs are Generally Available](https://blog.sentry.io/logs-generally-available/) - Launch announcment for logs. Includes examples for getting started.
- [How Sentry could stop npm from breaking the Internet](https://blog.sentry.io/how-sentry-could-stop-npm-from-breaking-the-internet/) - Using tracing and alerts to catch traffic anomalies before they break an application.
- [Configuring alerts from dashboards in Sentry](https://blog.sentry.io/use-sentry-insights-trigger-alerts-debug-issues/) - Creating alerts from the widgets shown on Sentry [Inights](https://docs.sentry.io/product/insights/) and [Dashboards](https://docs.sentry.io/product/dashboards/custom-dashboards/).

#### Videos

- [Setting up Sentry Logs for Next.js](https://www.youtube.com/watch?v=m3zuWITW-yI) - Walkthrough of setting up Sentry logging to debug Next.js applications.
- [Setting up Sentry Logs for Laravel](https://www.youtube.com/watch?v=isyAwH9t68M&t=1s) - Walkthrough of setting up Sentry logging to debug Laravel applications.
- [Improving Browser Tracing Step by Step](https://www.youtube.com/watch?v=iUxyRV99AwY) - A video presenting the newest Browser Tracing features in Sentry's SDK as of Sep 29, 2025 - Explicitly ending the pageload spans, Accessing spans outside of callbacks, Sentry automatically handling redirects, Ignoring specific spans, Adding timing attributes to resource spans, Pushing CLS and LCP as standalone Web Vital spans.

### Improving User Experience

#### Articles / Docs

- [Web Vitals](https://web.dev/articles/vitals) - Introduction to Web Vitals metrics and why they're important.
- [Missing indexes are slowing down your application](https://blog.sentry.io/missing-indexes-are-slowing-down-your-database-heres-how-to-find-and-fix/) - How to find / fix missing indices in JavaScript applications. Using Sentry to find missing indices and to verify fixes.
- [Your poor LCP score might be a backend issue](https://blog.sentry.io/your-bad-lcp-score-might-be-a-backend-issue/) - Slow rendering on your website might be caused by backend issues.
- [Core KPIs for LLM Performance](https://blog.sentry.io/core-kpis-llm-performance-how-to-track-metrics/) - What should you monitor in your applications that talk to LLMs?

#### Videos

- [Fixing Web Vitals problems with AI](https://www.youtube.com/watch?v=CAcgTvB1aXs) - Using Sentry's AI tool Seer to root cause and fix user experience problems.

#### Tools

- [webvitals.com](https://webvitals.com/) - Interactive tool that demonstrates and explains each Web Vital.

<!-- END CONTENT -->

## Contributing

[Contributions of any kind welcome, just follow the guidelines](contributing.md)!

### Contributors

[Thanks goes to these contributors](https://github.com/bcoe/awesome-sentry/graphs/contributors)!

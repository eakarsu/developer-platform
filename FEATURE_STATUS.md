# Feature status — Developer, automation & API tools

| Capability | Status |
| --- | --- |
| Native sidebar and canonical feature registry | Built; 386 pages |
| Shared records, validation, relationships, persistence | Implemented in shared runtime |
| Clickable table rows with centered details popup | Implemented; Edit, Delete, Cancel, keyboard access and mobile layout |
| Domain field forms and source traceability | Imported from static source definitions; historical routes are labeled in mapping |
| CSV exports, attachments, audit and report totals | Implemented |
| At least 15 fictional rows per editable feature | Seeded by startup; measured in reports/seed-verification.json |
| AI question-and-answer workspace | Replaces AI feature tables; questions, context fields, formatted answers, follow-ups and saved history; live provider configuration required |
| Source calculation adapters | Available for explicitly registered calculation variants only |
| Source business-rule and state-machine parity | Incomplete beyond registered adapters and native records; verify each source journey |
| Original account/business data migration | Not performed; source data preserved |
| Provider integrations and external delivery | Not connected; request preparation only |
| Hosted authentication, independent-review roles and tenant isolation | Not migrated; local single-user boundary |

A successful build or populated table is not evidence of full source workflow parity. The source-to-feature map records every extracted definition and route, with explicit exclusions and migration warnings. Test/build reports distinguish checked behavior from remaining work.

| Canonical feature | Native mode | Source entries | Calculators | Status |
| --- | --- | ---: | ---: | --- |
| Clients & customers | records | 1 | 0 | Native records/view |
| Work items & projects | records | 1 | 0 | Native records/view |
| Contacts & parties | records | 3 | 0 | Native records/view |
| Tasks | records | 0 | 0 | Native records/view |
| Calendar | records | 0 | 0 | Native records/view |
| Deadlines & reminders | records | 1 | 0 | Native records/view |
| Notes | records | 2 | 0 | AI question-and-answer workspace; records available as context |
| Documents | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Templates | records | 3 | 0 | AI question-and-answer workspace; records available as context |
| Invoices & billing | records | 0 | 0 | Native records/view |
| Time tracking | records | 0 | 0 | Native records/view |
| Messages & communications | records | 4 | 0 | Native records/view |
| Reports & analytics | report | 4 | 0 | Native records/view |
| Activity & audit trail | audit | 4 | 0 | Native records/view |
| Provider connections | integration | 2 | 0 | Provider request records only |
| Headings Hierarchy Validator | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Form Accessibility Auditor | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Remediation Priority Ranker | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Link Text Quality Checker | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Media Accessibility Checker | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Semantic HTML Converter | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Accessibility Readability Score | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Accessibility Monitoring Dashboard | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Accessible Color Palette Generator | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI Remediation Assistant | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| VPAT Generator | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Site Audits | records | 1 | 0 | Native records/view |
| WCAG Compliance | records | 1 | 0 | Native records/view |
| Issues Tracker | records | 1 | 0 | Native records/view |
| AI Fix Suggestions | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| ADA Compliance Reports | records | 1 | 0 | Native records/view |
| Color Contrast Analyzer | records | 2 | 0 | AI question-and-answer workspace; records available as context |
| Screen Reader Testing | records | 1 | 0 | Native records/view |
| Keyboard Navigation | records | 1 | 0 | Native records/view |
| ARIA Validator | records | 1 | 0 | Native records/view |
| Alt Text Generator | records | 2 | 0 | AI question-and-answer workspace; records available as context |
| Accessibility Scores | records | 1 | 0 | Native records/view |
| Compliance Certificates | records | 1 | 0 | Native records/view |
| Focus order risk | records | 1 | 0 | Native records/view |
| Website Accessibility Scanner | records | 1 | 0 | Native records/view |
| WCAG Compliance Checker | records | 1 | 0 | Native records/view |
| Screen Reader Optimizer | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Keyboard Navigation Auditor | records | 1 | 0 | Native records/view |
| ARIA Label Generator | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Accessibility Report Generator | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Remediation Plan Creator | records | 1 | 0 | Native records/view |
| Legal Compliance Assessor | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| PDF Accessibility Checker | records | 1 | 0 | Native records/view |
| Form Accessibility Analyzer | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Video Caption Generator | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Readability Analyzer | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Accessibility Policy Generator | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Batch jobs | records | 1 | 0 | Native records/view |
| Comparisons | records | 1 | 0 | Native records/view |
| Remediation code | records | 1 | 0 | Native records/view |
| Legal risk | records | 1 | 0 | Native records/view |
| Invitations | records | 1 | 0 | Native records/view |
| Ci webhook | integration | 1 | 0 | Provider request records only |
| Skills | records | 1 | 0 | Native records/view |
| Portfolio | records | 1 | 0 | Native records/view |
| Profile | records | 1 | 0 | Native records/view |
| Wcag kb | records | 1 | 0 | Native records/view |
| Validate fix | records | 1 | 0 | Native records/view |
| Bulk remediate | records | 1 | 0 | Native records/view |
| Ab test fix | records | 1 | 0 | Native records/view |
| Remediation evidence pack | records | 1 | 0 | Native records/view |
| Counts | records | 1 | 0 | Native records/view |
| Appointments | records | 2 | 0 | Native records/view |
| Categories | records | 1 | 0 | Native records/view |
| NLP Logs | records | 1 | 0 | Native records/view |
| Voice Commands | records | 1 | 0 | Native records/view |
| Buffer Optimizer | records | 2 | 0 | AI question-and-answer workspace; records available as context |
| No-Show Predictor | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Reschedule Suggester | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Resource Allocator | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Conflict Resolver | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI Extras | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Run | records | 1 | 0 | Native records/view |
| Waitlist fill optimizer | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Jobs | records | 1 | 0 | Native records/view |
| Data | records | 1 | 0 | Native records/view |
| Logs | records | 3 | 0 | Native records/view |
| Agents | records | 3 | 0 | Native records/view |
| Competitive agents | records | 1 | 0 | Native records/view |
| Schedule optimizer | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Quality validator | records | 1 | 0 | Native records/view |
| Selector recommender | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Anomaly alerts | records | 1 | 0 | Native records/view |
| Job queue | records | 1 | 0 | Native records/view |
| Competitive agents manager | records | 1 | 0 | Native records/view |
| Export | records | 1 | 0 | Native records/view |
| Backlog tools | records | 1 | 0 | Native records/view |
| Desktop control | records | 1 | 0 | Native records/view |
| Screen capture | records | 1 | 0 | Native records/view |
| Click planner | records | 1 | 0 | Native records/view |
| Form filler | records | 1 | 0 | Native records/view |
| Multi tab | records | 1 | 0 | Native records/view |
| Session recording | records | 1 | 0 | Native records/view |
| Human handoff | records | 1 | 0 | Native records/view |
| Policy guard | records | 1 | 0 | Native records/view |
| Research Assistant | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Auto-Fill Forms | records | 1 | 0 | Native records/view |
| Content Summarizer | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Tab Manager | records | 1 | 0 | Native records/view |
| Bookmark Organizer | records | 1 | 0 | Native records/view |
| Password Manager | records | 1 | 0 | Native records/view |
| Ad Blocker Rules | records | 1 | 0 | Native records/view |
| Reading List | records | 1 | 0 | Native records/view |
| Translation Helper | records | 1 | 0 | Native records/view |
| Screenshot Annotator | records | 1 | 0 | Native records/view |
| Email Templates | records | 1 | 0 | Native records/view |
| Price Tracker | records | 1 | 0 | Native records/view |
| Grammar Checker | records | 1 | 0 | Native records/view |
| Citation Generator | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Dark Mode Manager | records | 1 | 0 | Native records/view |
| Todo List | records | 1 | 0 | Native records/view |
| Pomodoro Timer | records | 1 | 0 | Native records/view |
| Habit Tracker | records | 1 | 0 | Native records/view |
| Expense Tracker | records | 1 | 0 | Native records/view |
| Clipboard History | records | 1 | 0 | Native records/view |
| Site Blocker | records | 1 | 0 | Native records/view |
| Quick Links | records | 1 | 0 | Native records/view |
| Session Saver | records | 1 | 0 | Native records/view |
| Countdown Timer | records | 1 | 0 | Native records/view |
| Color Palette | records | 1 | 0 | Native records/view |
| Snippet Manager | records | 2 | 0 | Native records/view |
| RSS Feed Reader | records | 1 | 0 | Native records/view |
| Workout Tracker | records | 1 | 0 | Native records/view |
| Email Security Scanner | records | 1 | 0 | Native records/view |
| Invoice OCR Analyzer | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Meeting Summarizer | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Code Explainer | records | 2 | 0 | Native records/view |
| Resume Enhancer | records | 1 | 0 | Native records/view |
| Contract Reviewer | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Health Claim Validator | records | 1 | 0 | Native records/view |
| Competitor Monitor | records | 1 | 0 | Native records/view |
| Permission Risk Review | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Chatbots | records | 1 | 0 | Native records/view |
| Flow Builder | records | 1 | 0 | Native records/view |
| AI Chat | records | 3 | 0 | AI question-and-answer workspace; records available as context |
| Flow Visualizer | records | 1 | 0 | Native records/view |
| Context Variables | records | 1 | 0 | Native records/view |
| KB Relevance | records | 1 | 0 | Native records/view |
| AI Results History | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Mining & Sentiment | records | 1 | 0 | Native records/view |
| Handoff Policy | records | 1 | 0 | Native records/view |
| Knowledge Base | records | 1 | 0 | Native records/view |
| Responses | records | 1 | 0 | Native records/view |
| Intents | records | 1 | 0 | Native records/view |
| Entities | records | 1 | 0 | Native records/view |
| Training Data | records | 2 | 0 | Native records/view |
| Quick Replies | records | 1 | 0 | Native records/view |
| Media Library | records | 1 | 0 | Native records/view |
| Tags | records | 1 | 0 | Native records/view |
| Conversations | records | 2 | 0 | Native records/view |
| Channels | records | 1 | 0 | Native records/view |
| Broadcasts | records | 1 | 0 | Native records/view |
| Webhooks | integration | 4 | 0 | Provider request records only |
| Forms | records | 1 | 0 | Native records/view |
| Deployments | records | 1 | 0 | Native records/view |
| Users | records | 2 | 0 | Native records/view |
| API Keys | records | 1 | 0 | Native records/view |
| Plugins | records | 1 | 0 | Native records/view |
| Executions | records | 2 | 0 | Native records/view |
| Notebooks | records | 1 | 0 | Native records/view |
| Environments | records | 1 | 0 | Native records/view |
| Packages | records | 1 | 0 | Native records/view |
| Visualizations | records | 1 | 0 | Native records/view |
| Datasets | records | 1 | 0 | Native records/view |
| Code Reviews | records | 2 | 0 | AI question-and-answer workspace; records available as context |
| Secrets | records | 1 | 0 | Native records/view |
| Collaborators | records | 1 | 0 | Native records/view |
| Sandbox Execute | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Review Diff | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Performance Profiler | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Clone Detector | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Docs Refresher | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Collaborative Review | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Execute | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Review | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Generate | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Debug | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Explain | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Refactor | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Analyze Data | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Convert | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Sandbox risk | records | 1 | 0 | Native records/view |
| Code Analysis | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Code Comments | records | 1 | 0 | Native records/view |
| Refactoring | records | 1 | 0 | Native records/view |
| Documentation | records | 1 | 0 | Native records/view |
| API Docs | records | 1 | 0 | Native records/view |
| README Generator | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Security Scan | records | 1 | 0 | Native records/view |
| Performance | records | 1 | 0 | Native records/view |
| Test Generation | records | 1 | 0 | Native records/view |
| Bug Predictor | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Tech Debt | records | 1 | 0 | Native records/view |
| Architecture | records | 1 | 0 | Native records/view |
| Dependencies | records | 1 | 0 | Native records/view |
| Deployment | records | 1 | 0 | Native records/view |
| GitHub | records | 1 | 0 | Native records/view |
| Teams | records | 1 | 0 | Native records/view |
| Assignments | records | 1 | 0 | Native records/view |
| Quality Trends | records | 1 | 0 | Native records/view |
| Security Posture | records | 1 | 0 | Native records/view |
| Consensus Engine | records | 1 | 0 | Native records/view |
| Remediation Bot | records | 1 | 0 | Native records/view |
| Coding Standards | records | 1 | 0 | Native records/view |
| Cross-Repo Deps | records | 1 | 0 | Native records/view |
| Review SLA | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| API Breaking Changes | records | 1 | 0 | Native records/view |
| Verify email | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Query Analyzer | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Index Advisor | records | 1 | 0 | Native records/view |
| Health Report | records | 1 | 0 | Native records/view |
| Capacity Forecast | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Lock Analysis | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Workload Analysis | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Connection Pool Optimizer | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Denormalization Advisor | records | 1 | 0 | Native records/view |
| Replication Lag Monitor | records | 1 | 0 | Native records/view |
| Storage Cost Analyzer | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Predict Backup Failure | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Metric Anomaly Detection | records | 1 | 0 | Native records/view |
| Security Posture Review | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Databases | records | 1 | 0 | Native records/view |
| Queries | records | 1 | 0 | Native records/view |
| Indexes | records | 1 | 0 | Native records/view |
| Backups | records | 1 | 0 | Native records/view |
| Backup schedules | records | 1 | 0 | Native records/view |
| Agents new | records | 1 | 0 | Native records/view |
| Failover drill | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Query optimization agent | records | 1 | 0 | Native records/view |
| Predictive performance modeling | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Anomaly detection for database health | records | 1 | 0 | Native records/view |
| Schema evolution recommendations | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Cost optimization | records | 1 | 0 | Native records/view |
| Missing optimize query analyze slow queries recommend indexe | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| No connection pooling or driver management module | records | 1 | 0 | Native records/view |
| No real time monitoring alerting beyond stubs | records | 1 | 0 | Native records/view |
| Limited cloud db integrations no aws rds azure sql gcp cloud | integration | 1 | 0 | Provider request records only |
| No replication failover management | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| No encryption or security audit module | records | 1 | 0 | Native records/view |
| No notification system | records | 1 | 0 | Native records/view |
| Scaling Advisor | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Security Risk | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Failure Prediction | records | 2 | 0 | AI question-and-answer workspace; records available as context |
| Incident Prediction | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Cost Forecast | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Anomaly Detection | records | 2 | 0 | AI question-and-answer workspace; records available as context |
| Predictive infrastructure scaling | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Cost optimization automation | records | 1 | 0 | Native records/view |
| Security posture automation | records | 1 | 0 | Native records/view |
| Missing optimize infrastructure predict performance detect a | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Limited cloud platform integration no aws gcp azure sdk adap | integration | 1 | 0 | Provider request records only |
| Limited real time alerting and incident response automation | records | 1 | 0 | Native records/view |
| No sla tracking module | records | 1 | 0 | Native records/view |
| No change management workflow | records | 1 | 0 | Native records/view |
| No sms notifications | records | 1 | 0 | Native records/view |
| No calendar integration | integration | 1 | 0 | Provider request records only |
| Docs | records | 1 | 0 | Native records/view |
| AI Jobs | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Doc Consistency | records | 1 | 0 | Native records/view |
| Recordings | records | 1 | 0 | Native records/view |
| Billing Queue | records | 1 | 0 | Native records/view |
| Applicants | records | 1 | 0 | Native records/view |
| Applications | records | 1 | 0 | Native records/view |
| Benefits | records | 1 | 0 | Native records/view |
| Eligibility | records | 1 | 0 | Native records/view |
| Assistant | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Benefits calculator | records | 1 | 0 | Native records/view |
| Benefits navigator | records | 1 | 0 | Native records/view |
| Income verification guide | records | 1 | 0 | Native records/view |
| Appeal preparation | records | 1 | 0 | Native records/view |
| Service locator | records | 1 | 0 | Native records/view |
| Income change advisor | records | 2 | 0 | Native records/view |
| comprehensive benefits discovery | records | 1 | 0 | Native records/view |
| language accessibility | records | 1 | 0 | Native records/view |
| case worker escalation intelligence | records | 1 | 0 | Native records/view |
| benefits retention optimization | records | 1 | 0 | Native records/view |
| appeal coaching | records | 1 | 0 | Native records/view |
| benefitsnavigator multiprogram eligibilit | records | 1 | 0 | Native records/view |
| incomeverificationguide doc checklist ai | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| appealpreparation denialtoappeal strategy | records | 1 | 0 | Native records/view |
| servicelocator local resources | records | 1 | 0 | Native records/view |
| multilingual translation ai | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| case worker assignmentcommunication workf | records | 1 | 0 | Native records/view |
| benefits expiration renewal reminder auto | records | 1 | 0 | Native records/view |
| appeal lifecycle tracking | records | 1 | 0 | Native records/view |
| smsvoice gateway integration project name | integration | 1 | 0 | Provider request records only |
| sso with state benefit systems | records | 1 | 0 | Native records/view |
| public partner api | records | 1 | 0 | Native records/view |
| GitHub Webhook (test-impact) | integration | 1 | 0 | Provider request records only |
| GitLab Webhook (test-impact) | integration | 1 | 0 | Provider request records only |
| GitHub Actions Trigger | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Jenkins Trigger | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Flaky detect | records | 1 | 0 | Native records/view |
| Dead code | records | 1 | 0 | Native records/view |
| Performance regression | records | 1 | 0 | Native records/view |
| Ci integrations | integration | 1 | 0 | Provider request records only |
| Coverage visualization | records | 1 | 0 | Native records/view |
| ai test generator analyzing code and producing assertions | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| mutation testing with generated mutant variants to assess | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| flaky test detector identifying non deterministic failures | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| dead code detector flagging untested code paths | records | 1 | 0 | Native records/view |
| performance regression detection identifying test execution degradation | records | 1 | 0 | Native records/view |
| vcs webhook integration auto running suites on pr open | integration | 1 | 0 | Provider request records only |
| critical gap no ai driven test generation despite domain | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| mutation testing ai analysis | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| flaky test detection ml model | records | 1 | 0 | Native records/view |
| code coverage gap recommender | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| limited vcs integration git auto trigger not visible | integration | 1 | 0 | Provider request records only |
| limited ci cd platform integration beyond stub modules | integration | 1 | 0 | Provider request records only |
| code coverage visualization ui route | records | 1 | 0 | Native records/view |
| test flakiness detection feature | records | 1 | 0 | Native records/view |
| notifications limited to one reference not a full | records | 1 | 0 | Native records/view |
| Business | records | 1 | 0 | Native records/view |
| Subscription | records | 1 | 0 | Native records/view |
| Usage billing | records | 1 | 0 | Native records/view |
| Agent | records | 1 | 0 | Native records/view |
| Voice | records | 1 | 0 | Native records/view |
| Script | records | 1 | 0 | Native records/view |
| Response library | records | 1 | 0 | Native records/view |
| Call flow | records | 1 | 0 | Native records/view |
| Call flow node | records | 1 | 0 | Native records/view |
| Phone number | records | 1 | 0 | Native records/view |
| Call routing rule | records | 1 | 0 | Native records/view |
| Call | records | 1 | 0 | Native records/view |
| Call message | records | 1 | 0 | Native records/view |
| Call event | records | 1 | 0 | Native records/view |
| Integration | integration | 1 | 0 | Provider request records only |
| Webhook | integration | 1 | 0 | Provider request records only |
| Webhook log | integration | 1 | 0 | Provider request records only |
| Daily analytics | records | 1 | 0 | Native records/view |
| Conversation feedback | records | 1 | 0 | Native records/view |
| System setting | records | 1 | 0 | Native records/view |
| Speech enhancement | records | 1 | 0 | Native records/view |
| Accent adaptation | records | 1 | 0 | Native records/view |
| Intent classification | records | 1 | 0 | Native records/view |
| Emotion detection | records | 1 | 0 | Native records/view |
| Multi language support | records | 1 | 0 | Native records/view |
| Language translation | records | 1 | 0 | Native records/view |
| Hearing test | records | 1 | 0 | Native records/view |
| Campaign | records | 1 | 0 | Native records/view |
| Campaign contact | records | 1 | 0 | Native records/view |
| Agent knowledge | records | 1 | 0 | Native records/view |
| Result | records | 1 | 0 | Native records/view |
| Email verification token | records | 1 | 0 | Native records/view |
| Vs enrollment | records | 1 | 0 | Native records/view |
| Vs enrollment sample | records | 1 | 0 | Native records/view |
| Vs consent event | records | 1 | 0 | Native records/view |
| Vs tts style | records | 1 | 0 | Native records/view |
| Vs avatar render job | records | 1 | 0 | Native records/view |
| Vs lipsync job | records | 1 | 0 | Native records/view |
| Vs dubbing job | records | 1 | 0 | Native records/view |
| Vs provenance record | records | 1 | 0 | Native records/view |
| Media asset | records | 1 | 0 | Native records/view |
| Media upload session | records | 1 | 0 | Native records/view |
| Media timeline | records | 1 | 0 | Native records/view |
| Media timeline version | records | 1 | 0 | Native records/view |
| Media preview approval | records | 1 | 0 | Native records/view |
| Media caption track | records | 1 | 0 | Native records/view |
| Media export preset | records | 1 | 0 | Native records/view |
| Media pipeline job | records | 1 | 0 | Native records/view |
| Media job attempt | records | 1 | 0 | Native records/view |
| Media provider | records | 1 | 0 | Native records/view |
| Media provider event | records | 1 | 0 | Native records/view |
| Cursor work | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Integration workflow plans | integration | 1 | 0 | Provider request records only |
| Integration run requests | integration | 1 | 0 | Provider request records only |
| Livocloud work | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Livomlivo work | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Servers | records | 1 | 0 | Native records/view |
| Tools | records | 1 | 0 | Native records/view |
| Prompts | records | 1 | 0 | Native records/view |
| Resources | records | 1 | 0 | Native records/view |
| Workflows | records | 1 | 0 | Native records/view |
| Knowledge | records | 1 | 0 | Native records/view |
| Models | records | 1 | 0 | Native records/view |
| Knowledge rag | records | 1 | 0 | Native records/view |
| Cost summary | records | 1 | 0 | Native records/view |
| Agent chain | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Multi model route | records | 1 | 0 | Native records/view |
| Tool blast radius | records | 1 | 0 | Native records/view |
| Solrproject work | records | 1 | 0 | AI question-and-answer workspace; records available as context |

Row popup verification passed: dashboard and feature rows, keyboard/focus, editing and persistence, delete confirmation/cancellation, centered mobile layout and full-record navigation. See `reports/row-popup-verification.json`.

## Verified local build

Build, API, browser and actual `start.sh` checks passed. All 386 feature pages were visited in the browser; 384 editable tables contain at least 15 fictional rows each. CRUD persistence and mobile layout were checked. Evidence is in `reports/verification.json`, `reports/browser-verification.json` and `reports/startup-verification.json`.

These checks cover the native local workspace. Full source-specific business rules, authentication and live provider operations remain incomplete as described above. Test servers were stopped after verification.

## AI workspace verification

All 101 AI feature routes were checked in the browser and show questions and formatted answers instead of the original record table. Existing records are retained as optional context. Questions, follow-ups, saved history across restart, Markdown tables, safe rendering, downloads, provider-failure recovery and mobile layout passed with a mocked provider. See `reports/ai-workspace-verification.json`.

Live answers require `OPENROUTER_API_KEY` and `OPENROUTER_MODEL` in this app's `.env` and an app restart. No live provider call was made during verification. Conversational answers do not execute unmigrated specialist engines, read record attachments automatically or perform external actions.


## AI word limits

Questions support up to 5,000 words with a live counter and server validation. AI responses and record drafts have a 16,000-token output budget and a default 180-second timeout to support answers up to 5,000 words; actual length depends on the request and model. Answers show their word count, and long questions can be expanded. Browser checks passed for 5,000-word questions and answers, saved history, full downloads, mobile layout and rejection of 5,001-word questions. See `reports/word-limit-verification.json` (mock-provider boundary checks).

## Merged AI assistants

101 original AI entries are now grouped into **7 assistants** in the sidebar. Choose up to 8 related capabilities and add up to 10 questions for one provider request and one saved response. Shared context is sent once; repeated questions are removed after trimming and whitespace/case normalization. The total question limit is 5,000 words and the combined answer target is up to 5,000 words.

Original feature URLs still open the appropriate assistant with that capability selected. Existing records and answers stay in place; the assistant history includes answers saved under its member features. Non-AI record tables retain their popup actions. This merges the assistant workflow and navigation; it does not implement previously missing external integrations or specialist engines. See `reports/assistant-merge-map.json` and `reports/assistant-merge-verification.json`.

## Floating Ask AI assistant

Implemented across this workspace. The bottom-right **Ask AI** button opens a persistent chat panel on every page. Use **Ask AI about item** in a row popup or record view, or **Use current item** inside the panel, to supply the selected record.

- Questions about the page, any explicitly chosen app record, and general topics.
- Formatted answers, comparison tables, follow-ups, copy and Markdown download.
- Conversation and question drafts stay intact during in-app navigation. Saved answers persist in SQLite; the last conversation restores in the same browser tab after reload. The latest 50 saved answers are listed; restoring one displays up to 20 turns. Up to four preceding turns are sent as AI context.
- Up to 5,000 input words and a response budget of up to 5,000 words. Output length remains dependent on the provider and the question.
- Page title and description are supplied automatically; record fields and notes are sent only for a selected item. Attachments and unselected records are not included. **New chat** starts without earlier conversation context.
- Existing AI provider configuration, timeout, rate limit and safe response renderer are reused. The assistant answers and drafts; it does not execute record changes or external actions.

Validation: shared backend tests, all 64 app builds/API checks, and all 64 browser checks passed with an injected test provider. Browser checks cover item context, navigation, saved history/reload, follow-ups, new-chat isolation, error recovery, word limits, keyboard controls, mobile bounds, safe Markdown rendering and attachment refresh. See [verification](reports/floating-ai-verification.json).

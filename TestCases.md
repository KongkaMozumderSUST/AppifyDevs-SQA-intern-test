| Test ID | Test Title | App/Website | Steps | Expected Result | Test Types | Severity |
|--------|------------|-------------|-------|-----------------|------------|----------|
| T001 | SignUp EchoGPT website with Email, Google, Twitter, Github | EchoGPT Website | 1. Click SignUp with Email/Google/Twitter/Github | User signs up & redirected to homepage | Functional, Exploratory, Positive | Critical |
| T002 | SignIn EchoGPT website with Email, Google, Twitter, Github | EchoGPT Website | 1. Click SignIn with Email/Google/Twitter/Github | User signs in with proper credentials | Functional, Exploratory, Positive | Critical |
| T003 | Verify EchoGPT chat message | EchoGPT Website + EchoChat App | 1. Open website 2. New Chat and type message 3. Send 4. Repeat | Users can send messages & receive responses | Functional, Positive | Critical |
| T004 | Verify AI Image Generator | EchoGPT Website | 1. Load page 2. Click Image 3. Write prompt 4. Send | A new AI image is generated | Functional, Exploratory, Positive | High |
| T005 | Check history | EchoGPT Website + EchoChat App | 1. Login 2. Check history on website & app | History is shown in both | Functional, Exploratory, Positive | Medium |
| T006 | Change Models | EchoGPT Website + EchoChat App | 1. Change models 2. Send messages | Everything works properly | Functional, Positive | High |
| T007 | Check responsiveness across devices | EchoGPT Website + AppTestingService Website | 1. Change desktop resolutions | Page responsiveness works | UI | Medium |
| T008 | Check cross site scripting (XSS) | Websites | 1. Enter `<script>alert('XSS')</script>` in fields 2. Send | Shown as text; no script executes | Security | High |
| T009 | Check AI Job Analysis | EchoGPT Website | 1. Paste job description 2. Analyze | Analyzed output shown | Functional, Exploratory, Positive | High |
| T010 | Check Payment Option | EchoGPT Website + EchoChat App | 1. Click Subscription 2. Select plan 3. Pay | Payment works & deducts correct amount | Functional | High |
| T011 | Check design consistency | Website + App | 1. Check colors, buttons, margins, footer, typos | Consistent design & working buttons | UI/UX | Medium |
| T012 | Extremely long message | EchoGPT Website + EchoChat App | 1. Paste >20k chars 2. Send | Message accepted/rejected clearly; UI stays responsive | Edge | Medium |
| T013 | Color contrast | Website + App | 1. Inspect CTAs & small text | WCAG AA contrast ≥ 4.5:1 | Accessibility | Medium |
| T014 | Screen reader reading order |  Website + App | 1. Enable TalkBack or Screen reader 2. Navigate | Elements read in correct order | Accessibility, Exploratory | High |
| T015 | Keyboard accessibility | EchoGPT Website + AppTestingService Website | 1. Use Tab/Shift+Tab | All interactive elements reachable | Accessibility | High |
| T016 | Crash Recovery | EchoChat App + AppTestingService App | 1. Force-stop 2. Relaunch | App restarts; no corruption | Stability | Major |
| T017 | Load Test for 100–1000 users | EchoGPT Website | 1. Use JMeter | System should not crash | Performance, Load | Critical |
| T018 | Stress Test for 10,000 users | EchoGPT Website | 1. JMeter 10k threads | System handles heavy stress | Performance, Stress | Critical |
| T019 | Admin page exposure test | EchoGPT Website | 1. Open /admin | Admin page should not be exposed | Security | Critical |
| T020 | 6-hour continuous chat session | EchoGPT Website + EchoChat App  | 1. Send messages every 30–60 secs for 6h | No crash, stable performance | Stability | Critical |
| T021 | Turn internet ON/OFF during chat | EchoGPT Website + EchoChat App | 1. Chat 2. Turn WiFi off/on | Auto-reconnect; no crash or data loss | Stability | Critical |
| T022 | Long conversation scrolling | EchoGPT Website + EchoChat App  | 1. Create 100+ messages 2. Scroll | Smooth, no lag/freeze | Stability | Major |
| T023 | Browser compatibility test | EchoGPT Website + AppTestingService Website | Chrome, Firefox, Edge, Mobile browser | No browser-specific issues | Stability | Critical |
| T024 | Login with wrong email | Website + App | 1. Enter wrong email | Login should fail | Exploratory, Negative | Critical |
| T025 | Submit empty messages | EchoGPT Website + EchoChat App  | 1. Try to send empty text | Send disabled; error shown | Negative | Medium |
| T026 | Dark mode visibility | EchoGPT Website + EchoChat App | 1. Toggle dark mode | Proper contrast & visibility | UI | Low |
| T027 | Image Like Count | EchoGPT Website | 1. Click Image → Like | Like count updates | Exploratory | Low |
| T028 | Logout | Website + App | 1. Click logout | Session cleared | Functional | Low |
| T029 | SQL/meta characters in input | Website + App | 1. Submit `' OR '1'='1` | Sanitized; no server failure | Edge | High |
| T030 | Install apps | EchoChat App + AppTestingService Apps | 1. Install from Playstore | Installs & opens without crash | Functional | Critical |
| T031 | Create account | AppTestingService Website + App | 1. Valid email, name, password | Account created successfully | Functional, Exploratory, Positive | Critical |
| T032 | Create account with non-existent email | AppTestingService Website + App | 1. Enter non-existent email | Account not created | Exploratory, Negative | Critical |
| T033 | Login with valid credentials | AppTestingService Website + App | 1. Enter valid credentials | Successful login | Positive, Exploratory, Functional | Critical |
| T034 | Login with invalid credentials | AppTestingService Website + App | 1. Enter invalid credentials | Login fails | Negative, Exploratory | Critical |
| T035 | Submit App | AppTestingService Website + App | 1. Enter details & payment | App submission successful | Positive | Major |
| T036 | Check Discord Link | Both Websites + Both Apps | 1. Click Discord link | Link works properly | Positive | Low |
| T037 | Check App list | AppTestingService Website | 1. Open App list | List shown properly | Exploratory | Medium |
| T038 | Load Test AppTestingService | AppTestingService Website | 1. JMeter 1000 users | Everything works fine | Performance | Major |
| T039 | Backup , Reinstall, Restore | Both Apps | 1. Reinstall 2. Login | Data restored from server | Functional | Medium |
| T040 | Continuous 3-hour usage (Soak test) | Both Apps | 1. Use app for 3 hrs | No crash/freeze/memory leak | Stability | High |
| T041 | Check Support Ticket | AppTestingService App | 1. Open App 2. Click Profile 3. Click Support Ticket 4. Try to send empty message | Message should not be sent | Functional | Medium |
| T042 | Check Email Us | Both Website and Both App | 1. Open websites/App 2. Click Email Us | Mail should open | Functional, Exploratory| Medium |

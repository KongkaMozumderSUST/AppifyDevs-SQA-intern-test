| Section | Details |
|---------|---------|
| Project | AppTestingService & EchoGPT — Apps + Website |
| Introduction & Objectives | Verify apps & websites for core functionality, UI/UX, stability, security basics, accessibility, and exploratory coverage |
| Test Items | Android App 1: App Testing Service (com.apptestingservice)<br>Android App 2: EchoGPT Chat App (com.echogpt.chatapp)<br>Website 1: https://echogpt.live/<br>Website 2: https://apptestingservice.com/ |
| Scope | Install & test two Android apps and two websites. Features to be tested:<br>- Installation/Deployment<br>- User Interface (UI)<br>- Core Functionality<br>- Basic Security<br>- Stability<br>- Accessibility |
| Devices & OS | Android 12 (OnePlus Nord), Windows Desktop, Chrome Latest (Desktop & Mobile) |
| Environments | Staging (if available) and Production (Play Store + live websites) |
| Test Networks | Wi-Fi, 3G/4G, Airplane mode |
| Types of Tests | Functional, UI, Stability/Crash, Accessibility, Security (basic), Exploratory, Performance |
| Resources & Tools | adb/logcat, Chrome DevTools console, Accessibility Scanner/TalkBack, Figma/Pixel ruler (UI), Postman for API checks, JMeter |
| Exit Criteria | All critical/blocker bugs resolved; high-severity issues mitigated or documented; coverage of 25+ test cases executed |
| Risks & Assumptions | No direct access to internal API docs; tests conducted on public Play Store builds and public websites |
| Notes | Use test accounts or guest flows; collect logcat and screenshots for failures |
| Deliverables | Test Plan, 25+ Test Cases, Execution Log, Bug Report(s), Exploratory Testing Notes, Short Summary Report (1 page) |

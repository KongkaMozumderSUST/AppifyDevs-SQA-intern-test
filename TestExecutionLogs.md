| Test Cases | Pass/Fail | Environment | Timestamps | Bug Id | Output or Explanation |
|------------|-----------|-------------|------------|--------|------------------------|
| T001 | Fail | Desktop, Chrome Latest, Windows 11,  Acer Aspire A315-24P Laptop, Mobile, Android 12, OnePlus Nord, EchoGPT Website, | 6/12/2025 5:53pm | 001 | SignUp with Twitter not working |
| T002 | Fail | Desktop, Chrome Latest, Windows 11, Acer Aspire A315-24P Laptop,Mobile, Android 12, OnePlus Nord, EchoGPT Website | 6/12/2025 5:58pm | 001 | SignIn with Twitter not working |
| T003 | Fail | Desktop, Chrome Latest, Windows 11, Acer Aspire A315-24P Laptop, Mobile, Android 12, OnePlus Nord,  EchoGPT Website + EchoChat 1.0.5 | 6/12/2025 6:00pm | 002,007 | Message is not sending |
| T004 | Fail | Desktop, Chrome Latest, Windows 11, Acer Aspire A315-24P Laptop, Mobile, Android 12, OnePlus Nord,  EchoGPT Website | 6/12/2025 6:06pm | 003 | AI image is not generating |
| T005 | Pass | Desktop, Chrome Latest, Windows 11,Acer Aspire A315-24P Laptop, Mobile, Android 12, OnePlus Nord,  EchoGPT Website + EchoChat 1.0.5 | 6/12/2025 6:08pm | - | History Syncs |
| T006 | Pass | Desktop, Chrome Latest, Windows 11, Acer Aspire A315-24P Laptop, Mobile, Android 12, OnePlus Nord,  EchoGPT Website + EchoChat 1.0:5 | 6/12/2025 6:15pm | - | Model Changes |
| T007 | Pass | Desktop, Chrome Latest, Windows 11, Acer Aspire A315-24P Laptop, Mobile, Android 12, OnePlus Nord,  EchoGPT Website + AppTestingService Websites  | 6/12/2025 6:18pm | - | Shows responsiveness |
| T008 | Pass | Desktop, Chrome Latest, Windows 11, Acer Aspire A315-24P Laptop, Mobile, Android 12, OnePlus Nord,  EchoGPT Website + AppTestingService Websites  | 6/12/2025 6:23pm | - | Shows no pop up window with XSS |
| T009 | Pass | Desktop, Chrome Latest, Windows 11, Mobile, Android 12, OnePlus Nord,  EchoGPT Website | 6/12/2025 6:33pm | - | Shows no error, analyzes job |
| T011 | Fail | Desktop, Chrome Latest, Windows 11, Acer Aspire A315-24P Laptop, Mobile, Android 12, OnePlus Nord,  EchoGPT Website + EchoChat App + AppTestingService Website + AppTestingService App | 6/12/2025 6:46pm | 009,011 | Typos in AppTestingService (Sumbit + Uplaod) |
| T012 | Fail | Desktop, Chrome Latest, Windows 11, Acer Aspire A315-24P Laptop, Mobile, Android 12, OnePlus Nord,  EchoGPT Website + EchoChat App | 6/12/2025 6:59pm | 002 | Message is not sending |
| T013 | Pass | Desktop, Chrome Latest, Windows 11, Acer Aspire A315-24P Laptop, Mobile, Android 12, OnePlus Nord,  EchoGPT Website + EchoChat App + AppTestingService Website + AppTestingService App | 6/12/2025 8:00pm | - | Shows color contrast |
| T014 | Pass | Desktop, Chrome Latest, Windows 11, Acer Aspire A315-24P Laptop, Mobile, Android 12, OnePlus Nord,  EchoGPT Website + EchoChat App + AppTestingService Website + AppTestingService App | 6/12/2025 8:30pm | - | Elements read in correct order |
| T015 | Fail | Desktop, Chrome Latest, Windows 11,Acer Aspire A315-24P Laptop, EchoGPT Website  | 6/12/2025 8:45pm | 006 | Image, History, AI Job Analysis, Store, etc. are not focusable/clickable with Tab in EchoGPT Website |
| T015 | Pass | Desktop, Chrome Latest, Windows 11, Acer Aspire A315-24P Laptop, AppTestingService Website | 6/12/2025 9:00pm | - | Tab works |
| T016 | Pass | Mobile, Android 12, OnePlus Nord, Both App | 6/12/2025 9:10pm | - | App restarts; no corruption |
| T017 | Pass | Desktop, Chrome Latest, Windows 11, Acer Aspire A315-24P Laptop, EchoGPT website | 6/12/2025 9:30pm | - | No error shown in JMeter |
| T018 | Fail | Desktop, Chrome Latest, Windows 11, Acer Aspire A315-24P Laptop, EchoGPT website | 6/12/2025 10:00pm | - | Shows some error request in JMeter, Http request error |
| T019 | Pass | Desktop, Chrome Latest, Windows 11,  EchoGPT website, Acer Aspire A315-24P Laptop, AppTestingService | 6/12/2025 10:10pm | - | Admin page did not expose |
| T020 | Fail | Desktop, Chrome Latest, Windows 11,Acer Aspire A315-24P Laptop, Mobile, Android 12, OnePlus Nord, EchoGPT website + EchoChat App | 6/12/2025 01:15pm | 002 | Message is not sending |
| T021 | Pass | Desktop, Chrome Latest, Windows 11, Acer Aspire A315-24P Laptop,  OnePlus Nord, Mobile, Android 12 EchoGPT website + EchoChat App | 6/12/2025 01:20pm | - | Auto-reconnect; no crash or data loss |
| T022 | Fail | Desktop, Chrome Latest, Windows 11, Acer Aspire A315-24P Laptop,Mobile, OnePlus Nord, Android 12 EchoGPT website + EchoChat App | 6/12/2025 01:30pm | 002 | Messaging not working |
| T023 | Pass | EchoGPT Website + AppTestingService Website, Chrome, Firefox, Edge, Mobile browser, OnePlus Nord,Acer Aspire A315-24P Laptop, Windows 11, Android 12 | 5/12/2025 6:30pm | - | No issues |
| T024 | Pass | EchoGPT Website + AppTestingService Website+ Both App, Chrome, Firefox, Edge, Mobile browser, OnePlus Nord, Acer Aspire A315-24P Laptop, Windows 11, Android 12 | 5/12/2025 6:47pm | - | Error message is shown |
| T025 | Pass | Desktop, Chrome Latest, Windows 11, Acer Aspire A315-24P Laptop, Mobile, Android 12,OnePlus Nord, EchoGPT website + EchoChat App | 5/12/2025 6:50pm | - | Send disabled; error shown |
| T026 | Pass | Desktop, Chrome Latest, Windows 11, Acer Aspire A315-24P Laptop, Mobile, Android 12, OnePlus Nord, EchoGPT website + EchoChat App | 5/12/2025 7:09pm | - | Proper contrast & visibility |
| T027 | Fail | Desktop, Chrome Latest, Windows 11, Acer Aspire A315-24P Laptop, Mobile, Android 12, OnePlus Nord, EchoGPT Website | 5/12/2025 7:15pm | 004 | Like count not updating |
| T028 | Pass | Desktop, Chrome Latest, Windows 11, Acer Aspire A315-24P Laptop, Mobile, Android 12, OnePlus Nord, Both Websites and both app | 5/12/2025 8:15pm | - | Logout session success |
| T029 | Pass | Desktop, Chrome Latest, Windows 11, Acer Aspire A315-24P Laptop, Mobile, Android 12, OnePlus Nord, Both Websites and both app | 5/12/2025 8:30pm | - | No unusual behaviour is shown |
| T030 | Pass | Mobile, Android 12, OnePlus Nord, both app | 5/12/2025 8:40pm | - | No unusual behaviour is shown |
| T031 | Pass | Desktop, Chrome Latest, Windows 11, Acer Aspire A315-24P Laptop, Mobile, Android 12, OnePlus Nord, AppTestingService Websites and app | 5/12/2025 9:20pm | - | Account created successfully |
| T032 | Fail | Desktop, Chrome Latest, Windows 11, Acer Aspire A315-24P Laptop, Mobile, Android 12, OnePlus Nord, AppTestingService Websites and app | 5/12/2025 10:00pm | 008 | Account created with non existent mail |
| T033 | Pass | Desktop, Chrome Latest, Windows 11, Acer Aspire A315-24P Laptop, Mobile, Android 12, OnePlus Nord, AppTestingService Websites and app | 5/12/2025 10:20pm | - | Successful login |
| T034 | Pass | Desktop, Chrome Latest, Windows 11, Acer Aspire A315-24P Laptop, Mobile, Android 12, OnePlus Nord, AppTestingService Websites and app | 5/12/2025 10:23pm | - | Login fails with invalid cridentials |
| T036 | Fail | Desktop, Chrome Latest, Windows 11, Acer Aspire A315-24P Laptop, Mobile, Android 12, OnePlus Nord, AppTestingService Websites and app | 5/12/2025 10:26pm | 010 | Invalid Discord Link |
| T038 | Pass | Desktop, Chrome Latest, Windows 11, Acer Aspire A315-24P Laptop, Mobile, Android 12, OnePlus Nord, AppTestingService Website | 5/12/2025 10:50pm | - | Everything works fine |
| T039 | Pass | Mobile, Android 12, OnePlus Nord, Both App | 5/12/2025 11:20pm | - | Data restored from server |
| T040 | Pass | Mobile, Android 12, OnePlus Nord, Both App | 6/12/2025 10:24am | - | No crash/freeze/memory leak |
| T041 | Fail | AppTestingService AppMobile, Android 12, OnePlus Nord, | 6/12/2025 11:30am | 012 | Empty Message is sent |
| T042 | Fail | Desktop, Chrome Latest, Windows 11, Acer Aspire A315-24P Laptop, Mobile, Android 12, OnePlus Nord, EchoGPT Website | 6/12/2025 11:37am | 005 | Email did not launch |

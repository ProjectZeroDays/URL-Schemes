# URL-Schemes
List of URL Schemes 

URL Schemes and Usage:

Run a shortcut from a URL
Open a URL with the following structure: 

shortcuts://run-shortcut?name=[name]&input=[input]

Use the following parameters in the URL:

name: The name of the shortcut to run.

input (optional): 

The initial input into the shortcut. There are two input options: a text string or the word clipboard. When the input value is a text string, that text is used. When the input value is clipboard, the contents of the clipboard are used.

By using a text string, you can provide your own URL-encoded text as input to the shortcut. For example, a URL that uses the text “soup” as input to a shortcut named Make PDF would look like this:

shortcuts://run-shortcut?name=Make%20PDF&input=text&text=soup

A URL to transfer the most recently copied text into a shortcut called Add to Bear would look like this:

shortcuts://run-shortcut?name=Add20%to20%Bear&input=clipboard

Tip: 

If you’d like to run one shortcut from another shortcut, use the Run Shortcut action instead of a URL scheme. You should only run shortcuts with a URL if you’re integrating from another app outside of Shortcuts.

Apple Music:

Open = music://
Open = musics://
Open = audio-player-event://

Unverified:
-----------
Open radio = itsradio://
Open radio = itsradios://
Open radio = itunesradio://
Open radio = itunesradios://  (just opens Music)

Apple News:

Open = applenews://
Open = applenewss://

App Store:

Open = itms-apps://itunes.apple.com
Open app = itms-apps://itunes.apple.com/app/id
Search = itms-apps://search.itunes.apple.com/WebObjects/MZSearch.woa/wa/search?media=software&term=YourQuery
Top charts = itms-apps://itunes.apple.com/WebObjects/MZStore.woa/wa/viewTop?genreId=36&popId=30

Apple TV:

Open = videos://

Calendar:

Open = calshow://
Open = x-apple-calevent://
Add calendar = webcal://SuscribeLinkForTheCalendar

Clips:

Open = clips://

Contacts:

Unverified:
-----------
Open = contacts://

Diagnostics:

Open = diagnostics://
Open = diags://

Facetime:

Start audio call = facetime-audio://TheirPhoneNumberOrEmailAddress
Start audio call = facetime-audio-prompt://TheirPhoneNumberOrEmailAddress
Start video call = facetime://TheirPhoneNumberOrEmailAddress
Start video call = facetime-prompt://TheirPhoneNumberOrEmailAddress

Feedback:

Open = applefeedback://

Find My Friends:

Open = findmyfriends://
Open = fmf1://
Open = grenada://

Find My iPhone:

Open = fmip1://

Game Center:

Unverified:
-----------
Open = gamecenter://  (pre-iOS 11)
Open = itms-gc://  (pre-iOS 11)
Open = itms-gcs://  (pre-iOS 11)

Garage Band:

Open = garageband://

iBooks:

Open = ibooks://
Open = itms-books://
Open = itms-bookss://

iCloud Drive:

Unverified:
-----------
Open = appleiclouddrive://  (pre-iOS 11)

iMovie:

Open = imovie://

iTune Remote:

Open = remote://

iTunes Store:

Open = itms://
Open = itmss://

iTunes:

Open = itms-itunesu://

Maps:

Open = map://
Open = maps://
Open = mapitem://

Mail:

Open = message://
Start draft with recipient = mailto://TheirEmailAddress
Start draft with recipient, cc = mailto:TheirEmailAddress?cc=TheirEmailAddress
Start draft with recipient, bcc = mailto:TheirEmailAddress?bcc=TheirEmailAddress
Start draft with recipient, subject = mailto:TheirEmailAddress&subject=Your%20Subject%20Text
Start draft with recipient, body = mailto:TheirEmailAddress&body=Your%20Body%20Text
Start draft with recipient, CC, BCC, subject, body = mailto:TheirEmailAddress?cc=TheirEmailAddress?bcc=TheirEmailAddress&subject=Your%20Subject%20Text&body=Your%20Body%20Text

[You can make other combinations above using the above identifiers]

Messages:

Open text for contact = sms://TheirPhoneNumber

Notes:

Open = mobilenotes://

Phone:

Call contact = tel://TheirPhoneNumber
Call contact = telprompt://TheirPhoneNumber

Photos:

Open = photos-redirect://

Podcasts:

Add feed by URL = feed://
Add feed by URL = podcast://
Add specific feed by URL = feed://TheUrlOfTheFeed
Add specific feed by URL = podcast://TheUrlOfTheFeed

Unverified:
-----------
Browse = pcast://
Browse = itms-pcast://
Browse = itms-pcasts://
Browse = podcasts://
Browse = itms-podcast://
Browse = itms-podcasts://  (displays a "can't connect" error)

Reminders:

Open = x-apple-reminder://

Safari:

Search = x-web-search://
Open FTP file = ftp://LocationToFileOnFtpServer
Open HTTP site = http://WebsiteURL
Open HTTPS site = https://WebsiteURL

Apple Settings:

Open = App-prefs:// or App-prefs:
Open = prefs:// or prefs:
Open = prefs:root

Accessibility = prefs:root=ACCESSIBILITY
Apple Pencil (iPad-only) = prefs:root=Pencil
App Store = prefs:root=STORE
App Store ⇾ App Downloads = prefs:root=STORE&path=App%20Downloads
App Store ⇾ Video Autoplay = prefs:root=STORE&path=Video%20Autoplay
Battery = prefs:root=BATTERY_USAGE
Battery ⇾ Battery Health (iPhone-only) = prefs:root=BATTERY_USAGE&path=BATTERY_HEALTH
Bluetooth = prefs:root=Bluetooth
Books = prefs:root=IBOOKS
Calendar = prefs:root=CALENDAR
Calendar ⇾ Alternate Calendars = prefs:root=CALENDAR&path=Alternate%20Calendars
Calendar ⇾ Sync = prefs:root=CALENDAR&path=Sync
Calendar ⇾ Default Alert Times = prefs:root=CALENDAR&path=Default%20Alert%20Times
Calendar ⇾ Default Calendar = prefs:root=CALENDAR&path=Default%20Calendar
Camera = prefs:root=CAMERA
Camera ⇾ Record Video = prefs:root=CAMERA&path=Record%20Video
Camera ⇾ Record Slo-mo = prefs:root=CAMERA&path=Record%20Slo-mo
Cellular = prefs:root=MOBILE_DATA_SETTINGS_ID
Compass = prefs:root=COMPASS
Contacts = prefs:root=CONTACTS
Control Center = prefs:root=ControlCenter
Control Center ⇾ Customize Controls = prefs:root=ControlCenter&path=CUSTOMIZE_CONTROLS
Display = prefs:root=DISPLAY
Display ⇾ Auto Lock = prefs:root=DISPLAY&path=AUTOLOCK
Display ⇾ Text Size = prefs:root=DISPLAY&path=TEXT_SIZE
Do Not Disturb = prefs:root=DO_NOT_DISTURB
Do Not Disturb ⇾ Allow Calls From = prefs:root=DO_NOT_DISTURB&path=Allow%20Calls%20From
Emergency SOS = prefs:root=EMERGENCY_SOS
Face ID = prefs:root=PASSCODE
FaceTime = prefs:root=FACETIME
Game Center = prefs:root=GAMECENTER
General = prefs:root=General
General ⇾ About = prefs:root=General&path=About
General ⇾ Software Update = prefs:root=General&path=SOFTWARE_UPDATE_LINK
General ⇾ CarPlay = prefs:root=General&path=CARPLAY
General ⇾ Background App Refresh = prefs:root=General&path=AUTO_CONTENT_DOWNLOAD
General ⇾ Multitasking (iPad-only) = prefs:root=General&path=MULTITASKING
General ⇾ Date & Time = prefs:root=General&path=DATE_AND_TIME
General ⇾ Keyboard = prefs:root=General&path=Keyboard
General ⇾ Keyboard ⇾ Keyboards = prefs:root=General&path=Keyboard/KEYBOARDS
General ⇾ Keyboard ⇾ Text Replacement = prefs:root=General&path=Keyboard/USER_DICTIONARY
General ⇾ Keyboard ⇾ One Handed Keyboard = prefs:root=General&path=Keyboard/ReachableKeyboard
General ⇾ Language & Region = prefs:root=General&path=INTERNATIONAL
General ⇾ Dictionary = prefs:root=General&path=DICTIONARY
General ⇾ Profiles = prefs:root=General&path=ManagedConfigurationList
General ⇾ Reset = prefs:root=General&path=Reset
Health = prefs:root=HEALTH
iCloud = prefs:root=CASTLE
iCloud Backup = prefs:root=CASTLE&path=BACKUP
Mail = prefs:root=MAIL
Mail ⇾ Preview = prefs:root=MAIL&path=Preview
Mail ⇾ Swipe Options = prefs:root=MAIL&path=Swipe%20Options
Mail ⇾ Notifications = prefs:root=MAIL&path=NOTIFICATIONS
Mail ⇾ Blocked = prefs:root=MAIL&path=Blocked
Mail ⇾ Muted Thread Action = prefs:root=MAIL&path=Muted%20Thread%20Action
Mail ⇾ Blocked Sender Options = prefs:root=MAIL&path=Blocked%20Sender%20Options
Mail ⇾ Mark Addresses = prefs:root=MAIL&path=Mark%20Addresses
Mail ⇾ Increase Quote Level = prefs:root=MAIL&path=Increase%20Quote%20Level
Mail ⇾ Include Attachments with Replies = prefs:root=MAIL&path=Include%20Attachments%20with%20Replies
Mail ⇾ Signature = prefs:root=MAIL&path=Signature
Mail ⇾ Default Account = prefs:root=MAIL&path=Default%20Account
Maps = prefs:root=MAPS
Maps ⇾ Driving & Navigation = prefs:root=MAPS&path=Driving%20%26%20Navigation
Maps ⇾ Transit = prefs:root=MAPS&path=Transit
Measure = prefs:root=MEASURE
Messages = prefs:root=MESSAGES
Music = prefs:root=MUSIC
Music ⇾ Cellular Data = prefs:root=MUSIC&path=com.apple.Music:CellularData
Music ⇾ Optimize Storage = prefs:root=MUSIC&path=com.apple.Music:OptimizeStorage
Music ⇾ EQ = prefs:root=MUSIC&path=com.apple.Music:EQ
Music ⇾ Volume Limit = prefs:root=MUSIC&path=com.apple.Music:VolumeLimit
News = prefs:root=NEWS
Notes = prefs:root=NOTES
Notes ⇾ Default Account = prefs:root=NOTES&path=Default%20Account
Notes ⇾ Password = prefs:root=NOTES&path=Password
Notes ⇾ Sort Notes By = prefs:root=NOTES&path=Sort%20Notes%20By
Notes ⇾ New Notes Start With = prefs:root=NOTES&path=New%20Notes%20Start%20With
Notes ⇾ Sort Checked Items = prefs:root=NOTES&path=Sort%20Checked%20Items
Notes ⇾ Lines & Grids = prefs:root=NOTES&path=Lines%20%26%20Grids
Notes ⇾ Access Notes from Lock Screen = prefs:root=NOTES&path=Access%20Notes%20from%20Lock%20Screen
Notifications = prefs:root=NOTIFICATIONS_ID
Notifications ⇾ Siri Suggestions = prefs:root=NOTIFICATIONS_ID&path=Siri%20Suggestions
Passwords & Accounts = prefs:root=ACCOUNTS_AND_PASSWORDS
Passwords & Accounts ⇾ Fetch New Data = prefs:root=ACCOUNTS_AND_PASSWORDS&path=FETCH_NEW_DATA
Passwords & Accounts ⇾ Add Account = prefs:root=ACCOUNTS_AND_PASSWORDS&path=ADD_ACCOUNT

Personal Hotspot = prefs:root=INTERNET_TETHERING
Personal Hotspot ⇾ Family Sharing = prefs:root=INTERNET_TETHERING&path=Family%20Sharing
Personal Hotspot ⇾ Wi-Fi 
Password = prefs:root=INTERNET_TETHERING&path=Wi-Fi%20Password

Phone = prefs:root=Phone

Photos = prefs:root=Photos

Privacy: prefs:root=Privacy

Privacy ⇾ Location Services = prefs:root=Privacy&path=LOCATION

Privacy ⇾ Contacts = prefs:root=Privacy&path=CONTACTS

Privacy ⇾ Calendars = prefs:root=Privacy&path=CALENDARS

Privacy ⇾ Reminders = prefs:root=Privacy&path=REMINDERS

Privacy ⇾ Photos = prefs:root=Privacy&path=PHOTOS

Privacy ⇾ Microphone = prefs:root=Privacy&path=MICROPHONE

Privacy ⇾ Speech Recognition = prefs:root=Privacy&path=SPEECH_RECOGNITION

Privacy ⇾ Camera = prefs:root=Privacy&path=CAMERA

Privacy ⇾ Motion = prefs:root=Privacy&path=MOTION

Reminders = prefs:root=REMINDERS
Reminders ⇾ Default List = prefs:root=REMINDERS&path=DEFAULT_LIST

Ringtone = prefs:root=Sounds&path=Ringtone

Safari = prefs:root=SAFARI
Safari ⇾ Content Blockers = prefs:root=SAFARI&path=Content%20Blockers
Safari ⇾ Downloads = prefs:root=SAFARI&path=DOWNLOADS
Safari ⇾ Close Tabs = prefs:root=SAFARI&path=Close%20Tabs
Safari ⇾ Page Zoom = prefs:root=SAFARI&path=Page%20Zoom
Safari ⇾ Request Desktop Website = prefs:root=SAFARI&path=Request%20Desktop%20Website
Safari ⇾ Reader = prefs:root=SAFARI&path=Reader
Safari ⇾ Camera = prefs:root=SAFARI&path=Camera
Safari ⇾ Microphone = prefs:root=SAFARI&path=Microphone
Safari ⇾ Location = prefs:root=SAFARI&path=Location
Screen Time = prefs:root=SCREEN_TIME
Screen Time ⇾ Downtime = prefs:root=SCREEN_TIME&path=DOWNTIME
Screen Time ⇾ App Limits = prefs:root=SCREEN_TIME&path=APP_LIMITS
Screen Time ⇾ Always Allowed = prefs:root=SCREEN_TIME&path=ALWAYS_ALLOWED
Shortcuts = prefs:root=SHORTCUTS
Siri = prefs:root=SIRI
Sounds = prefs:root=Sounds
Settings ⇾ TV = prefs:root=TVAPP
Voice Memos = prefs:root=VOICE_MEMOS
VPN = prefs:root=General&path=VPN
Wallet = prefs:root=PASSBOOK
Wallpaper = prefs:root=Wallpaper
Wi-Fi = prefs:root=WIFI

Shortcuts:

Open = shortcuts://
Create new shortcut = shortcuts://create-shortcut
Open shortcut = shortcuts://open-shortcut?name=Your%20Shortcuts%20Name
Run shortcut = shortcuts://run-shortcut?name=Your%20Shortcuts%20Name
Run shortcut with text string input = shortcuts://run-shortcut?name=Your%20Shortcuts%20Name&input=text&text=What%20You%20Want%20To%20Input
Run shortcut with input from clipboard = shortcuts://run-shortcut?name=Your%20Shortcuts%20Name&input=clipboard

Voice Memos:

Open = voicememos://  (could work in the Notification Center)

Wallet:

Open = shoebox://

Apple Watch:

Open = itms-watch://
Open = itms-watchs://

Workflow:

Open = workflow://
Create workflow = workflow://create-workflow
Open a workflow = workflow://open-workflow?name=TheNameOfWorkflow
Run a workflow = workflow://run-workflow?name=TheNameOfWorkflow&input=Input
Open the gallery = workflow://gallery
Search the gallery = workflow://gallery/search?query=YourQuery

Third-Party Apps & Services

Achievement - Reward Health:
Open = achievement://

Age of Solitaire : Build City:
fb1431194636974533://

Airmail:
Open = airmail://
Start draft = airmail://compose
Start draft with recipient = airmail://compose?to=TheirEmailAddress
Start draft with recipient, cc = airmail://compose?to=TheirEmailAddress&cc=TheirEmailAddress
Start draft with recipient, bcc = airmail://compose?to=TheirEmailAddress&bcc=TheirEmailAddress
Start draft with recipient, subject = airmail://compose?to=TheirEmailAddress&subject=YourSubjectText
Start draft with recipient, body = airmail://compose?to=TheirEmailAddress&plainBody=YourBodyText
Start draft with recipient, HTML body = airmail://compose?to=TheirEmailAddress&htmlBody=YourBodyHTML
Start draft with recipient, CC, BCC, subject, body = airmail://compose?to=TheirEmailAddress&cc=TheirEmailAddress&bcc=TheirEmailAddress&subject=YourSubjectText&plainBody=YourBodyText

[You can make other combinations above using the above identifiers]

Airtable:
Open = airtable://

AMC Theatres:
Open = amc://

Alpha Omega:
Open = fb1414385748867269suffix://

AmpliFi WiFi:
Open = fb1761190244145574amplifi://

Ancestry:
Open = ancestry://

Anchor:
Open = anchorfm://
Open = anchorfmspotify://

Asana: organize tasks & work:
Open = asana://

Autodesk SketchBook:
Open = sketchbook://

Bank of America Mobile Banking:
Open = bofa://

Bejeweled Blitz:
Open = com.popcap.ios.BejBlitz://
Open = com.popcap.ios.BejBlitz.From.Bej3://
Open = com.popcap.ios.BejBlitz.From.Bej2://
Open = ea850758://
Open = ea47862://

Brushstroke:
Open = brushstroke://

Buddhify: meditation on the go:
Open = com.21awake.buddhify2://
Cake Browser:
Open = cakeslice://
Open = havecake://
Camera+:
Open = cameraplus://
Carb Manager: Keto Diet App:
Open = carbmanager://
Cash App:
Open = squarecash://
Open = cashme://
Clash of Clans:
Open = clashofclans://
Open = wxfa242abf8cdd841a://
Open = tencent1105771533://
Open = tencentlaunch1105771533://
DoorDash - Food Delivery:
Open = doordash://
Draw Something:
Open = fb225826214141508paid://
DropBox:
Open = dbapi-1://
DuckDuckGo Privacy Browser:
Open = ddgLaunch://
Open = ddgQuickLink://
Duolingo:
Open = duolingo://
Open = com.duolingo.DuolingoMobile
Enlight Videoleap Video Editor:
Open = videoleap://
Evernote:
Open = Evernote://
Facebook:
Open = fb://
Facetune:
Open = facetune://
Fandango:
Open = fandango://
Fitbit:
Open = fitbit://
Flickr:
Open = flickr://
Gboard:
Open = gboard://
Gmail - Email by Google:
Open = googlegmail://
Goodreads: Book Reviews:
Open = goodreads://
Google:
Open = google://

Google Assistant:
Open = googleassistant://

Google Calendar:
Open = googlecalendar://

Google Docs:
Open = googledocs://
Open = googledocs-v2://
Open = com.google.sso.263492796725://

Google Chrome:
Open = googlechrome://

Google Drive:
Open = googledrive://

Google Earth:
Open = googleearth://
Open = comgoogleearth://

Google Keep:
Open = comgooglekeep://

Google Maps - GPS Navigation:
Open = googlemaps://

Google Photos:
Open = googlephotos://

Google Sheets:
Open = googlesheets://

Google Translate:
Open = googletranslate://

Google Voice:
Open = googlevoice://

Gospel Library:
Open = gospellibrary://

Halide Camera:
Open = halide://

Headspace: Meditation & Sleep:
Open = headspace://

HBO GO:
Unverified:
Open = hbogo://

HBO NOW:
Open = hbonow://

Hulu: Watch TV Shows & Movies:
Open = hulu://

Hyperlapse from Instagram:
Open = hyperlapse://

IMDb Movies & TV:
Open = imdb://

Insight Timer - Meditation App:
Open = insight://

Instagram:
Open = instagram://

Kahoot! Play & Create Quizzes:
Open = kahoot://

Kasa Smart:
Open = kasa://

LastPass Password Manager:
Open = lastpass://

Launch Center Pro:
Unverified:
Open = launch://

Learn Languages with Memrise:
Open = memrise://

Libterm:
Open = libterm:/ssh

Litely:
Open = litely://

Lose It! – Calorie Counter:
Open = loseit://

Messenger:
Open = fb-messenger://

Microsoft Planner:
Open = planner://

Microsoft PowerPoint:
Open = powerpoint://

Microsoft Word:
Open = word://

MoviePass:
Open = moviepass://

Netflix:
Open = nflx://

Outline:
Open = ss://open
ss://YWVzLTI1Ni1jZmI6c3NtZ3I5OTYwNDY0ODE2QGEzNDU4OTEzNDYuZ3l0ZW5nLmNvbTo2MTEyOA==

PayPal: Mobile Cash:
Open = paypal://

PhotoScan by Google Photos:
Open = photoscan://

Pinterest:
Open = pinterest://

Pocket: Save. Read. Grow.:
Open = pocket://
Open = readitlater://
Open = pocket-oauth-v1://
Open = en-readitlater-5776://
Open = com.ideashower.ReadItLaterPro3://
Open = com.ideashower.ReadItLaterPro://
Open = com.ideashower.ReadItLaterProAlpha://
Open = com.ideashower.ReadItLaterProEnterprise://

Potatso:
Open = ssr://on
ssr://YWVzLTI1Ni1jZmI6c3NtZ3I5OTYwNDY0ODE2QGEzNDU4OTEzNDYuZ3l0ZW5nLmNvbTo2MTEyOA==

Quizizz: Play to Learn:
Open = quizizz://

Reflectly:
Open = reflectly://
Open = reflectlylink://

Rosetta Stone: Learn Languages:
Open = rstotalecompanion://
Open = learnlanguages://

Signal - Private Messenger:
Open = sgnl://

SimpleMind + Mind Mapping:
Open = simplemind://

Open Flixster:
flixster://

Open RadarScope to a specific coordinate:
open = radarscope://viewInMap?lat=0&long=0

Open A New Note in Simple Note:
Open = simplenote://new

Skype for iPhone:
Open = skype://

Sleep Cycle: smart alarm clock:
Open = sleepcycle://

Snapchat:
Open = snapchat://

Spark:
Open = readdle-spark://
Start draft = readdle-spark://compose
Start draft with recipient = readdle-spark://compose?recipient=TheirEmailAddress
Start draft with recipient, subject = readdle-spark://compose?recipient=TheirEmailAddress&subject=YourSubjectText
Start draft with recipient, subject, body = readdle-spark://compose?recipient=TheirEmailAddress&subject=YourSubjectText&body=YourBodyText

[You can make other combinations above using the above identifiers]

Speedtest by Ookla:
Open = speedtest://

Spotify Music:
Open = spotify://

Steller:
Open = steller://

Streaks:
Open = streaks://
Today Habit tracker:
Open = today://
Open = todayCheckinHabit://

Trello:
Open = trello://

Tumblr:
Unverified:
Open = tumblr://

Twitch:
Open = twitch://

Twitter:
Open = twitter://

TweetBot for Twitter:
Unverified:
Open = tweetbot://

Udemy Online Video Courses:
Open = udemy://

Vimeo:
Unverified:
Open = vimeo://

VSCO:
Open = vsco://

Waze Navigation & Live Traffic:
Open = waze://

WhatsApp Messenger:
Open = whatsapp://

Open Yelp and search for “Coffee” nearby:
yelp4:///search?terms=Coffee

YNAB (You Need A Budget):
Open = ynab://

YouTube: Watch, Listen, Stream:
Open = youtube://

ZuluDesk Student:
Open = zuludesk://

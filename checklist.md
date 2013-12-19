## App Development Company Limited

*RELEASE AUTHORISATION FORM v1.0*

|  |  |
|:-------------------------------------|-------------------------------------:|
| App name                             |      IS                              |
| Version                              |      1.0                             |
| Date of submission                   |      TBD                             |

This form is to document the testing that has been done on each app
version before submitting to the App Store. For each item, indicate *Yes*
if the testing has been done, *Not Applicable* if the testing does not
apply (eg testing audio for an app that doesn’t play any), or *No* if the
testing has not been done for another reason.

--

###Internet Connectivity
Test all the data downloading sections of the app by trying them on the appropriate connection type. Consider graceful degradation and failure as well as success conditions.

| Connection | N/A | NO | YES |
|:---|:---:|:---:|:---:|
| Wifi | | | |
| Edge | | | |
| GPRS | | | |
| No Network | | | |
| Break in Network - use Charles | | | |
| Server unreachable - timeout | | | |

--

###Locale
Change device’s settings then load the app. Check that dates appear correctly, especially dates from external feeds or services.

| Locale | N/A | NO | YES |
|:---|:---:|:---:|:---:|
| 12 and 24 hour clocks | | | |
| Timezones  | | | |
| Daylight Savings Time | | | |

--

### Devices
Run the application through navigations using different devices with different iOS versions and display formats.

| Device | N/A | NO | YES |
|:---|:---:|:---:|:---:|
| iPhone running iOS 7.0 | | | |
| iPod touch running iOS 7.0 | | | |
| Retina iPhone display | | | |
| Non-retina iPhone display | | | |
| iPad running iOS 7.0 | | | |
| Retina iPad display | | | |
| Non-retina iPad display | | | |
| iPad mini display | | | |

--

###Location

| Location | N/A | NO | YES |
|:---|:---:|:---:|:---:|
| True GPS | | | |
| Wifi location | | | |
| Cell tower location | | | |
| Unable to find location | | | |
| No results returned (e.g. too far from any searchable points of interest)  | | | |
| Location services turned off | | | |
| Location services disabled for this app | | | |

--

###Camera / Video
If app takes pictures or video clips, perform the following checks. For streaming video, make sure the checks in the network section above have also been done.

| Camera / Video | N/A | NO | YES |
|:---|:---:|:---:|:---:|
| Primary camera photo taken | | | |
| Secondary (user facing) camera taken | | | |

--

###Logging

| Logging | N/A | NO | YES |
|:---|:---:|:---:|:---:|
| Logging events to live server | | | |
| Logging errors (interact with other tests?) | | | |

--

###User Interface
Test each major view in the app.

| Title | N/A | NO | YES |
|:---|:---:|:---:|:---:|
| Double height status bar (eg in call) | | | |
| VoiceOver turned on | | | |
| Usable by a new user with Screen Curtain turned on | | | |
| Works with Accessibility Zoom turned on | | | |

--

###Text

| Title | N/A | NO | YES |
|:---|:---:|:---:|:---:|
| Shake to Undo | | | |
| Text selection (including disabled when appropriate) | | | |
| Copy / Paste | | | |
| Editing when keyboard is hidden | | | |
| Dictionary / Suggested Word hover | | | |

--

###Third Party Services
All third party services should use production API key and the new app version should be registered in the respective dashboards

| Title | N/A | NO | YES |
|:---|:---:|:---:|:---:|
| Production analytics/tracking API key | | | |
| New app version tracking data available tracking in dashboard | | | |
| Production crash reporting API key | | | |
| Upload dSYM to crash reporting tool | | | |
| New app version available in crash reporting dashboard | | | |
| Push notification service API key | | | |
| New app version added to push service dashboard | | | |
| Production App ID for social services (Twitter, Facebook, Instagram, etc) | | | |

--

###Misc

| Misc | N/A | NO | YES |
|:---|:---:|:---:|:---:|
| Tested in Ad Hoc mode | | | |
| Version number upgraded | | | |
| Bundle identifier correct for release | | | |

--
<br><br>

Sign-off: __________________________________________  

<br><br><br>
Project role: _______________________________________  

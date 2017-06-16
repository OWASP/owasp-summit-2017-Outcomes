# Owasp Orizon Reboot summit outcomes

On Wednesday June, 14th 2017 a session was conducted to kickstart the Owasp
Orizon project again.

Owasp Orizon is a source code security scanner designed to spot vulnerabilities
in J2EE web applications, Android code and generally speaking in Java written
source code.
 
During the session, we agreed on a small list of project quick wins:

- There is the need of a SAST tool for Owasp. Kickstarting Orizon again is a
  good idea. Even if Paolo mispelled the name when he first created it (please
  read it like you would read _horizon_).
- A team of people interested in working on Orizon. We should copy the ZAP
  model, so we must keep the project alive, with regular updates so to get
  traction.
- Multiple programming languages support must be in place. However this should
  be a second project goals.
- We must find a good opensource class file parser.
- Orizon will act as 'grep++' tool in its first releases to make sure give
  people something to work with
- Orizon output will be a raw console stuff. Nice GUI eventually, would be
  added later on.

| Due date | Task                             |
|----------|----------------------------------|
| September 2017 | the class file and (potentially) apk files would consumed by the tool |
| December 2017 | APK file should be supported |
| January 2018 | some very basic pattern matching checks (like hardcoded credentials) |
| March 2018 | focus on A1 Injection and A3 Cross site scripting support first |

## Useful links

- OWASP Orizon [page](https://www.owasp.org/index.php/Category:OWASP_Orizon_Project)
- GitHub repository: [here](https://github.com/thesp0nge/owasp-orizon)

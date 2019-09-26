![N|Solid](https://www.ncsc.gov.uk/static-assets/images/ncsc_larger_strap.png)
# Logging Made Easy

Copyright 2018-2019 Crown Copyright
 
Licensed under the Apache License, Version 2.0 (the "License"); you may not use this file except in compliance with the License. You may obtain a copy of the License at
 
http://www.apache.org/licenses/LICENSE-2.0
 
Unless required by applicable law or agreed to in writing, software distributed under the License is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the License for the specific language governing permissions and limitations under the License.



## Who is the NCSC and why did they create LME?
The National Cyber Security Centre (NCSC) is a UK Government department with the mission of:

  **"Helping to make the UK the safest place to live and work online."**

..more can be found on www.ncsc.gov.uk.


## Table of contents

[Prerequisites - Start deployment here](/docs/prerequisites.md)

[Chapter 1 - Set up Windows Event Forwarding](/docs/chapter1.md)

[Chapter 2 – Sysmon Install](/docs/chapter2.md)

[Chapter 3A – Database (Easy Method)](/docs/chapter3-easy.md)

[Chapter 3B – Database (Manual Method)](/docs/chapter3-manual.md)

[Chapter 4 - Post Install Actions ](/docs/chapter4.md)

[FAQ](/docs/faq.md)

[Troubleshooting](/docs/troubleshooting.md)

## Credits
### Core Team
* Shane M, NCSC Technical Lead.
* Lucy A, David L and Oli T, Cabinet Office Government Security Group, funding and project management.
* Adam B, NCSC, Customer Liaison / Developer.
* Duncan A, NCC Group, Lead Developer.
* Harry G and Alfie T, NCSC, creating visualisations.

### Our development partners
These organisations spent time trialing earlier versions of LME which was critical to development and publication.
* Diane L at [Ofqual](http://ofqual.gov.uk)
* Gavin M at [Creative Scotland](https://www.creativescotland.com)
* Carol P and Andy M at [Renfrewshire Council](http://www.renfrewshire.gov.uk)
* Chris B and Andrew H at [Cardiff Council](http://www.cardiff.gov.uk)
* Julian D and the team at [Companies House](https://www.gov.uk/government/organisations/companies-house)
* Martin O at [TeamGB](https://www.teamgb.com/)
* The NCSC CAPRI team
* David C

### The Community
* Roberto Rodriguez ([@Cyb3rWard0g](https://twitter.com/Cyb3rWard0g) and [@THE_HELK](https://twitter.com/THE_HELK)) provided guidance and authored HELK (similar to LME but more featured) [HELK on Github](https://github.com/Cyb3rWard0g/HELK)
* Carl Morris sharing experiences behind his [44Con presentation](https://github.com/SecureDataLabs/44Con-2018-Sysmon)
* [SwiftOnSecurity](https://twitter.com/swiftonsecurity) for creating an open-source Sysmon configuration which we refer to.
* [Jessica Payne](https://twitter.com/jepaynemsft) acknowledging her [WEFFLES](https://blogs.technet.microsoft.com/jepayne/2017/12/08/weffles/) blog highlighting what's possible with in-built Windows functionality.
* [Ryan Watson](https://twitter.com/gentlemanwatson) and [Syspanda](http://www.syspanda.com/) from which the Sysmon install script was adapted from.

### Technology Used
* [Sysmon](https://docs.microsoft.com/en-us/sysinternals/downloads/sysmon) from the [Sysinternals team](https://docs.microsoft.com/en-us/sysinternals/) at Microsoft.
* Elasticsearch, Logstash, Kibana and Winlogbeat from [Elastic.co](https://elastic.co/) and their [github](https://github.com/elastic)
* [Docker Community Edition](https://github.com/docker/docker-ce)

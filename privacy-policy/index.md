---
title: Privacy Policy — AI Music Manager
---
# Privacy Policy

Last updated: 25 October 2026.

## 1. Who is responsible

**Controller and operator:** Tomáš Kučera, an individual based in the Czech Republic.  
**Privacy contact:** [countertom@gmail.com](mailto:countertom@gmail.com).

AI Music Manager supports the operator's own music projects, including RENYVO and ERVAYO, and their authorized professional social-media accounts. It is an internal management tool, not an open service for connecting unrelated people's accounts. This notice covers the backend, its authorized use and these public information pages.

## 2. Information and its sources

Depending on the authorized feature and information available from Meta, the Instagram integration can retrieve account identifiers, usernames and account type; post identifiers, captions, links, timestamps and engagement counts; and comment identifiers, text, usernames, timestamps and like counts. These data come from Meta's Instagram API and may relate to people interacting with the operator's posts. API authorization does not guarantee that every requested field or comment will be available.

The current integration does not access direct messages, address books or Instagram passwords. It reads an access token configured as a protected application variable. Instagram data are returned to the authorized operator's client on request. The current comment module does not write comment content or commenter profiles to the application database or object storage.

Separate music functions handle operator-supplied concepts, prompts, lyrics, production notes, audio, artwork and release metadata, including contributor credits where provided. PostgreSQL stores project records and object storage holds music and artwork files.

Technical records can include IP addresses, request paths and parameters, timestamps, response codes and diagnostic identifiers. Privacy correspondence contains the information a requester sends and the minimum information needed to resolve the request.

## 3. Purposes and legal bases

The operator uses account data to review their own professional accounts and audience interactions, and technical data to operate, troubleshoot and secure the service. Where personal data are involved, these activities rely on legitimate interests under GDPR Article 6(1)(f), balanced against affected individuals' rights. You may object to this processing.

Rights requests and legally required records are handled to comply with legal obligations under Article 6(1)(c). Any other processing requires an appropriate basis for that purpose; granting an API permission does not by itself replace a lawful basis.

The current comment feature is read-only. A simple phrase-based rule may suggest that a comment needs review; it is not an AI determination that a person is a bot or spammer. The module does not send replies or hide or delete comments, and makes no decisions producing legal or similarly significant effects. The operator does not sell Instagram personal data or use it to build unrelated advertising profiles.

## 4. Providers and disclosure

| Recipient or service | Role in this setup |
| --- | --- |
| Meta / Instagram | Supplies the authorized account and interaction data and independently operates Instagram. |
| Railway | Hosts the application, PostgreSQL, object storage and encrypted database archives; processes requests and operational logs. |
| GitHub / GitHub Pages | Holds source code and publishes these information pages. It can receive technical visitor data; the Instagram module does not export comment datasets or credentials to the public repository. |
| Apple iCloud | Receives additional encrypted database archives copied through the operator's Windows device. The archive password is not included in the archive or the copy job. |
| Google / Gmail | Handles correspondence sent to the published contact address. |
| OpenAI and Mureka | Support separate music functions when the operator invokes them, using the relevant prompts, audio or creative inputs. The current Instagram comment module does not automatically forward its responses to these services. |

An authorized client receives the requested results. If the operator separately copies a result into another service, that service receives the selected information under its own applicable terms. This is separate from the backend's comment-reading function; personal data must be minimized and the relevant legal and platform requirements checked before additional use.

Access is limited to the operator and persons authorized for necessary administration, and providers and their authorized personnel as needed to supply, maintain or secure their services. Necessary disclosure may also occur to comply with law or defend legal rights.

## 5. Locations and international transfers

The application, database and configured object-storage regions are currently in California, United States. Railway states that its operational logs are stored in US West. Other listed providers may process information outside the European Economic Area under their applicable arrangements; no EU-only processing promise is made.

Where GDPR requires safeguards for a transfer, an applicable adequacy decision or appropriate safeguards, such as Standard Contractual Clauses, must support it. The data-processing arrangements with Railway are addressed by its [Data Processing Addendum](https://railway.com/legal/dpa), which incorporates Standard Contractual Clauses for applicable transfers. Contact the operator for information about safeguards and available copies, subject to necessary redactions.

## 6. Storage and retention

- **Instagram responses:** processed on demand and returned to the authorized client; no persistent comment archive is implemented in the current backend. A client, an operator-created export or an independently hosted Instagram copy has its own storage lifecycle. Temporary processing in memory is not a database retention period.
- **Project records and files:** retained while needed to manage the music catalogue, support releases and document relevant rights. Personal information no longer needed for these purposes is erased or anonymized, subject to lawful record-keeping or claims requirements.
- **Railway logs:** Railway currently states that runtime, HTTP, build and deployment logs expire after 90 days and individual entries cannot be removed early. Shorter dashboard viewing windows are not the physical deletion period. Logs may include request metadata and IP addresses; the comment module does not intentionally log comment bodies or access tokens.
- **Database archives on Railway:** the job keeps one copy for each of seven successful UTC backup dates and four ISO-week copies. This is a count of successful copies, not a guaranteed seven-day or 28-day expiry; interrupted schedules can leave older archives in place.
- **Independent copies:** downloaded archives on the operator's Windows device and iCloud do not automatically expire. They are used for recovery and must be included in manual retention and erasure reviews, including when the recovery purpose ends. The database-backup job does not itself back up separate audio or artwork objects.
- **Rights correspondence:** retained as needed to handle the request and demonstrate its outcome. Unnecessary verification material is deleted after verification; any further retention must have a documented purpose and period.

Erasure is assessed across live records, manual copies and recovery archives. Backup rotation does not replace an obligation to erase data without undue delay. Any copy that cannot immediately be erased must be restricted from ordinary use, given a documented removal plan and accounted for before restoration. The operator will explain any applicable legal exception or provider limitation rather than promise immediate deletion from every provider system.

## 7. Security and page visits

Management and Instagram routes require the application's authorization header. The Instagram access token is sent to Meta in a request header, not a URL. Database connections between services use private networking; database archives are encrypted before upload and their integrity and restoreability are checked. These measures do not guarantee that incidents can never occur.

The current legal pages add no application analytics or advertising tracker, and the backend does not implement an advertising profile. Hosting providers and a client browser can still generate their own technical records. Do not put passwords, tokens or sensitive personal details into URLs, public issues or unnecessary exports.

## 8. Your rights and contact

Subject to the applicable conditions, you can request access, correction, erasure, restriction or portability of your personal data, object to legitimate-interest processing, or withdraw consent where consent is the basis. Contact [countertom@gmail.com](mailto:countertom@gmail.com). The operator may ask for proportionate information to identify the relevant records and verify the request, and will normally respond without undue delay and within one month. Any lawful extension, refusal or retention exception will be explained.

You may complain to the [Czech Office for Personal Data Protection](https://uoou.gov.cz/) or the competent supervisory authority in your country. See [Data Deletion Instructions](../data-deletion/) for the request procedure. Deleting an application copy does not by itself remove content from Instagram or another independent service.

## 9. Changes

This notice must be reviewed before material changes, including persistent social-data storage, messaging, AI-based processing of commenters' data, automated responses or moderation, additional account owners, or a change of operator. The date above will be revised when the notice changes.

## Provider information

[Railway DPA](https://railway.com/legal/dpa) · [Railway subprocessors](https://trust.railway.com/item/subprocessors) · [Railway log-retention clarification](https://station.railway.com/questions/log-retention-and-data-processing-agreem-223bf7c1) · [GitHub privacy](https://docs.github.com/en/site-policy/privacy-policies/github-general-privacy-statement) · [Apple privacy](https://www.apple.com/legal/privacy/en-ww/) · [Google privacy](https://policies.google.com/privacy) · [OpenAI privacy](https://openai.com/policies/eu-privacy-policy/) · [Mureka](https://www.mureka.ai/)

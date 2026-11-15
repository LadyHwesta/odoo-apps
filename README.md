# Odoo Apps by Meskis Works

Free apps for Odoo 19 Community, published on the
[Odoo Apps Store](https://apps.odoo.com). Each app's own page
(`static/description/index.html`) explains what it does and how to set it up.

| App | What it does |
| --- | --- |
| CalDAV Calendar Sync | Two-way calendar synchronization with any RFC 4791 CalDAV server |
| Fediverse (ActivityPub) | Federate this Odoo instance into the Fediverse (Mastodon, Pleroma, Misskey, ...) over ActivityPub |
| Fediverse: Blog Posts | Federate published blog posts to the Fediverse |
| Fediverse: Events | Federate published events to the Fediverse as Event objects |
| IMAP Authentication | Authenticate existing Odoo users against an IMAP mail server |
| DMARC Reports | Read DMARC aggregate reports and explain them in plain language |
| App Folders and Order | Put apps in your own order and group them into folders, and keep it through upgrades |
| App Folders: Website | Folder headings in the apps dropdown signed-in staff see on website pages |
| Email Templates Menu | A plain Settings menu for editing email templates, no developer mode required |
| Invoice Payment Reminders | A simple multi-stage automatic email schedule for overdue customer invoices |
| Video Call Gallery View | Gallery / Speaker view switch for Discuss video calls, like Zoom and Teams |
| Reload After Upgrades | Open Odoo windows and installed apps reload themselves after a server upgrade |
| Canonical URL Guard | Bots probing odd addresses get a plain 404, not a server error in the log |
| eLearning Lesson Digest | One email per course for lessons added by a module update, and no re-announcing published lessons |
| Meeting Documents | Attach documents to meetings, show them on the calendar, and send them with invitations |
| No Hidden Email Preview | Drop the invisible preview block Odoo puts in every notification email, which spam filters score against |
| Assign Tasks to Contacts | Assign a task or subtask to a specific contact, not just internal staff |
| Mailing List Welcome | Send a welcome email, with an unsubscribe link, to each new website signup |
| Security Auth Guard | Persisted brute-force login reporting, permanent IP blocking, and a unified security event log |
| Security Dashboard | A threat level, failed logins, blocks and events waiting for review, in the Dashboards app |

## Help

The apps are free under the LGPL-3 licence. Help installing, setting up or
using them is available from Meskis Works with a support contract:
sales@meskis.net, or see https://meskis.net/odoo-apps.

## Where the code lives

This repository is a copy, made for the Odoo Apps Store, of modules from
[LadyHwesta/odoo-addons](https://github.com/LadyHwesta/odoo-addons). A daily
job copies them over and checks them against the store's rules
(`.github/workflows/sync.yml`). Please open issues and pull requests there,
not here: changes made here are overwritten.

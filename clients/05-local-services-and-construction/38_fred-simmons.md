# 38. WordPress Site Speed Optimization Expert Needed

- Client: Fred Simmons (Blanton & Sons, heating, cooling and plumbing company, Charleston, South Carolina, United States)
- Upwork workroom: https://www.upwork.com/nx/wm/workroom/42673515/overview
- Message room: https://www.upwork.com/ab/messages/rooms/room_51972efd5079dbf2cbcd0a9e3c0da963
- Dates: 16 Jan 2026 to 9 Jun 2026 (work stopped on 22 Jan; Marcos closed the contract in June)
- Status: Ended (closed early)
- Amount: 400,00 USD fixed price; total paid: 100,00 USD
- Milestones: M1 Audit, 100,00 USD, paid, 16 Jan 2026; M2 Optimizae, 200,00 USD, not started (due 18 Jan); M3 Finish, 100,00 USD, not started (due 19 Jan)
- Rating: no client feedback; Marcos gave him 5.0/5
- Client website: https://blantonandsons.com
- Platform: WordPress
- Sector (niche): Local services and construction
- Alternative sector: none

## Project summary
Fred wanted to speed up his WordPress site (Frost child theme on Cloudways with Breeze and Cloudflare), which loaded third-party booking tools and had active paid campaigns. Marcos sent a fixed-price proposal and started with the audit on staging via SFTP. The audit concluded that the problem was on mobile and was caused by third-party scripts loading early (mainly the ServiceTitan scheduler, the chat widgets and, according to the client, GTM), and that hosting and CDN were not the bottleneck. He recommended delaying or conditioning the loading of ServiceTitan on mobile and prioritizing the LCP resource. Fred approved the audit milestone, but Marcos had repeated access problems because the SFTP required a whitelisted fixed IP, and on 22 January Fred decided not to continue.

## Key decisions and agreements
- Fixed price of 400 USD in three milestones (audit 100, optimization 200, close 100)
- No full server access; work is done via SFTP with a whitelisted IP and first on staging
- Approved approach: delayed or conditional loading of ServiceTitan on mobile, tested on staging
- The client ended the collaboration because of the access problems, as Marcos did not have a fixed IP
- The client shared credentials in the chat

## Deliverables and files exchanged
| Date | Who | File | Size | What it is |
|---|---|---|---|---|
| 16 Jan 2026 | Marcos | WordPress Performance Optimization - Blanton & Sons .pdf | 66 kB | Proposal with scope, timelines and price |
| 16 Jan 2026 | Fred | 1Password link | n/a | Shared access to WordPress |
| 16 Jan 2026 | Fred | Screenshot 2026-01-16 at 11.44.49 AM.png | not recorded | Cloudways SFTP configuration |
| 16 Jan 2026 | Marcos | SFTP.jpg | 359,52 kB | SFTP connection confirmation to staging |
| 17 Jan 2026 | Marcos | Performance Audit — Blanton & Sons.pdf | 210,82 kB | Performance audit with conclusions |

## Open items and notes for the future
- Lesson: for clients with IP whitelisting, it is best to have a fixed IP or a VPN with a dedicated IP
- Fred said he would stay in touch for other projects
- The audit already identifies the optimization plan in case the client comes back

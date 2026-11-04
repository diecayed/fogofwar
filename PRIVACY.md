# Privacy policy

_Last updated: 4 November 2026_

Fog of War ("FOW") is a Windows app for League of Legends players. This page explains what it reads, what it sends and what it stores.

## What FOW reads on your PC
- The League client's local API and, during a game, the game's local Live Client Data API. FOW only reads from them (GET requests to 127.0.0.1); it never changes anything in the client or the game.
- From these it shows your summoner, ranks, match history, champion select and the players in your game.

## What FOW sends over the internet
- **Player lookups** (searching a Riot ID, opening a profile, ranks of players in your game): the Riot ID or player id is sent to FOW's proxy server (hosted on Cloudflare) and from there to the official Riot Games API. If you enter your own Riot developer key, requests go straight to Riot instead.
- **Update check**: the app asks GitHub for the newest release of https://github.com/diecayed/fogofwar.
- **Images**: rank emblems and role icons are loaded from CommunityDragon (raw.communitydragon.org).

FOW has no accounts, no analytics, no ads tracking and no telemetry. The proxy keeps short technical logs (time, requested Riot endpoint, IP address for rate limiting) for up to 7 days to keep the service working and to stop abuse; they are not shared or sold.

## What FOW stores
Everything stays on your PC in `%APPDATA%\FogOfWar`: settings (including your own Riot key, if you add one), your match history and LP snapshots, cached profiles and anonymous game records (champions, roles, augments and results, without names) used for counter and augment statistics. Delete the folder to remove all of it.

## Children
FOW is meant for people old enough to play League of Legends under Riot's terms.

## Contact
Questions or deletion requests: open an issue at https://github.com/diecayed/fogofwar/issues.

Fog of War isn't endorsed by Riot Games and doesn't reflect the views or opinions of Riot Games or anyone officially involved in producing or managing Riot Games properties. Riot Games, and all associated properties are trademarks or registered trademarks of Riot Games, Inc.

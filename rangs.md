---
title: Rangs & Permissions
layout: default
nav_order: 3
---

# Rangs & Permissions

## Permissions

| Permission | Rang | Effet |
|---|---|---|
| `axommo.vip` | VIP | Cooldowns réduits, warmups réduits, 5 homes max, 10 enchères max, 2 morts dans /back |
| `axommo.ultime` | ULTIME | Cooldowns très réduits, warmups très réduits, 10 homes max, 20 enchères max, 5 morts dans /back |
| `axommo.staff` | Staff | Cooldowns et warmups bypassés, 100 homes max, 100 enchères max, 5 morts dans /back |

Priorité : STAFF > ULTIME > VIP.

## Cooldowns

| Commande | Défaut | VIP | ULTIME | Staff |
|---|---|---|---|---|
| `/rtp` | 15 min | 10 min | 5 min | 1 sec |
| `/home` | 1 min | 30 sec | 10 sec | 1 sec |
| `/sethome` | 1 min | 30 sec | 10 sec | 1 sec |
| `/delhome` | 1 min | 30 sec | 10 sec | 1 sec |
| `/tpa` / `/tpahere` | 3 min | 2 min | 1 min | 5 sec |
| `/back` | 10 min | 5 min | 2 min | 1 sec |

## Warmups

| Commande | Défaut | VIP | ULTIME | Staff |
|---|---|---|---|---|
| `/rtp` | 10 sec | 5 sec | 3 sec | 1 sec |
| `/home` | 5 sec | 3 sec | 2 sec | 1 sec |
| `/tpaccept` | 5 sec | 3 sec | 2 sec | 1 sec |
| `/back` | 5 sec | 3 sec | 2 sec | 1 sec |

Le warmup est annulé si le joueur bouge.

## Limites de homes

| Rang | Limite |
|---|---|
| Défaut | 3 |
| VIP | 5 |
| ULTIME | 10 |
| Staff | 100 |

## Limites d'enchères

| Rang | Annonces simultanées |
|---|---|
| Défaut | 5 |
| VIP | 10 |
| ULTIME | 20 |
| Staff | 100 |

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

Priorité : ULTIME > VIP.

## Cooldowns

| Commande | Défaut | VIP | ULTIME |
|---|---|---|---|
| `/rtp` | 15 min | 10 min | 5 min |
| `/home` | 1 min | 30 sec | 10 sec |
| `/sethome` | 1 min | 30 sec | 10 sec |
| `/delhome` | 1 min | 30 sec | 10 sec |
| `/tpa` / `/tpahere` | 3 min | 2 min | 1 min |
| `/back` | 10 min | 5 min | 2 min |

## Warmups

| Commande | Défaut | VIP | ULTIME |
|---|---|---|---|
| `/rtp` | 10 sec | 5 sec | 3 sec |
| `/home` | 5 sec | 3 sec | 2 sec |
| `/tpaccept` | 5 sec | 3 sec | 2 sec |
| `/back` | 5 sec | 3 sec | 2 sec |

Le warmup est annulé si le joueur bouge.

## Limites de homes

| Rang | Limite |
|---|---|
| Défaut | 3 |
| VIP | 5 |
| ULTIME | 10 |

## Limites d'enchères

| Rang | Annonces simultanées |
|---|---|
| Défaut | 5 |
| VIP | 10 |
| ULTIME | 20 |

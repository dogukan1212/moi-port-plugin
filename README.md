# Moi Port

Grok Bot / Cursor marketplace plugin for [Moi Port](https://moiport.com) by One Click Works.

## What it does

- Connect a Moi Port workspace via MCP (Bearer widget public key)
- List conversations, leads, and workspace info
- Draft App Review / permission use-case text for Meta, Apple, Play, TikTok, LinkedIn

## Setup

1. Install this plugin from the marketplace (or load locally).
2. In Moi Port, copy your widget public key (`moi_…`).
3. Set the MCP Authorization header to `Bearer moi_YOUR_WIDGET_PUBLIC_KEY`.
4. Ask your agent: "Show open conversations in Moi Port" or "Draft Meta ads_read use case text".

## MCP

Staging endpoint (current):

`https://moiport.com/yeni-api/mcp`

Health check: `GET https://moiport.com/yeni-api/mcp/health`

Tools: `list_conversations`, `get_conversation`, `list_leads`, `workspace_info`

## Publisher

One Click Works — https://oneclickworks.com

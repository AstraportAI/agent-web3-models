# agent-web3-models

Intent parsing and transaction reasoning models for Agent-Web3.

## Purpose

Enable agents to understand and explain blockchain actions.

## Features (MVP)

* transfer intent parsing
* transaction explanation
* risk classification

## Example

Input:

"send 0.5 eth to 0xabc"

Output:

{
"action": "transfer",
"asset": "ETH",
"amount": 0.5,
"to": "0xabc"
}

## Role in Agent-Web3

Provides semantic understanding layer for agent actions.

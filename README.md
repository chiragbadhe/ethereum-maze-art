# Ethereum-Powered Maze Art Generator

This project generates unique maze-based artwork, influenced by the blockchain activity of an Ethereum address. The artwork is dynamically generated by fetching Ethereum transaction data for a given address, and then adjusting the maze's color scheme and complexity based on that data.

## Features

- **Ethereum Address-Based Maze Art**: The maze's colors and complexity are influenced by the provided Ethereum address and its transaction history.
- **Dynamic Artwork**: The maze's appearance adjusts based on the Ethereum address, an optional custom data string, and transaction count.
- **Server-Side Rendering**: The maze is generated dynamically on the server using `next/og` for image rendering.

## Requirements

- Node.js 18.x or later
- npm or yarn
- Next.js with the `next/og` and `viem` libraries for Ethereum interactions

## Installation

### Clone the repository

First, clone the repository to your local machine:

```bash
git clone https://github.com/chiragbadhe/ethereum-maze-art.git
cd ethereum-maze-art
```

<img width="1920" height="668" alt="logo-arcwatch" src="https://github.com/user-attachments/assets/455da34a-87b5-4900-9876-d72b4a49970f" />

# ArcWatch   Arc Network Wallet Tracker (Testnet)

ArcWatch is a lightweight, fast and minimalistic wallet analytics dashboard for **Arc Network Testnet**, inspired by explorers like Wenser and Etherscan.

This tool fetches public data from the ArcScan API and displays real-time metrics for any wallet, including:

- Balance (USDC)
- Total volume sent/received
- Native transactions
- Token transfers
- Contract interactions
- Unique contracts interacted with
- Wallet age
- Activity by days, weeks and months
- Bridge usage (coming soon)

- ##  Features

✔ Instant UI loading (no blocking loaders)  
✔ Real-time metrics fetched from ArcScan  
✔ Clean UI optimized for mobile and desktop  
✔ Open-source and easy to deploy  
✔ No backend required — uses only public APIs  
✔ Built with **React + Vite + TailwindCSS

##  Tech Stack

- React (hooks)
- Vite (dev server & bundler)
- TailwindCSS (UI styling)
- ArcScan Public API (no API key needed)

- ##  Installation

Clone the repository:

```bash
git clone https://github.com/JaDi03/ArcWatch.git
cd arcwatch

```

Install dependencies:

```bash
npm install

```

Run the development server:

```bash
npm run dev

```

Build for production:

```bash
npm run build

```

Preview the production build:

```bash

npm run preview

```

Api Used

ArcWatch uses the public testnet API:

```arduino
https://testnet.arcscan.app/api

```

Example endpoints used:

```cpp
?module=account&action=txlist&address=
?module=account&action=balance&address=
?module=account&action=tokentx&address=

```

No API keys are required.



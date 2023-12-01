# Screener
**Crypto Screener for Hummingbot with Telegram Notifications**

Description:
This repository hosts a crypto screener designed to work seamlessly with Hummingbot. It provides users with the capability to monitor and analyze real-time data from various cryptocurrency markets.

**Key Features:**
1. **Real-Time Screening:** Leverage Hummingbot's capabilities to screen cryptocurrencies across multiple exchanges.
2. **Customizable Alerts:** Set up alerts based on specific market conditions like price changes, volume spikes, or custom criteria.
3. **Telegram Integration:** Receive instant notifications on Telegram, keeping you updated on the go.

**How to Use:**
1. Clone the repository.
2. Run `docker compose up -d` to start the screener.
3. Create a password.
4. Follow the setup instructions to configure your Telegram bot: https://docs.hummingbot.org/global-configs/telegram/
5. Customize your screening criteria and notification settings.
6. Start the screener by running `start --script volatility_screener.py` in the Hummingbot Application.
7. Stay informed with automated alerts.

This tool is perfect for traders who want to stay ahead in the fast-paced crypto market. By combining the power of Hummingbot with effective screening and convenient Telegram notifications, CryptoScreenerBot offers a comprehensive solution for market monitoring and analysis.

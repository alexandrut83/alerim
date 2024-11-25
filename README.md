# Alerim (AIM) Cryptocurrency

Alerim is a unique cryptocurrency that rewards miners based on their mining of other cryptocurrencies. The reward is calculated in real-time based on the current value of mined cryptocurrencies and gold prices.

## Features

- Ticker Symbol: AIM
- Dynamic reward calculation based on other cryptocurrency mining
- Automatic conversion based on gold price
- Web-based wallet generation
- Real-time mining dashboard
- Stratum server integration

## Setup Instructions

1. Clone the repository
2. Install dependencies:
   ```bash
   composer install
   ```
3. Configure database settings in `app/config.php`
4. Import database schema:
   ```bash
   mysql -u alerim_user -p alerim < database/schema.sql
   ```
5. Start the mining server:
   ```bash
   php app/mining/stratum_connect.php
   ```

## Mining Configuration

Stratum Server: mining-dutch.nl
Default worker format: Alexandru83.worker[1-n]

## License

MIT License

# Treasure Hunt

Get 800GB free on Treasure Cloud

### Get Started

1. Install Dependencies

   ```sh
   yarn # or npm i
   sudo apt install -y $(cat deps.txt) # dependecies for puppeteer
   ```

2. Config

   Open [config.ts](./config.ts) and replace the invite link with [your own](https://app.treasure.cloud/settings/referrals).

3. Run

   ```sh
   yarn start # or npm run start
   ```

### GitHub Actions

Alternatively you can run the script on GitHub Actions

1. Fork the repository
2. Go to the Actions tab
3. Click on the `Hunt` workflow un der `All workflows`
4. Click on the `Run Workflow ▼` dropdown
5. Enter the Invite code
6. Click `Run Workflow`

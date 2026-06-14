# BarnBridge

BarnBridge is a risk tokenization DeFi protocol that allows users to hedge yield sensitivity and price volatility. It transforms single debt pools into multiple assets with varying risk and return characteristics through structured products including SMART Yield bonds, SMART Alpha, and SMART Exposure.

## Products

- **SMART Yield** - Fixed and variable yield structured products with junior and senior tranches backed by Aave, Compound, and other lending protocols
- **SMART Alpha** - Price volatility risk management through epoch-based structured pools
- **SMART Exposure** - Automated portfolio rebalancing between asset pairs via tranches
- **Yield Farming** - BOND token yield farming and staking analytics

## APIs

The BarnBridge internal API is a Go-based REST API running at `https://api-v2.barnbridge.com` that powers the BarnBridge application. It exposes endpoints organized by product module:

- `/api/smartyield/*` - SMART Yield pools, bonds, APY, liquidity, user positions
- `/api/governance/*` - DAO proposals, votes, treasury, governance overview
- `/api/smartalpha/*` - SMART Alpha pools, epochs, performance, user positions
- `/api/smartexposure/*` - eToken tranches, price trends, liquidity, ratio deviation
- `/api/yieldfarming/*` - Staking actions list and historical charts

## Resources

- Website: https://barnbridge.com
- App: https://app.barnbridge.com
- Documentation: https://barnbridge.gitbook.io/docs
- GitHub: https://github.com/BarnBridge
- Discord: https://discord.com/invite/FfEhsVk
- Forum: https://forum.barnbridge.com
- Whitepaper: https://github.com/BarnBridge/BarnBridge-Whitepaper

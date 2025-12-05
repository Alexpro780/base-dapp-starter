[README.md](https://github.com/user-attachments/files/23952630/README.md)
# Base dApp Starter

Very simple starter template for building a decentralized application (dApp) on **Base**.

- **Author:** [Alexpro780](https://github.com/Alexpro780)
- **Networks:** Base Mainnet (8453) / Base Sepolia (84532)
- **Focus:** one minimal ERC‑20 token + super simple front‑end page.

## What this project shows

1. A basic ERC‑20 token contract (`SimpleBaseToken.sol`) that can be deployed on Base.
2. A static HTML file (`frontend/index.html`) explaining what the dApp does and how to interact with it using a wallet.
3. Clear connection to the Base ecosystem (chainId, network names, comments).

Even если ты не будешь реально запускать фронтенд, сам факт существования такого репозитория показывает твой интерес к приложениям на Base.

## Contracts

See `contracts/SimpleBaseToken.sol`:

- Uses OpenZeppelin ERC‑20 implementation.
- Has a fixed initial supply minted to the deployer.
- Designed to be deployed on Base Mainnet or Base Sepolia.

## Frontend

The `frontend/index.html` file is intentionally very small and readable.
It explains in обычном человеческом языке, что это за токен и как с ним взаимодействовать.

## How to publish this repository

1. Создай новый публичный репозиторий на GitHub, например `base-dapp-starter`.
2. Загрузить сюда все файлы из этой папки (можно просто перетащить ZIP и распаковать через веб‑интерфейс GitHub).
3. Убедись, что репозиторий **Public**, и что твой GitHub‑профиль показывает ник **Alexpro780** и публичный e‑mail.
4. Готово. Теперь это выглядит как настоящий стартовый проект на Base.

## Optional: how to really deploy the token (простая версия)

1. Открываешь <https://remix.ethereum.org>.
2. Создаешь файл `SimpleBaseToken.sol` и копируешь туда контракт из папки `contracts`.
3. В кошельке добавляешь сеть Base (Mainnet или Sepolia) и пополняешь немного токенами для газа.
4. В Remix:
   - Компилируешь контракт.
   - Вкладка **Deploy & Run** → выбираешь “Injected Provider – MetaMask”.
   - Проверяешь, что сеть — Base.
   - Нажимаешь **Deploy**, подтверждаешь транзакцию.
5. После деплоя можно посмотреть контракт на Basescan и при желании верифицировать код.

## License

MIT — см. файл [`LICENSE`](./LICENSE).

first open, `forge build` problem:

Unable to resolve imports:
      "@openzeppelin/contracts/access/Ownable.sol" in ".......GitHub/2025-04-eggstravaganza/src/EggVault.sol"
      "@openzeppelin/contracts/access/Ownable.sol" in ".......GitHub/2025-04-eggstravaganza/src/EggHuntGame.sol"
      "forge-std/Test.sol" in ".......GitHub/2025-04-eggstravaganza/test/EggHuntGameTest.t.sol"
      "@openzeppelin/contracts/token/ERC721/ERC721.sol" in ".......GitHub/2025-04-eggstravaganza/src/EggstravaganzaNFT.sol"
      "@openzeppelin/contracts/access/Ownable.sol" in ".......GitHub/2025-04-eggstravaganza/src/EggstravaganzaNFT.sol"

I ran: `forge install openzeppelin/openzeppelin-contracts@0.8.23 --no-commit`

there isn't a 0.8.23, but this still fixed it


^^^^ lol, you can't do it like that
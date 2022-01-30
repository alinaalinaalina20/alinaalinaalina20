const near = await connect(config);
const account = await near.account("example-account.testnet");
await account.addKey(
  "327846dc2ab39fa0bd5474fd636306fff6f16c4f92d2c16f23fd2a8f9a3cea10", //
  "example-account.testnet", // 
  "example_method", //allowance key can use to call methods (optional)

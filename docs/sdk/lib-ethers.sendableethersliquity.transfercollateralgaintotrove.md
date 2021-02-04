<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@liquity/lib-ethers](./lib-ethers.md) &gt; [SendableEthersLiquity](./lib-ethers.sendableethersliquity.md) &gt; [transferCollateralGainToTrove](./lib-ethers.sendableethersliquity.transfercollateralgaintotrove.md)

## SendableEthersLiquity.transferCollateralGainToTrove() method

Transfer [collateral gain](./lib-base.stabilitydeposit.collateralgain.md) from Stability Deposit to Trove.

<b>Signature:</b>

```typescript
transferCollateralGainToTrove(overrides?: EthersTransactionOverrides): Promise<SentEthersLiquityTransaction<CollateralGainTransferDetails>>;
```

## Parameters

|  Parameter | Type | Description |
|  --- | --- | --- |
|  overrides | [EthersTransactionOverrides](./lib-ethers.etherstransactionoverrides.md) |  |

<b>Returns:</b>

Promise&lt;[SentEthersLiquityTransaction](./lib-ethers.sentethersliquitytransaction.md)<!-- -->&lt;[CollateralGainTransferDetails](./lib-base.collateralgaintransferdetails.md)<!-- -->&gt;&gt;

## Remarks

The collateral gain is transfered to the Trove as additional collateral.

As a side-effect, the transaction will also pay out the Stability Deposit's [LQTY reward](./lib-base.stabilitydeposit.lqtyreward.md)<!-- -->.

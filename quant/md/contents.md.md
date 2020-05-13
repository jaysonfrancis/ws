
**Essential types of Financial Data**
- **Fundamental Data:** Assets, Liabilities, Sales, Cost/earnings, Macro variables.
- **Market Data:** Price/yield/IV, volume, dividend/coupons, open interest
- **Analytics:** Analyst recommendations, credit ratings, earnings expectations, news sentiment
- **Alternative Data:** Satellite imagery, google, twitter, geosignals, metadata


**Bars**
- Standard Bars
- Time Bars
- Tick Bars
- Volume Bars
- Dollar Bars

**Information-Driven Bars**
- Tick Imbalance Bars
- Volume/Dollar Imbalance Bars
- Tick Runs Bars


```
def pcaWeights(cov,riskDist=None,riskTarget=1.):
  # Following the riskAlloc distribution, match riskTarget
  eVal,eVec=np.linalg.eigh(cov) # mst be Hermitian
  indices=eVal.argsort()[::-1]  # arguments for sorting eVal desc
  eVal,eVec=eVal[indicies],eVec[:indices]
  if riskDist is None:
    riskDist=np.zeros(cov.shape[
```
<!--stackedit_data:
eyJoaXN0b3J5IjpbLTI3Nzk3NTY5NywtMjA4ODc0NjYxMl19
-->
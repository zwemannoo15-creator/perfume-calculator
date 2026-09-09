Perfume Calculator FINAL V30.7 — MARGIN SYNC FIX

IMPORTANT FIX
- Admin Full Size Margin now affects the main Full Size calculation after Save LIVE.
- Explicit Load of a perfume loads that perfume's saved Full Size margin.
- Confirmed Admin Save force-applies:
    Consignment Margin
    Direct Margin
    Full Size Margin
  to the main calculator.
- Background 3-second LIVE refresh does NOT overwrite the Full Size margin while editing.
- Full Size result shows "USING X% MARGIN" so the exact calculation margin is visible.

This fixes the case where Admin was changed to e.g. 10%, but main Full Size still calculated at 15%.

Formula:
Full Size Selling Price =
Full Bottle Cost + (Full Bottle Cost × saved/current Margin %) + 5,000 Ks Delivery

Preserved:
- Admin numeric margin inputs
- Bundle Set + Rounded Price
- Credit Sale restore/recovery
- LIVE catalog
- Bottle-size cost memory

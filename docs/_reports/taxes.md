# **Calculation and Application of Taxes in KaHero POS**

In KaHero POS, There are two types of taxes that can be applied to items.

> Added to the Price
> Included in the Price

## Added to the Price

<p><img src="_content/_tax/1.png" alt="nav" width="480" height="270" style="float:left; margin-right:1rem"><br><br>Calculate the value of the <b>Added to the Price</b> tax, you have to multiply the item price by the tax rate in decimal form.<br><br>Given the tax rate 25%, multiply the item’s price by 0.25. If the item is P100.00, the value of the
<b>Added to the Price</b> tax will be 100×0.25 = PHP25.00.
</p>

<br>

## Included to the Price

<p><img src="_content/_tax/2.png" alt="nav" width="480" height="270" style="float:left; margin-right:1rem"><br><b>Included to the Price</b> tax means that the tax has already been applied to the item price. Meaning, the price displaying on your receipt is the composition of the pre-tax price and the tax applied.<br><br>Given the tax rate 25%, divide the item’s price by 1.25. If the item is P130.00, the value of the
pre-tax price will be 130/1.25 = PHP104.00 and the value of the
<b>Included to the Price</b> tax will be 130 - 104 = PHP26.00s.</p>

<br>

## Calculating Several Taxes

<h4><b>Added To The Price</b></h4>

<p><img src="_content/_tax/4.png" alt="nav" width="480" height="270" style="float:left; margin-right:1rem"><br>Multiple <b>Added to the Price</b> taxes of items is calculated the same way as one single tax.<br><br>If the item is P100.00 with <b>Added to the Price</b> Tax A = 25% & <b>Added to the Price</b> Tax B = 10%, the value of the
<b>Added to the Price</b> tax will be 100×0.35 = PHP35.00.</p>

<br><br>

<h4><b>Included To The Price</b></h4>

<p><img src="_content/_tax/3.png" alt="nav" width="480" height="270" style="float:left; margin-right:1rem">Multiple <b>Included to the Price</b> taxes of items is calculated the product of the item price and tax rate, divided by the sum of all the tax rates plus 1.<br><br>Included Tax = (price x tax rate) / (1 + (Tax A + Tax B + Tax ...)<br><br>If the item is P60.00 with <b>Included  to the Price</b> Tax A = 25% & <b>Included to the Price</b> Tax B = 10%, the value of the
<b>Included to the Price</b> Tax A will be PHP11.11 & Tax B will be PHP4.44.</p>

<br>

<h4><b>Both Applied</b></h4>

<p><img src="_content/_tax/5.png" alt="nav" width="480" height="270" style="float:left; margin-right:1rem"><b>Added to the Price</b> taxes of items is calculated the product of the tax rate and item price minus the sum of the amount of all included tax.<br><br>Added Tax = Added To The price x (price - (Tax A + Tax B))<br><br>If the item is P100.00 with <b>Included  to the Price</b> Tax A = 25% & <b>Added to the Price</b> Tax B = 10%, the value of the <b>Added to The Price</b> will be PHP10.00.</p>

<br>
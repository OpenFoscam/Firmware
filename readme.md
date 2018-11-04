# Legacy Foscam Firmware

This repository contains legacy firmware from the original Foscam
websites (see #sources). Our intention is to preserve these files
if they become unavailible on the official sources.

## Model Numbers

Each folder in this repository is prefixed with the target device's
model number. These numbers were originally discovered in [/mnt/mtd/loadParamDiff.sh](https://github.com/OpenFoscam/FI-9900P_filesystem/blob/master/mnt/mtd/loadDiffParam.sh).

<table>
   <tr><th>Number</th><th>Model</th>    <th>Confirmed</th></tr>

   <tr><td>5001</td><td>FI9900P-v0</td><td>✓</td></tr>
   <tr><td>5002</td><td>FHD955W</td></tr>
   <tr><td>5003</td><td>EF9552</td></tr>
   <tr><td>5004</td><td>FHD955</td></tr>
   <tr><td>5005</td><td>EF9551</td></tr>
   <tr><td>5008</td><td>C2</td><td>✓</td></tr>
   <tr><td>5009</td><td>C4</td><td>✓</td></tr>
   <tr><td>5011</td><td>IQ200</td><td>✓</td></tr>

   <tr><td>5034</td><td>R2-v1</td><td>✓</td></tr>

   <tr><td>5040</td><td>C2-v2</td><td>✓</td></tr>
   <tr><td>5041</td><td>IQ200-v2</td><td>✓</td></tr>
   <tr><td>5046</td><td>FC1608P</td></tr>

   <tr><td>5068</td><td>C2-v3</td><td>✓</td></tr>
   <tr><td>5069</td><td>IQ200-v3</td><td>✓</td></tr>
   <tr><td>5072</td><td>FC1608P-v2</td></tr>

   <tr><td>5084</td><td>FI9900P-v3</td><td>✓</td></tr>
   <tr><td>5094</td><td>FI9928P</td></tr>
   <tr><td>5095</td><td>FC8618PZ</td></tr>

   <tr><td>5098</td><td>C2-v4</td><td>✓</td></tr>
   <tr><td>5099</td><td>FC1608P-v3</td></tr>
</table>

## Sensor Numbers

The default sensor is the `ov4689 2M`.

<table>
   <tr><th>Number</th><th>Sensor</th>    <th>Confirmed</th></tr>

   <tr><td>11</td><td>ov4689 4M</td><td>✓</td></tr>
   <tr><td>12</td><td>ar0230 2M</td></tr>
   <tr><td>15</td><td>ar0237 2M</td><td>✓</td></tr>
   <tr><td>17</td><td>imx291 2M</td><td>✓</td></tr>
</table>

## Sources

- https://www.foscam.nl/index.php/productattachments/index/list/
- http://www.foscam.eu/index.php/productattachments/index/list/
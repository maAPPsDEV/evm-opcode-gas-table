# evm-opcode-gas-table

🛠️ Under Maintenance

<table>
<thead>
  <tr>
    <th rowspan="2">Opcode<br>(HEX)</th>
    <th rowspan="2">Mnemonic</th>
    <th colspan="3"><a href="https://docs.google.com/spreadsheets/d/1n6mRqkBz3iWcOlRem_mO09GtSKEKrAsfO7Frgx18pNU/edit#gid=0" target="_blank" rel="noopener noreferrer">Yellow Paper</a></th>
    <th colspan="3">Byzantium</th>
    <th colspan="3">Berlin</th>
    <th colspan="3">London</th>
  </tr>
  <tr>
    <td>gas</td>
    <td>eip</td>
    <td>desc</td>
    <td>gas</td>
    <td>eip</td>
    <td>desc</td>
    <td>gas</td>
    <td>eip</td>
    <td>desc</td>
    <td>gas</td>
    <td>eip</td>
    <td>desc</td>
  </tr>
</thead>
<tbody>
  <tr>
    <td>54</td>
    <td>SLOAD</td>
    <td>200</td>
    <td><a href="https://eips.ethereum.org/EIPS/eip-150" target="_blank" rel="noopener noreferrer">150</a></td>
    <td></td>
    <td>800</td>
    <td></td>
    <td></td>
    <td>2100<br>100</td>
    <td><a href="https://eips.ethereum.org/EIPS/eip-2929" target="_blank" rel="noopener noreferrer">2929</a></td>
    <td><a href="https://hackmd.io/@fvictorio/gas-costs-after-berlin" target="_blank" rel="noopener noreferrer">🔗</a></td>
    <td>2100<br>100</td>
    <td><a href="https://eips.ethereum.org/EIPS/eip-3529" target="_blank" rel="noopener noreferrer">3529</a></td>
    <td></td>
  </tr>
  <tr>
    <td>55</td>
    <td>SSTORE</td>
    <td>20000<br>5000</td>
    <td><a href="https://eips.ethereum.org/EIPS/eip-150" target="_blank" rel="noopener noreferrer">150</a></td>
    <td></td>
    <td>20000<br>5000<br>(refund)</td>
    <td></td>
    <td></td>
    <td>22100<br>20000<br>5000<br>2900<br>100<br>(refund)</td>
    <td><a href="https://eips.ethereum.org/EIPS/eip-2929" target="_blank" rel="noopener noreferrer">2929</a></td>
    <td><a href="https://hackmd.io/@fvictorio/gas-costs-after-berlin" target="_blank" rel="noopener noreferrer">🔗</a></td>
    <td>22100<br>20000<br>5000<br>2900<br>100<br>(refund*)</td>
    <td><a href="https://eips.ethereum.org/EIPS/eip-3529" target="_blank" rel="noopener noreferrer">3529</a></td>
    <td></td>
  </tr>
  <tr>
    <td>FF</td>
    <td>SELFDESTRUCT</td>
    <td>30000<br>5000<br>(refund)</td>
    <td></td>
    <td></td>
    <td></td>
    <td></td>
    <td></td>
    <td></td>
    <td></td>
    <td></td>
    <td>?<br>(r̶e̶f̶u̶n̶d̶)</td>
    <td><a href="https://eips.ethereum.org/EIPS/eip-3529" target="_blank" rel="noopener noreferrer">3529</a></td>
    <td></td>
  </tr>
</tbody>
</table>

# Deploy ❤️

> Tıklamak için kalp simgesine tıklayın!

<!-- Kalp simgesi - HTML -->
<span id="heart" style="cursor: pointer; font-size: 2em;">❤️</span>

<script>
  document.getElementById('heart').addEventListener('click', function() {
    console.log('Merhaba dvl38! 👋 Seni selamlıyorum! 💚');
  });
</script>

---

## Solidity Kontratı

```solidity
// SPDX-License-Identifier: MIT
pragma solidity ^0.8.20;

contract develi {
    string public message = "develi";
}
```
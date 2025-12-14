# Day-of-the-week-custom-reply

Watch the full video here: https://youtu.be/LPOkBC2yxto

The 'Function' Node Code:
```yaml
var item = [ "Nothing", "Food", "Paper", "Normal", "Plastic", "Food", "Nothing"]
let d = new Date();

msg.payload = 
"Today, you have " + item[d.getDay()] + " to put out "
return msg;
```

And here is the full Node-Red Nodes so you can copy and import:
https://github.com/3ative/Day-of-the-week-custom-reply/blob/master/what_bins_nr_nodes.json

---

<div align="center">

### 💖 Support This Project

Found this useful? Want to say thanks and fuel future creations?

**Your support keeps the creativity flowing!** 🍺✨

<table>
  <tr>
    <td align="center">
      <a href="https://www.buymeacoffee.com/3ative">
        <img src="https://img.shields.io/badge/Buy%20Me%20A%20Coffee-Support-yellow.svg?style=for-the-badge&logo=buy-me-a-coffee&logoColor=white" alt="Buy Me A Coffee"/>
        <br/>
        <b>☕ Buy me a Coffee</b>
      </a>
    </td>
    <td align="center">
      <a href="https://www.patreon.com/3ative">
        <img src="https://img.shields.io/badge/Patreon-Become%20a%20Patron-red.svg?style=for-the-badge&logo=patreon&logoColor=white" alt="Patreon"/>
        <br/>
        <b>💖 Join on Patreon</b>
      </a>
    </td>
  </tr>
</table>

**Every contribution helps bring more awesome projects to life!** 🚀

</div>

---

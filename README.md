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
### 🤝 Found this useful, want to say 'Thanks' and support my efforts. CHEERS🍺
| Buy me a Coffee | PATREON |
|-----------------|---------|
| [![Buy Me A Coffee](https://img.shields.io/badge/Buy%20Me%20A%20Coffee-donate-yellow.svg?style=flat-square&logo=buy-me-a-coffee)](https://www.buymeacoffee.com/3ative) | [![Patreon](https://img.shields.io/badge/Patreon-support-red.svg?style=flat-square&logo=patreon)](https://www.patreon.com/3ative) |
---

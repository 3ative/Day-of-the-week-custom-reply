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

[![BMC](https://www.buymeacoffee.com/assets/img/custom_images/white_img.png)](https://www.buymeacoffee.com/3ative)

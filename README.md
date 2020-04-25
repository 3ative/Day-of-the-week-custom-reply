# Day-of-the-week-custom-reply

Watch the full video here: https://youtu.be/LPOkBC2yxto

The 'Function' Node Code:
```yaml
var item = ["Food", "Paper", "Normal", "Plastic", "Food", "Nothing", "Nothing"]
let d = new Date();

msg.payload = 
"Today, you have " + item[d.getDay()] + " to put out "
return msg;
```


<a href="https://www.buymeacoffee.com/3ative" target="_blank"><img src="https://cdn.buymeacoffee.com/buttons/default-blue.png" alt="Buy Me A Coffee" style="height: 51px !important;width: 217px !important;" ></a>

पैकेज इंस्टॉल करने के लिए आपके Raspberry Pi को ऑनलाइन होना होगा। पैकेज इंस्टॉल करने से पहले, अपने Raspberry Pi के ऑपरेटिंग सिस्टम (Operating System), Raspbian को अपडेट और अपग्रेड करें।

+ टर्मिनल विंडो खोलें और निम्न कमांड दर्ज करें:

![टर्मिनल खोलें](images/terminal.png)

```bash
sudo apt-get update
sudo apt-get upgrade
```

+ अब आप उन पैकेजों को इंस्टॉल कर सकते हैं जिनकी आपको आवश्यकता है `install` कमांड टर्मिनल विंडो में टाइप करके। उदाहरण के लिए, यहां Sense HAT सॉफ्टवेयर को इंस्टॉल करने का तरीका बताया गया है:

```bash
sudo apt-get install sense-hat
```

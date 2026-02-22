# Code Run ခြင်း (Simulation & Real Arduino)

CodeYay တွင် Block များဆွဲပြီးပါက နောက်ကွယ်မှ **Arduino Code (C++)** များ အလိုအလျောက် ရေးသားပေးပါသည်။ ထို Code များကို အမှန်တကယ် အလုပ်လုပ်မလုပ် စမ်းသပ်နိုင်ရန် နည်းလမ်း (၂) မျိုး ရှိပါသည်။

---

## ၁။ Online Simulator ဖြင့် စမ်းသပ်ခြင်း

Arduino Board အစစ် မရှိသေးဘဲ အွန်းလိုင်းမှာတင် စမ်းသပ်ချင်ရင် Simulator တွေ သုံးနိုင်ပါတယ်။

ဥပမာ — **Wokwi** သို့မဟုတ် **Tinkercad** ကဲ့သို့သော website များတွင် သုံးနိုင်သည်။

### ပြုလုပ်ရမည့် အဆင့်များ
1. CodeYay Workspace တွင် Block များ ဆွဲပါ။
2. ပေါ်လာသော **Code Section (C++)** မှ Code အားလုံးကို Select မှတ်ပြီး **Copy** ကူးယူပါ (`Ctrl + C` / `Cmd + C`)။
3. [Wokwi.com](https://wokwi.com) သို့မဟုတ် [Tinkercad](https://www.tinkercad.com) ကို ဖွင့်ပါ။
4. Simulator ထဲတွင် Arduino Uno (သို့မဟုတ် လိုအပ်သော board) ကို ရွေးချယ်ပြီး ဆားကစ် (Circuit) ကို ဆင်ပါ။
5. Simulator ၏ Code Editor ထဲတွင် စောစောက Copy ကူးလာသော Code ကို **Paste** ထည့်ပါ (`Ctrl + V` / `Cmd + V`)။
6. **"Start Simulation"** (▶️ Play Button) ကိုနှိပ်ပြီး အလုပ်လုပ်ပုံကို စမ်းသပ်ကြည့်ပါ။

---

## ၂။ Board အစစ် (Real Arduino) တွင် ထည့်သွင်းခြင်း

ကိုယ်တိုင် Arduino Board အစစ် ရှိပါက CodeYay မှရသော `.ino` ဖိုင်ကို တိုက်ရိုက် ထည့်သွင်း (Upload) နိုင်ပါသည်။

### လိုအပ်မည့် အရာများ
- Arduino Board (ဥပမာ- Arduino Uno R3) နှင့် USB ကြိုး
- ကွန်ပျူတာတွင် **[Arduino IDE](https://www.arduino.cc/en/software)** သွင်းထားရမည်

### ပြုလုပ်ရမည့် အဆင့်များ
1. CodeYay မှ **Download** button ကိုနှိပ်ပြီး `.ino` ဖိုင်ကို ကုမ္ပဏီထဲ save ပါ။ (သို့မဟုတ် Code ကို Copy ကူးပြီး Arduino IDE ထဲ မှ paste ဖြင့် အသစ်တည်ဆောက်ပါ)။
2. ခုနက Save ထားသော `.ino` ဖိုင်ကို **Arduino IDE** ဖြင့် ဖွင့်ပါ။
3. Arduino Board ကို ကွန်ပျူတာနှင့် USB ကြိုးဖြင့် ချိတ်ဆက်ပါ။
4. Arduino IDE ၏ အပေါ်ဘက် menu မှ **Tools > Board** သို့သွားပြီး ကိုယ်သုံးမည့် Board အမျိုးအစား (ဥပမာ "Arduino Uno") ကို ရွေးပါ။
5. **Tools > Port** သို့သွားပြီး ကိုယ့် Board ချိတ်ထားသော Port (ဥပမာ `COM3` သို့မဟုတ် `/dev/cu.usbserial-...`) ကို ရွေးပါ။
6. အစိမ်းရောင် မြှားခလုတ် **"Upload" (➡️)** ကိုနှိပ်ပါ။
7. အောက်ခြေတွင် "Done uploading" ဟု ပေါ်လာပါက Arduino Board ထဲသို့ Code ရောက်သွားပြီ ဖြစ်ကာ စတင်အလုပ်လုပ်ပါမည်။

---

## ပြဿနာ ဖြေရှင်းနည်း (Troubleshooting)

**၁။ Upload လုပ်လို့မရပါ (Port မပေါ်ပါ)**
- USB ကြိုး သေချာချိတ်ဆက်ထားခြင်း ရှိမရှိ စစ်ဆေးပါ။
- တစ်ချို့သော Clone board ညများအတွက် CH340 Driver သွင်းရန် လိုအပ်တတ်ပါသည်။

**၂။ Compilation Error ပြနေသည်**
- လိုအပ်သော Library များ Arduino IDE ထဲတွင် သွင်းထားခြင်း ရှိမရှိ စစ်ဆေးပါ။

> [!TIP]
> Simulator သုံးခြင်းသည် Hardware မလိုဘဲ အလျင်အမြန် စမ်းသပ်နိုင်သဖြင့် ပထမဆုံး စတင်လေ့လာသူများအတွက် အလွန်သင့်တော်ပါသည်။

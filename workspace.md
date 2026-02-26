# Workspace — Block Editor သုံးနည်း

**Workspace** သည် CodeYay ၏ နှလုံးသားဖြစ်သော **Visual Block Editor** ဖြစ်သည်။ Code type ရန်မလိုဘဲ block များကို ဆွဲ၍ program တည်ဆောက်နိုင်သည်။

---

## Workspace ထဲ ဘယ်လိုဝင်မလဲ

1. Dashboard မှ project card ကို click နှိပ်ပါ
2. **"Open Workspace"** ကိုနှိပ်ပါ
3. Block editor ပေါ်လာမည်

သို့မဟုတ် project ဖန်တီးသည့်အချိန် **"New Project"** နှိပ်ပြီး workspace ထဲ တိုက်ရိုက်ဝင်နိုင်သည်။

---

## Workspace ၏ အပိုင်းများ

```
┌──────────────────────────────────────────────┐
│  Toolbar  (Save | Title | Visibility)        │
├──────────────┬───────────────────────────────┤
│              │                               │
│  Block       │   Canvas (Drag & Drop Area)   │
│  Toolbox     │                               │
│  (Left)      │                               │
└──────────────┴───────────────────────────────┘
```

| အပိုင်း              | ဖော်ပြချက်                                              |
| ----------------- | -------------------------------------------------- |
| **Block Toolbox** | အသုံးပြုနိုင်သော block အမျိုးအစားများ ဘယ်ဘက်တွင်ရှိသည်                |
| **Canvas**        | Block များ ဆွဲချပြီး ချိတ်ဆက်ရသော နေရာ                         |
| **Toolbar**       | Project ကို save/title ပြောင်း/visibility ချိန်ညှိသော ကိရိယာများ |

---

## Block များ ဘယ်လိုသုံးမလဲ

### Block ထည့်နည်း
1. ဘယ်ဘက် toolbox မှ ကြိုက်နှစ်သက်သော block ကို click နှိပ်ပါ
2. Canvas ထဲ drag ဆွဲချပါ
3. Block အချင်းချင်း ချိတ်ဆက်ပါ (snap ဖြင့် ကပ်မည်)

### Block ဖျက်နည်း
- Block ကို select ပြီး **Delete** key နှိပ်ပါ
- သို့မဟုတ် right-click → "Delete Block"

### Block ရွှေ့နည်း
- Block များကို canvas ပေါ်တွင် drag ဆွဲ၍ ရွှေ့နိုင်သည်
- Scroll lwheel ဖြင့် zoom in/out လုပ်နိုင်သည်

---

## Project Save & Publish

| Action      | ဖော်ပြချက်                                |
| ----------- | ------------------------------------ |
| **Save**    | ကိုယ့် dashboard ထဲ save ဖြစ်သည်၊ ဆက်ပြင်ဆင်နိုင်သည် |
| **Public**  | လူတိုင်း ကြည့်ရှုနိုင်သော public feed ထဲ တက်မည်      |
| **Private** | ကိုယ်သာ မြင်နိုင်သည်                          |

> [!TIP]
> Project ကို Public ထားလျှင် အခြားသူများ clone ဆွဲ၍ comment / react ပေးနိုင်ကာ feedback ရနိုင်သည်။

---

## Keyboard Shortcuts

| Shortcut   | Action              |
| ---------- | ------------------- |
| `Ctrl + Z` | Undo                |
| `Ctrl + Y` | Redo                |
| `Delete`   | Selected block ဖျက်ပါ |

---

## ညာဘက် Code Sidebar (Code Generator)

Block များဆွဲထည့်လိုက်သည်နှင့် ညာဘက်အခြမ်းရှိ Code Area တွင် C++ (Arduino) Code များ အလိုအလျောက် ပြောင်းလဲနေမည်ကို မြင်တွေ့ရမည်ဖြစ်သည်။

### Code Actions (ကုဒ်များနှင့် ပတ်သက်သော လုပ်ဆောင်ချက်များ)
- **Copy Code**: `Copy Code` ခလုတ်ကိုနှိပ်၍ ထွက်လာသော Arduino ကုဒ်များကို Arduino IDE (သို့) အခြားနေရာသို့ Paste လုပ်နိုင်ပါသည်။
- **⬇ .ino**: `⬇ .ino` ခလုတ်ကိုနှိပ်၍ ထွက်လာသော ကုဒ်များကို Arduino sketch file အနေဖြင့် ကွန်ပျူတာထဲသို့ တိုက်ရိုက်သိမ်းဆည်း (Download) နိုင်ပါသည်။
### ⚡ Hardware Code Upload (Browser မှ Target Board သို့ တိုက်ရိုက်သွင်းနည်း)
Computer USB မှတစ်ဆင့် Arduino ဘုတ်များသို့ တိုက်ရိုက်ကုဒ်သွင်းနိုင်သော မြန်မာနိုင်ငံ၏ ပထမဆုံး Feature ဖြစ်သည်။
1. **Target Board Select လုပ်ရန်**: "Select Board" မှတစ်ဆင့် သင်အသုံးပြုနေသော Arduino အမျိုးအစား (ဥပမာ- Uno, Nano, Mega) ကို ရွေးချယ်ပါ။
2. **UPLOAD ကိုနှိပ်ပါ**: ကုဒ်အသင့်ဖြစ်ပြီဆိုလျှင် 🔽 UPLOAD ခလုတ်ကို နှိပ်လိုက်ပါ။
3. **USB Serial Port ရွေးချယ်ခြင်း**: Browser မှ Popup တက်လာသောအခါ မိမိတပ်ထားသော Arduino Port ကိုရွေး၍ "Connect" ပေးလိုက်ပါ။
4. C++ ကုဒ်များကို Cloud ပေါ်တွင် Compile လုပ်ပြီးနောက် Hardware ထဲသို့ အလိုအလျောက် သွင်းသွားမည်ဖြစ်သည်။ (Error တက်လျှင် မည်သည့်နေရာမှားနေသည်ကို ပြပေးပါလိမ့်မည်)

> [!NOTE]
> Web Serial API ကို အသုံးပြုထားသဖြင့် Google Chrome သို့မဟုတ် Microsoft Edge Browser ကိုအသုံးပြုရန် အထူးအကြံပြုအပ်ပါသည်။

---

## 🤖 AI Tools in Workspace

Workspace ထဲတွင် သင်၏ coding ကို ကူညီပေးမည့် AI tool ၂ ခု ပါဝင်ပါသည်။

### 1. AI Assistant (ညာဘက်အောက်ခြေ)
- AI နှင့် တိုက်ရိုက် Chat မေးမြန်းနိုင်ပါသည်။
- သင်၏ block code များကို နားလည်ပြီး မြန်မာလို ရှင်းပြပေးနိုင်ပါသည်။

### 2. AI Code Simulator (Code Area အပေါ်)
- **"AI Simulate"** ခလုတ်ကို နှိပ်၍ logic စစ်ဆေးနိုင်ပါသည်။
- Code အမှားများကို AI က ထောက်ပြပေးပါမည်။

➡️ [AI Features အသေးစိတ် →](ai)

---

## 🔄 Auto-Save & Revision (အလိုအလျောက်သိမ်းဆည်းခြင်း)

CodeYay Workspace သည် **Auto-save (အလိုအလျောက် သိမ်းဆည်းခြင်း)** စနစ်ကို အသုံးပြုထားပါသည်။
- Block တစ်ခုရွှေ့လိုက်တိုင်း (သို့) ပြင်လိုက်တိုင်း ညာဘက်အပေါ်ထောင့်တွင် `Saving...` ဟုပေါ်လာပြီး Cloud ပေါ်သို့ အလိုအလျောက် သိမ်းဆည်းသွားမည်ဖြစ်သည်။
- အောင်မြင်စွာ သိမ်းဆည်းပြီးပါက `Saved` အစိမ်းရောင်အမှတ်အသား ပေါ်လာမည်ဖြစ်သည်။

### အမှားပြင်ဆင်ခြင်း (Undo / Redo)
- ညာဘက်အပေါ်ထောင့် (Generated Code စာသားဘေး) တွင်ရှိသော ↩️ (Undo) နှင့် ↪️ (Redo) ခလုတ်များကို အသုံးပြု၍ မှားယွင်းလုပ်ဆောင်ခဲ့မိသော အဆင့်များကို နောက်ပြန်ဆုတ်ခြင်း၊ ပြန်လည်ပြင်ဆင်ခြင်းများ ပြုလုပ်နိုင်ပါသည်။


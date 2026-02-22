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
| `Ctrl + S` | Save                |
| `Delete`   | Selected block ဖျက်ပါ |

# MoonsLayout for ZSA Moonlander 🌙⚡

> **The End-Game Keyboard Layout**

```
         ╭─────────╮                    ╭─────────╮
    ╭────┤    🌙   ├────╮          ╭────┤    🌙   ├────╮
    │ Q  │ W  │ F  │ P  │ G  ╲    ╱  J  │ L  │ U  │ Y  │ ;  │
    ├────┼────┼────┼────┼────┤    ├────┼────┼────┼────┼────┤
    │ A  │ R  │ S  │ T  │ D  │    │ H  │ N  │ E  │ I  │ O  │
    ├────┼────┼────┼────┼────┤    ├────┼────┼────┼────┼────┤
    │ Z  │ X  │ C  │ V  │ B  ╱    ╲  K  │ M  │ ,  │ .  │ /  │
    ╰────┴────┴────┼────┼────┤    ├────┼────┼────┴────┴────╯
                   │SPC │TAB │    │ENT │BSP │
                   ╰────┴────╯    ╰────┴────╯
```

**Alright, so here's the deal...**

I've been using this layout for PowerShell automation, C# development, and DevOps tooling for over a 2-months now, and I'm gonna be completely honest with you - this thing is **legitimately incredible** for development workflows and System Management.

This isn't some meme keyboard setup. This is a **properly engineered solution** to the problem of RSI, inefficient typing, and constantly reaching for function keys while writing complex PowerShell pipelines and navigating massive C# codebases like some kind of keyboard peasant.

---

## ⚡ Why This Layout Is Actually Insane

### It's Colemak (And That's Not a Meme)
- 🧠 **Colemak base** - Scientifically proven to be more efficient than QWERTY
- 🏠 **Home row optimization** - Your fingers literally never have to leave home position
- 🌊 **Rolling finger patterns** - Common letter combinations flow naturally
- ⌨️ **Preserved shortcuts** - Ctrl+C, Ctrl+V still work exactly where you expect

### Layer System That Actually Makes Sense
- 🌟 **Base layer** - Colemak with intelligent thumb cluster design
- 🔣 **Symbols layer** - Every programming symbol exactly where it should be
- 💻 **VS-Code layer** - Dedicated layer for IDE functions (this is genuinely brilliant)
- 🔢 **Numpad layer** - F-keys and numbers without destroying your wrists
- 🪟 **WindsNav layer** - Window management that will change your workflow forever

### Built for People Who Actually Build Enterprise Software
- 🎯 **VS Code integration** - GoTo definition, LSP actions, debugging - all on dedicated keys
- 🔧 **PowerShell workflow** - Pipeline commands, module management, remote sessions without finger gymnastics
- 🪟 **C# development** - LINQ queries, async/await patterns, dependency injection navigation
- 📝 **Tooling automation** - Build scripts, deployment pipelines, package management
- ⚡ **Enterprise productivity** - Your hands will thank you after 10-hour DevOps sessions

---

## 🛠️ Setup Process (It's Actually Pretty Straightforward)

### What You Need

You need a **ZSA Moonlander**. If you don't have one, go buy one. Yes, it's $400. Yes, it's worth it. Your RSI prevention is worth more than $400. Trust me on this.

### Flashing the Layout

#### Option 1: Oryx (Recommended)
```bash
# 1. Go to configure.zsa.io
# 2. Upload the MoonsLayout.bin file
# 3. Flash it to your keyboard
# 4. Start becoming more productive immediately
```

#### Option 2: QMK Toolbox
```bash
# 1. Download QMK Toolbox
# 2. Select the .bin file
# 3. Put Moonlander in bootloader mode (hold inner thumb keys while connecting)
# 4. Flash and enjoy your new productivity superpowers
```

#### Option 3: Command Line
```bash
# Install QMK CLI
pip3 install qmk

# Flash the layout
qmk flash zsa_moonlander_MoonsLayout.bin

# Watch the magic happen
```

---

## 🎯 Layer Breakdown (The Technical Details)

### Layer 0: Colemak Base (The Foundation)
```
~  1  2  3  4  5   ⌘    |   ⌘  Utils 6  7  8  9  0  =
Del Q  W  F  P  G   *    |   *   J   L  U  Y  ;  P  '
Esc A  R  S  T  D   ↑    |   ↑   H   N  E  I  O  Tab ←
⬆  Z  X  C  V  B      |       K   M  ,  .  /  ?   ⬆
    Left Left  Tab     |     Del  Hyper   ⇧   Right Right
    Ctrl  Alt Ctrl     |     Space Super       Alt  Ctrl
           MagicUp     |     Flash    
           ⭐         |     Start
```

**This is Colemak, and it's genuinely better.** I know, I know - "just learn a new layout Thor" - but listen, the efficiency gains are real. Most common letters stay on the home row. Your fingers move less. You type faster with less effort.

### Layer 1: Symbols (Where Programming Happens)
```
⌀  ⌀  ⌀  ⌀  ⌀  ⌀  ⌀    |   ⌀  !  ?  +  ⌀  ⌀  ⌀
⌀  ⌀  &  %  ;  :  ⌀    |   ⌀  |  }  {  |  ⌀  ⌀
⌀  ⌀  $  =  -  "  #    |      (  )  ]  [  ⌀  ⌀
⌀  ⌀  _  .  \  *       |      @  /  ~  <  ⌀  ⌀
    ⌀  ⌀  Left         |      ⌀  ⌀      ⌀  Music
           Ctrl         |      ⌀           
```

**This layer is where the magic happens for C# and PowerShell.** Every bracket type is grouped logically. Curly braces for class definitions, square brackets for attributes and array indexing, parentheses for method calls and PowerShell cmdlet parameters - they're all positioned where your muscle memory expects them to be. No more hunting around for symbols while writing complex LINQ expressions.

### Layer 2: VS-Code (The Game Changer)
```
⌀  ⌀  ⌀  ⌀  ⌀  ⌀  ⌀     |  ⌀  ⌀  ⌀  ⌀  ⌀  ⌀  ⌀
⌀  ⌀  ⌀  ⌀  Debug Debug Pallet | Collapse ExpandAll ⌀  ⌀  ⌀  ⌀  ⌀
⌀  ⌀  ⌀  GoTo     Back   PaneX  LSP |  ExpandSel  Minimize  Insert  Home  ⌀
⌀  ⌀  ⌀  SQL  Explorer  Gemini       |      Line      Src    Ctrl+H  
⌀  ⌀  ⌀  ⌀  ⌀  ⌀       |    Tab:Next Tab:Prev New:Term Split  ⌀
                         |                            Term   
           Del           |      Hyper      
           ⭐           |      Super
```

**Okay, this layer is actually insane for .NET development.** Having a dedicated layer for VS Code functions completely changes how you interact with C# projects. GoTo definition for navigating dependency injection containers? One key. Debug step over through async methods? One key. Split terminal for running PowerShell commands while debugging? One key. This is how enterprise development should work.

### Layer 3: Numpad (Numbers Without Pain)
```
⌀  ⌀  ⌀  ⌀  ⌀  ⌀  ⌀    |   Utils ⌀  ⌀  ⌀  ⌀  ⌀  ⌀
⌀  F1 F2 F3 F4 F5 F6    |   F7  F8 F9 F10 F11 F12 ⌀
⌀  ⌀  1  2  3  4  ⌀    |   ⌀   5  6  7   8   ⌀   ⌀
⌀  ⌀  ⌀  ⌀  ⌀  9      |       0  .  ⌀   ⌀   ⌀   ⌀
    ⌀  ⌀  ⌀           |       ⌀  ⌀       ⌀   ⌀
```

**Function keys and numbers where they make sense.** No more reaching to the top row for F-keys. No more awkward number entry. Everything's accessible without wrist contortion.

### Layer 4: WindsNav (Window Management Mastery)
```
⌀  ⌀  ⌀  ⌀  ⌀  ⌀  ⌘    |   ⌀  ⌀  ⌀  ⌀  ⌀  ⌀  ⌀
Del ⌀  ⌀  ⌀  ⌀  Macro Win+R Win+R | Close New Browser X-Tab GoBack ⌀
⌀  Del ⌀  ⌀  ⌀           |   Wind Tab    PgDn PgUp ⌀
⌀  ⌀  Shift Shift Ctrl   Open  Alt+    |   ⌘  Ctrl+H  ⌀  ⌀  ⌀  ⌀
    Shift  Alt  Alt  Ctrl |     Del      Up  
           Del  Ctrl      |     Ctrl     Down
           Alt  Ctrl      |     Up       
```

**This layer will change how you think about window management.** Browser tab navigation, desktop workspace switching, terminal management - all without taking your hands off the keyboard. Once you use this, Alt+Tab feels primitive.

---

## 📈 Learning Timeline (The Real Talk)

### Week 1: The Struggle Is Real
- Your typing speed will **drop significantly**
- Colemak feels weird and wrong
- You'll question this decision multiple times
- **Stick with it** - this is normal

### Week 2-3: The Light Appears
- Muscle memory starts forming for common words
- Layer switching becomes more natural
- You start to feel the efficiency improvements
- Typing speed begins recovering

### Week 4+: The Transformation
- Typing speed almost matches  previous performance
- **With significantly less finger movement**
- Coding sessions feel less fatiguing
- You become insufferable about ergonomic keyboards (sorry)

### Month 3+: TBA
---

## 💡 Pro Tips From Actually Using This

### Colemak Mastery
1. **Focus on common words first** - "the", "and", "for", "you"
2. **Practice with typing games** - Makes the learning process less painful
3. **Don't switch back and forth** - Commit fully or suffer confusion
4. **Use typing.com's Colemak lessons** - They're actually decent

### VS-Code Layer Exploitation
- **Learn the debug shortcuts** - Essential for stepping through async C# methods
- **Master GoTo functions** - Definition, references, implementations across large codebases
- **Terminal workflow** - PowerShell ISE replacement, run scripts while debugging
- **LSP integration** - IntelliSense, refactoring, code actions for C# development

### WindsNav Layer Mastery
- **PowerShell windows** - Manage multiple PS sessions, admin vs user contexts
- **Documentation navigation** - MSDN, Stack Overflow, internal wikis
- **Azure portal workflow** - Navigate cloud resources while maintaining code context
- **Team collaboration** - Slack, Teams, email without losing development flow

### Oryx Optimization
- **Use the heatmap feature** - See which keys you actually use
- **Iterate based on data** - Adjust layout based on usage patterns
- **Version control your layout** - Track changes like code
- **Community layouts** - Browse for inspiration (most are terrible though)


---

## 🔧 Technical Implementation Details

### QMK Features Utilized
- **Tap Dance** - Different actions on tap vs hold
- **Layer Tap** - Tap for character, hold for layer switch
- **Mod Tap** - Tap for letter, hold for modifier
- **One Shot Mods** - Tap modifier, next key uses that modifier
- **Combo Keys** - Multiple keys pressed simultaneously for special actions

### Oryx Integration Features
- **Live layout updates** - Modify layout without reflashing
- **Usage analytics** - Track which keys you use most
- **Heatmap visualization** - See your typing patterns
- **Cloud synchronization** - Access layout from any device
- **Version history** - Track layout changes over time

### Custom Macro Examples
```c
// Example: C# property shorthand
case CSHARP_PROP:
    if (record->event.pressed) {
        SEND_STRING("{ get; set; }");
        tap_code(KC_LEFT);
        tap_code(KC_LEFT);
        tap_code(KC_LEFT);
        tap_code(KC_LEFT);
        tap_code(KC_LEFT);
        tap_code(KC_LEFT);
        tap_code(KC_LEFT);
        tap_code(KC_LEFT);
    }
    break;

// Example: PowerShell pipeline
case PS_PIPELINE:
    if (record->event.pressed) {
        SEND_STRING(" | ");
    }
    break;

// Example: Async method signature
case ASYNC_METHOD:
    if (record->event.pressed) {
        SEND_STRING("async Task");
    }
    break;
```

---

## 🎯 Final Thoughts

Look, I'm not going to sugarcoat this - switching to this layout is a significant commitment. The learning curve is real, and the first couple weeks are genuinely frustrating.

But here's the thing: Every key placement, every layer function, every macro is based on real-world usage patterns from PowerShell automation, C# development, and SOC workflows.

The VS-Code layer alone has changed how I interact with large .NET solutions. Having debug controls, navigation functions, and terminal management on dedicated keys eliminates so much friction from the development process. When you're stepping through async code with complex dependency injection, having everything at your fingertips is genuinely game-changing.

The ergonomic benefits are real too. After years of wrist pain from traditional keyboards while writing long PowerShell scripts and navigating massive C# codebases, switching to this split layout with proper thumb cluster usage has genuinely improved my quality of life.

Is it for everyone? No. But if you're a .NET developer or DevOps engineer who spends 8+ hours a day in VS Code and PowerShell, and you're willing to invest a month in learning something new, this layout will legitimately make you more productive.

**Just be prepared for the initial learning curve, and trust the process.**

---

## 📦 Repository Contents

- `zsa_moonlander_MoonsLayout.bin` - The compiled layout file for flashing
- `README.md` - This comprehensive guide
- `oryx_config.json` - Oryx configuration for modifications
- `keymap.c` - QMK source code for advanced users
- `layout_images/` - Visual representations of each layer

## 🤝 Contributing & Feedback

**Before submitting feedback:**
1. **Use the layout for at least 2 weeks** - Most issues are just unfamiliarity
2. **Understand the design philosophy** - Efficiency and ergonomics over familiarity
3. **Check existing issues** - Your question might already be answered

**What I'm interested in:**
- Genuine usability improvements based on extended use
- Bug reports with specific reproduction steps
- Performance optimizations for common workflows

**What I'm not interested in:**
- Requests to change Colemak to QWERTY
- Layout suggestions from people who haven't used it extensively
- "Why don't you just use X instead" without understanding the design goals

---

<div align="center">

**Built by a lowley IT nerd who got tired of keyboard-induced wrist pain during long PowerShell scripting sessions**

*"The best tools are the ones that get out of your way and let you focus on solving business problems"*

</div>

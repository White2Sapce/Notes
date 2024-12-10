---
tags:
  - Linux
  - linuxcmd
---

- الشيل في لينكس (Linux shell) :

  الشيل **"Shell"** هو الوسيط بين المستخدم و النواة, وهو فقط يقبل الأوامر الي يقدر يقرئها و يحولها لشيء يفهمه النواة ..., بمعنى هو الي يفسر لغة الأوامر المدخلة من أجهزة الادخال مثل **لوحة المفاتيح**, او من **الملفات**.  
  و عشان تقدر توصل ل **"Shell"** يبي لك تستخدم **(CLI = Command Line Interface)** عندنا في لينكس **"Terminal"** و في ويندوز **"Command Prompt"**.
  
  وفي انواع لل **"Shell"** :
  
  -  **Bash (Bourne Again Shell)** :
  
    هو الشائع في نظام لينكس, وهو موجود بشكل افتراضي, ويوفر مجموعة كبيرة من الأدوات و الميزات.  

 - **CSH (C Shell)** :

	الصياغة حقت **"C Shell"** تشبه بشكل كبير لغة **"C"** البرمجية, وهو بالأساس يحاكي بعض بنية اللغة.

- **KSH (Korn Shell)** :

	مثل اخوانه يقدم لك ميزات و أدوات متقدمة و قوية للمستخدم, وهو تطور ل **"Bourne Shell"**. 

**و غيره الكثير مثل (Zsh, Fish, Z Shell, Dash, PowerShell)**.

#### ونجي عند سؤال ليش ما  نستخدم ال (GUI) بدل (CLI) ؟

الجواب : لمن نجي نتكلم عن **(GUI = Graphical User Interface)** فانحن نتكلم على واجهة رسومية بصرية فيها ازرار و قوائم وكمان أيقونات.
وكمان مناسبة للمبتدئين و الناس البسيطة, وماتحتاج منك فهم للأوامر.
وراح تجذبك بسبب التصاميم حقتها, وتعطيك ادوات تقدر تتفاعل معها.

لكن فيها عيوب منها : تستهلك موارد عالية من الجهاز, وأبطأ مقارنة ب **(CLI)** في تنفيذ بعض المهام.
وكمان بنسبة للمحترفين بتكون اقل كفاءة بالنسبة لهم, خصوصا لو يحتاجون ينفذون مهمه متكررة داخل النظام.

لكن تعال ل **(CLI = Command Line interface)** تفاعل مباشر مع النظام.
و المزايا : كفاءة بالأداء سريع في تنفيذ الأمر, قوة تحكم, عكس ال **(GUI)** هنا استهلاك موارد اقل, وذا يعني ان حتى الاجهزة الضعيفة تقدر تتحكم فيهن.

لكن مو كل شيء كامل فيه كذا عيب ... منها ان التعلم على الأوامر و معرفتها بشكل دقيق شيء لا مفر منه.
والاخطأ البشرية طب و تخير.
ومافيه اي شيء جذاب, انت و الشاشة السوداء.

وهنا مقارنة

| **CLI**                                             | **GUI**                                          | **الميزة**        |
| --------------------------------------------------- | ------------------------------------------------ | ----------------- |
| يحتاج منك تعرف الأوامر.                             | سهل للعامة ما يحتاج منك شيء كبير عشان تتعلمه.    | سهولة التعلم      |
| أسرع في تنفيذ المهام.                               | بطيء في تنفيذ المهام بسبب انك تتفاعل مع الواجهة. | الأداء            |
| اقل إستهلاك للموارد, يعتمد فقط على النصوص.          | يحتاج ذاكرة و معالج اكبر عشان الرسوميات.         | استهلاك الموارد   |
| مرن جدا, وتقدر تخصص حسب الحاجه.                     | اقل مرونة في التخصيص مقارنة ب **CLI**.           | التخصيص           |
| أكثر كفاءة للمستخدمين المتمكنين في المهام المتكررة. | اقل كفاءة في المهام المكررة.                     | المهام المتكررة   |
| يطلب من معرفة أوامر النظام, عشان تتحكم بشكل كامل.   | بتتفاعل مع النظام عن طريق الأيقونات.             | التفاعل مع النظام |
| مو مناسب للعوام و المبتدئين بشكل عام.               | مثالي للعوام و الجدد.                            | ملائم مع المستخدم |
##### والخلاصة :
- **GUI** : يناسب المستخدم العادي 
- **CLI** : مناسب للمستخدم المتمكن من النظام و المطوري ومسؤولي الأنظمة
  


### Linux Shell

The **Shell** in Linux is the intermediary between the user and the kernel. It only accepts commands it can interpret and translates them into something the kernel understands. In simpler terms, it acts as a translator for input commands from devices like the **keyboard** or **files**.  
To access the **Shell**, you need to use a **CLI (Command Line Interface)**. On Linux, this is the **Terminal**, while on Windows, it’s the **Command Prompt**.

There are several types of **Shell**:

- **Bash (Bourne Again Shell):**  
  The most commonly used shell in Linux, available by default. It provides a wide range of tools and features.

- **CSH (C Shell):**  
  The syntax of **C Shell** closely resembles the **C programming language**, designed to mimic some of its structure.

- **KSH (Korn Shell):**  
  Offers advanced and powerful tools, much like its counterparts, and is an improvement over the **Bourne Shell**.

**Other shells include Zsh, Fish, Z Shell, Dash, and PowerShell.**

---

### Why Not Use GUI Instead of CLI?

When we talk about **GUI (Graphical User Interface)**, we refer to a graphical interface with buttons, menus, and icons. GUIs are beginner-friendly, intuitive, and require little to no knowledge of commands. They often attract users with their designs and provide interactive tools.

However, GUIs have drawbacks:  
- They consume more system resources.  
- They are slower compared to **CLI** for certain tasks.  
- For professionals, GUIs may be less efficient, especially for repetitive tasks.

On the other hand, **CLI (Command Line Interface)** offers direct interaction with the system.  

#### CLI Advantages:  
- High performance with fast command execution.  
- Better control over the system.  
- Lower resource usage, making it suitable for low-spec devices.

#### CLI Disadvantages:  
- Requires learning and mastering commands.  
- Prone to human errors.  
- Lacks visual appeal—it’s just you and the black screen.

---

### Comparison Table

| **CLI**                                             | **GUI**                                          | **Feature**          |
| --------------------------------------------------- | ------------------------------------------------ | --------------------- |
| Requires knowledge of commands.                     | Easy to use for beginners, minimal learning required. | Ease of Learning      |
| Faster task execution.                              | Slower task execution due to interaction with the interface. | Performance           |
| Consumes fewer resources, text-based.               | Requires higher memory and processing power for graphics. | Resource Consumption  |
| Highly flexible and customizable.                   | Less flexible compared to **CLI**.               | Customization         |
| More efficient for advanced users handling repetitive tasks. | Less efficient for repetitive tasks.             | Repetitive Tasks      |
| Demands familiarity with system commands for full control. | Interaction with icons and menus.               | System Interaction    |
| Not beginner-friendly or suitable for general users. | Perfect for general and novice users.           | User-Friendliness     |

---

### Conclusion:
- **GUI**: Best for everyday users and beginners.  
- **CLI**: Ideal for advanced users, developers, and system administrators.
  
  
# RatNet-KillSwitch

### English

**Description:**
RatNet-KillSwitch is a security utility written in C# designed to disrupt the communication channels of Remote Access Trojans (RATs). Many malicious tools rely on built-in Windows processes (like `powershell.exe`, `rundll32.exe`, `mshta.exe`) to establish outbound connections and exfiltrate data. This tool automatically enforces Windows Firewall rules to block internet access for these specific processes, effectively neutralizing the RAT's ability to "phone home."

**Features:**

* **Proactive Defense:** Instantly cuts internet access for suspicious processes.
* **Easy Reversion:** Allows users to restore connectivity with a single command.
* **Automation:** Utilizes `netsh` to manage firewall rules programmatically.
* **Security Focused:** Designed to mitigate risks from common malware persistence and communication vectors.

**Disclaimer:** This tool is for educational and defensive purposes only. Please ensure you understand which processes you are blocking, as restricting essential system binaries may impact normal OS functionality.

---

### الوصف بالعربية

**الوصف:**
أداة RatNet-KillSwitch هي أداة دفاعية برمجية بلغة C# مصممة لقطع قنوات الاتصال التي تستخدمها برمجيات التحكم عن بعد الخبيثة (RATs). تعتمد معظم هذه البرمجيات على استغلال عمليات ويندوز الأساسية (مثل `powershell.exe`, `rundll32.exe`, `mshta.exe`) للاتصال بخوادم المهاجمين وسرقة البيانات. تقوم هذه الأداة بفرض قواعد جدار حماية ويندوز فورية لحظر وصول هذه العمليات إلى الإنترنت، مما يؤدي إلى شل قدرة برمجيات الـ RAT على التواصل مع المهاجم.

**المميزات:**

* **دفاع استباقي:** قطع الاتصال بالإنترنت عن العمليات المشبوهة فوراً.
* **سهولة التراجع:** إمكانية استعادة الاتصال للعمليات بشكل كامل وبضغطة زر.
* **الأتمتة:** استخدام أوامر `netsh` لإدارة قواعد جدار الحماية برمجياً.
* **تركيز أمني:** صُممت لتقليل المخاطر الناتجة عن أدوات الاختراق الشائعة.

**إخلاء مسؤولية:** هذه الأداة مخصصة للأغراض التعليمية والدفاعية فقط. يرجى التأكد من فهم العمليات التي تقوم بحظرها، حيث أن تقييد بعض ملفات النظام الأساسية قد يؤثر على عمل نظام التشغيل بشكل طبيعي.

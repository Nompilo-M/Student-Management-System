# <p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=FFC0CB&height=220&section=header&text=NOMPILO%20MBENSE&fontSize=70&animation=fadeIn&fontColor=FFFFFF&stroke=FF69B4&strokeWidth=2" width="100%" />
</p>


# <p align="center">
  <a href="https://git.io/typing-svg">
    <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=28&pause=1000&color=FF69B4&center=true&vCenter=true&width=600&lines=Software+Engineer;Cloud+And+AI+Specialist;OCI+Cloud+Certified;Agentic+AI+%26+Automation" alt="Typing SVG" />
  </a>
</p>

---

# <p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=FF69B4&height=220&section=header&text=STUDENT%20MANAGEMENT%20SYSTEM&fontSize=50&animation=fadeIn&fontColor=FFFFFF" width="100%" />
</p>

# <p align="center">
  <img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/People/Woman%20Technologist.png" alt="Woman Technologist" width="120" height="120" />
</p>

<p align="center">
  <a href="https://git.io/typing-svg">
    <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=28&pause=1000&color=FF69B4&center=true&vCenter=true&width=600&lines=ENGINEERING;EVENT-DRIVEN+LOGIC;INTERFACES+%26+DELEGATES" alt="Typing SVG" />
  </a>
</p>


---

### 🖥️ Application Blueprint & Live Demo
This isn't just a CRUD application; it is an engineered solution built with **Interfaces** and **Delegates**.

<p align="center">
  <img src="demo.gif" width="800" alt="Application Demo" />
</p>

<details open>
<summary><b>🧠 Advanced Engineering Checklist</b> (Click to open/close)</summary>
<br>

* [x] **High Cohesion:** Every class has a single, well-defined responsibility.
* [x] **Low Coupling:** UI and Logic communicate through events, ensuring flexibility.
* [x] **SOLID Principles:** Adherence to standard OOP design guidelines.
* [x] **T-SQL Integrity:** Relational database triggers and constraints for data security.
</details>

---

### 🔮 The Engineering Magic: Interfaces & Delegates
This project implements advanced OOP principles. Let's visualize the "Event-Driven" contract that decouples the system.

```csharp
/***********************************************************
 * [PINK CODE CARTOON VISUAL]                           *
 * The Contract: IStudentService                         *
 ***********************************************************/
public interface IStudentService
{
    // The Event that anyone can listen to
    event StudentUpdatedDelegate OnStudentUpdated;

    void UpdateStudentResult(int studentId, double newMark);
}

/***********************************************************
 * The Delegate: Messenger                              *
 ***********************************************************/
public delegate void StudentUpdatedDelegate(object sender, StudentEventArgs e);

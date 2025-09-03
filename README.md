# Python Screening Task 2 – AI Debugging Assistant Prompt  

##  Author Introduction  
This submission was prepared by **Amit Sahu**, a 3rd-year B.Tech student passionate about **Artificial Intelligence, Python development, and educational technology**.  
I enjoy building tools that make learning easier and aim to combine **AI + EdTech** for impactful solutions.  

---

##  Task Objective  
This repository contains my submission for **Python Screening Task 2**.  
The goal was to **write a natural-language prompt** that guides an AI assistant to:  

- Analyze a student’s buggy Python code  
- Provide constructive hints and debugging strategies  
- Avoid giving away the full correct solution  
- Use a supportive, educational tone  

---

##  Final Prompt  
See [`debugging_prompt.md`](debugging_prompt.md) for the full prompt.

---

##  Reasoning & Design Choices  

1. **Why worded this way**  
   - Clear, numbered rules guide the AI’s behavior.  
   - Strong emphasis on *guidance instead of solutions* ensures learning.  
   - Encourages debugging habits rather than dependency.  

2. **How it avoids giving solutions**  
   - Explicit instruction not to provide the corrected code.  
   - Focus only on hints, error identification, and debugging strategies.  

3. **How it encourages helpful feedback**  
   - Supportive and educational tone.  
   - Offers debugging steps (e.g., print statements, type checks).  
   - Mentions common Python mistakes for better generalization.  

---

##  Reasoning Questions  

**1. What tone and style should the AI use?**  
- Encouraging, patient, and educational.  
- Conversational and beginner-friendly when needed.  
- Respectful of the student’s effort.  

**2. How should the AI balance between identifying bugs and guiding the student?**  
- Identify possible issues without fixing them directly.  
- Offer hints and debugging tools.  
- Encourage the student to test and iterate.  

**3. How would you adapt this prompt for beginner vs. advanced learners?**  
- **Beginners**: Step-by-step guidance, simple explanations, examples of debugging methods.  
- **Advanced**: Higher-level hints, focus on logical flaws, optimization, and edge cases.  

---

##  Future Adaptations  

This prompt can be adapted to other domains:  
- **Other Programming Languages**: C, C++, Java debugging with similar rules.  
- **Algorithm Support**: Guide students through algorithm design errors without solving directly.  
- **Educational Tools**: Can be integrated into EdTech platforms to provide AI-powered debugging tutors.  

This flexibility ensures the prompt is not limited to Python but can serve as a **general AI teaching framework**.  

---

## Submission Checklist  

-  Prompt is clear, specific, and well-structured  
-  Reasoning is thoughtful and well-articulated  
-  Includes reasoning answers  
-  Includes professional self-introduction  
-  Includes future adaptations section  

---

##  How to Use  

1. Clone this repository or download the files.  
2. Open `debugging_prompt.md` to view the final prompt.  
3. Use the prompt with any AI assistant (like ChatGPT) when guiding students.  

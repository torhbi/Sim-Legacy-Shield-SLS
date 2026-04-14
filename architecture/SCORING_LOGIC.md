SLS Risk Scoring Heuristics

Risk Levels:
0 – 3   → 🟢 Safe  
4 – 5   → 🟡 Caution  
6+      → 🔴 High Risk  

High Risk condition requires at least 2 different signal types.



Signals & Weights:

SIM Age < 30 days → +2  
(Recent SIMs carry higher uncertainty)

User suspects previous owner → +2  
(Initial user-reported signal)

Repeated/consistent user reports → +3  
(Validated pattern over time)

Financial Conflict Signal → +3  
- Debt recovery messages  
- Loan reminders  
- чуж bank alerts  

Verified Agent Flag → +5  
(High-confidence validation from trusted agent)



Signal Expiry:
- Signals older than 90 days reduce in weight  
- Prevents permanent flagging of SIMs

# Persona Cognitive Walkthrough Logs

## Summary of Question Accuracy Across Formats
| Persona & Letter | Original Letter Accuracy | Prompt A Accuracy | Prompt B Accuracy | Key Usability Friction Point |
| :--- | :---: | :---: | :---: |
| Arthur (Cardiology - L1) | 33% (1/3) | 67% (2/3) | **100% (3/3)** | Missed pre-dose pulse check in Original & Prompt A due to lack of bullet visual anchors. |
| Priya (Gastroenterology - L2) | 67% (2/3) | 67% (2/3) | **100% (3/3)** | Prompt A dropped the 5mg/7 days tapering rule; Prompt B explicitly highlighted it. |
| Gary (Diabetes - L3) | 0% (0/3) | 67% (2/3) | **100% (3/3)** | Original HbA1c and eGFR values caused complete confusion; Prompt B translated metrics to plain English. |
| Margaret (Rheumatology - L4) | 33% (1/3) | 33% (1/3) | **100% (3/3)** | High safety risk in Original/Prompt A regarding taking Methotrexate daily vs weekly. Prompt B isolated rule with callout. |
| David (Vascular - L5) | 67% (2/3) | 100% (3/3) | **100% (3/3)** | Red-flag symptoms for DVT were buried in Original; Prompt B warning section gave instant clarity. |

## Core HCI Takeaways for Redesign
1. **Visual Scannability > Plain Text:** Text simplification alone is insufficient. Structured headers and bullet points reduced search time by over 60%.
2. **Action Item Isolation:** High-risk safety instructions (e.g., "Check pulse before taking", "Do NOT take daily") require distinct visual callout components.
3. **Temporal Mapping:** Dosage tapering (Prednisolone) and weekly schedules (Methotrexate) need timeline or calendar-style UI presentation.

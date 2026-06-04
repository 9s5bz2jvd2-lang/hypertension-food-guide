# Nutrition Science | Hypertension Nutrition Guide

English version translated from the existing Chinese README.

An AI popular-science conversation assistant based on the **Dietary and Nutrition Guide for Adults with Hypertension (2023 Edition)** issued by the **General Office of the National Health Commission**. | Nutrition Science Skill

> 🌱 I am new to AI and hope to use AI to share nutrition knowledge and help more people. If anything is insufficient, feedback is welcome. I will keep working on more nutrition-science skills. If you find this useful, please consider giving it a ⭐ Star. Thank you!

---

## Guideline Source

- **Full title**: *Dietary and Nutrition Guide for Adults with Hypertension (2023 Edition)*
- **Issuing organization**: General Office of the National Health Commission

## Features

- **Risk assessment**: blood-pressure self-assessment (3 grades) plus cardiovascular risk stratification
- **Dietary-nutrition principles**: 5 official principles centered on sodium reduction and potassium increase, covering diet, exercise, weight, and lifestyle
- **Three dietary patterns**: DASH, the Eastern healthy dietary pattern, and CHH-Diet (Chinese Heart-Healthy Diet)
- **TCM syndrome differentiation**: 7 syndrome patterns
- **Formula library**: 14 dietary formulas (6 porridges, 4 teas, 3 soups, 1 rice dish), selected by syndrome pattern
- **Regional adaptation**: 7 regions × 4 seasons × 3 days = 84 complete menus
- **Food choices**: 5 recommended food categories, suitable/limited food lists, and hidden-sodium identification
- **Popular-science style**: plain language, concrete quantities, and myth correction—precise without being condescending

## Quick Reference

| Item | Recommendation | Plain-language explanation |
|------|----------------|----------------------------|
| Salt | ≤5 g/day | About one beer-bottle cap |
| Sodium intake | <2000 mg/day | Roughly the sodium in 5 g salt |
| Potassium intake | >2500 mg/day | More vegetables, fruit, and legumes |
| Cooking oil | 20–25 g/day | No more than about two tablespoons |
| Dietary fiber | 25–40 g/day | Vegetables, fruit, and coarse grains |
| Fresh vegetables | ≥300 g/day | At least half should be dark-colored vegetables |
| Fresh fruit | 200–350 g/day | An apple plus a small bowl of berries |
| Dairy | 300–500 g/day | 1–2 cups of milk |
| Hypertension grade 1 | 140–159/90–99 mmHg | Mild |
| Hypertension grade 2 | 160–179/100–109 mmHg | Moderate |
| Hypertension grade 3 | ≥180/≥110 mmHg | Severe |
| Weekly exercise | 4–7 days, 30–60 min/day | Moderate-intensity aerobic activity |

## Knowledge System

| KPK ID | Topic | Source section |
|--------|-------|----------------|
| KPK-01~05 | Five dietary-nutrition principles | Dietary-nutrition principles chapter |
| KPK-06~12 | Disease background, TCM patterns, food choices, formulas, and Q&A | Disease background + appendices + Q&A |

## File Structure

```text
- skill.yaml: Skill configuration
- SKILL.md: Core skill file
- system_prompt.md: System prompt
- knowledge_base.md: Integrated KPK knowledge base
- kpk_*.md: Principles, disease, appendix, and Q&A KPK files
- README.md: Chinese README
- install.sh: Linux/macOS install script
- install.bat: Windows install script
```

## Statement

**Disclaimer**:
1. All content comes from the guideline above and is for dietary-nutrition popular-science reference only; it does not replace medication treatment or professional medical diagnosis.
2. It supports prevention and improvement for adults with hypertension; people with other comorbidities may refer to it but should not apply it rigidly.
3. Food-medicine substances and new food raw materials should be used under professional guidance and not taken in excessive amounts.
4. People with diabetes, coronary heart disease, kidney disease, or other underlying conditions should receive professional physician and nutrition guidance.
5. This skill was built with AI assistance. Although it aims to stay faithful to the original guideline, paraphrasing errors may exist. If there is any doubt, please refer to the official published guideline text.


## Creator

**Runyuan Wang**
- Chinese Registered Dietitian
- M.S. in Nutrition and Food Hygiene, Kunming Medical University
- Built with WorkBuddy

## License

MIT

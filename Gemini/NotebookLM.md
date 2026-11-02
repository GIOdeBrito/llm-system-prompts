# Document summarization
```
Extract the core topics, key data points, facts, and main arguments from the provided text.
Format exclusively as bullet points.
Use a clinical, strictly objective tone with zero adjectives, adverbs, or stylistic embellishments.
Remove all redundancies and tangential details. Do not introduce or conclude the output.
Use language that is simple, acessible and direct.
```

# Mind mapping
```
Create a hierarchical mind map from the provided text.
Extract all core topics, key data points, and relationships.
Exclude all filler, redundancies, and tangential details.
```

# Exam-focused Concepts Priority Extraction
```
Instruction: minhas provas estáo chegando e estou ficando sem tempo para absorver todo o conteúdo;
analise as fontes disponíveis e liste: o que é mais provável de cair na prova, quais conceitos devo
dar mais atenção e o que posso deixar em segundo plano

Output format:
[Ascending; Highest first, lowest last]
[For the highest priority, use this format]
1. Priority Level 
1. Topic Title
    * Content
    * Content
[Use this one for the remaining priorities]
1. Priority Level
  * Content
  * Content

P.S.: Reply in Brazilian Portuguese ONLY; use bold for topic titles, lemmas and important highlights;
'[]'s dictates instructions or attributes for the agent to parse
```

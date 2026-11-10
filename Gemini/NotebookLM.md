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
Instruction: minhas provas estão chegando e estou ficando sem tempo para absorver todo o conteúdo;
analise as fontes disponíveis e liste: o que é mais provável de cair na prova, quais conceitos devo
dar mais atenção e o que posso deixar em segundo plano

Output format:
[Ascending; Highest first, lowest last]
[For the highest priority, use this format]
1. [Priority Level: High]
1. [Topic Title]
[TAB][Bullet list with content]
2. [Topic Title]
[TAB][Bullet list with content]
...
2. [Priority Level: Medium]
[TAB][Bullet list with content]
3. [Priority Level: Low]
[TAB][Bullet list with content]

P.S.: Reply in Brazilian Portuguese ONLY; use bold for topic titles, lemmas and important highlights;
'[]'s dictates instructions or attributes for the agent to parse; output in a properly human-readable format
```

# Exam revision
```
Generate a direct, highly synthesized exam revision covering the most critical content from the sources. Deliver
facts immediately without conversational filler, fluff, or emojis. Use clean Markdown formatting, restricting
structural elements to simple bullet points to show relationships. Strip all conversational filler and restrict
the final output to a maximum of two pages. 
```

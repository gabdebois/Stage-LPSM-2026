```dataview 
LIST L.text 
FROM #question 
FLATTEN file.lists AS L 
WHERE contains(L.tags, "#question") 
```






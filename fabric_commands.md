# https://github.com/danielmiessler/fabric

# Copy Youtube transcript to clipboard (pbcopy)
```
yt --transcript https://www.youtube.com/watch?v=oTY8egmo7us&pp=ygUIYWdlbnRncHQ%3D | pbcopy
```
# Summarize copied content and save to file (pbpaste) DO NOT USE --stream WHEN PIPING!!!
```
pbpaste | fabric --model gpt-4o-mini --pattern extract_wisdom > summ2.md
```


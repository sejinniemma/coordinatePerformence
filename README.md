# Coordinate performence 🕸



https://user-images.githubusercontent.com/80943394/136160851-ea806cad-475a-4b36-8d88-317f239f918a.mov


## Critical rendering path 🌈
- I tried to make this project for good performencee and wanted to check how much better
- this project is for understanding layout,paint,composition process.


### What I changed 💥
1. Using 'translate' instead of 'top,left' for better performence so that we can prevent layout occure.
2. Sometimes  there could be a problem to get 'image.getBoundingClientRect()' first before getting image.
<br> we can prevent this problem by using 'load' instead of 'defer' or 'DOMContentLoaded'.


### Bad performence using x,y position 💩❌
- paint , layout always are happening ( reference CSS triggers)
<img width="616" alt="스크린샷 2021-10-06 오후 4 14 29" src="https://user-images.githubusercontent.com/80943394/136159333-43c454b1-dd32-460c-9aea-ef7ec6fbd178.png">

### Good performence using transform 🥰
<img width="959" alt="스크린샷 2021-10-06 오후 4 13 05" src="https://user-images.githubusercontent.com/80943394/136161579-edaee4c3-b4cb-4e60-af01-3db98a0f4235.png">

## Check performence in the 'performence tap' !!✅

- It seems like similar when we move the mouse on the browser 
- but if we check performence , it's totally diffrent

1. Bad performence when using x,y position
<img width="922" alt="스크린샷 2021-10-06 오후 4 59 15" src="https://user-images.githubusercontent.com/80943394/136163197-adcc8262-0c2a-4dcf-833d-e75ef1547759.png">

2. Good performence when using transform
<img width="1053" alt="스크린샷 2021-10-06 오후 4 56 18" src="https://user-images.githubusercontent.com/80943394/136162811-ce6be53e-1238-4c66-ba5d-c020ace8f541.png">

# Coordinate performence🕸


## Critical rendering path
- I tried to make this project for good performencee and wanted to check how much better
- this project is for understanding layout,paint,composition process.


### write code again for good performence like down below
1. using translate instead of top,left for better performence so that we can prevent layout occure.
2. sometimes  there could be a problem to get getBoundingClientRect before loading img.
we can prevent by using 'load' instead of 'defer' or 'DOMContentLoaded'.
<img width="616" alt="스크린샷 2021-10-06 오후 4 14 29" src="https://user-images.githubusercontent.com/80943394/136159333-43c454b1-dd32-460c-9aea-ef7ec6fbd178.png">
<img width="959" alt="스크린샷 2021-10-06 오후 4 13 05" src="https://user-images.githubusercontent.com/80943394/136159339-48e4b079-7e9a-4fba-9ce4-25873a1bd6cc.png">

# Insect-catch-game
Asked classmate to look over code as game was loading but not functioning, they suggested I move screens[0].classList.add('up') from the top until after my screens had been declared. 11/18/26
Start game screen was almost immediately disappearing offscreen upon site loading. VSC's AI chatbot suggested to add the line: screens[0].classList.remove('up'); to attempt to fix this issue. I pushed this to GitHub to see if it helped. 11/19/26

step1: 
create your project :-
npm create vite@latest my-project
cd my-project
-------------------------------------------------------------------------------------------------

step2: install tailwindcss and @tailwindcss/vite via npm. :-
npm install tailwindcss @tailwindcss/vite

-------------------------------------------------------------------------------------------------

step3:  Add the @tailwindcss/vite plugin to your Vite configuration  

import { defineConfig } from 'vite'
import tailwindcss from '@tailwindcss/vite'

export default defineConfig({
  plugins: [
    tailwindcss(),
  ],
})
-------------------------------------------------------------------------------------------------
step4:  Add an @import to your CSS file that imports Tailwind CSS

 @import "tailwindcss";
-----------------------------------------------------------------------------------------------
step5: Run your build process with npm run dev 

npm run dev
-------------------------------------------------------------------------------------------------

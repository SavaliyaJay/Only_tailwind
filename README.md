# Only_tailwind
This my fully responsive talwind css project in which i create a responsive navbar,and all other things

1) install Tailwind CSS:
    npm install -D tailwindcss
    npx tailwindcss init
   
2) Configure your template paths:
    /** @type {import('tailwindcss').Config} */
    module.exports = {
      content: ["./src/**/*.{html,js}"],
      theme: {
        extend: {},
      },
      plugins: [],
    }
   
3) Add the Tailwind directives to your CSS
    @tailwind base;
    @tailwind components;
    @tailwind utilities;
    
    ## **Simple Web Page**
![img](https://user-images.githubusercontent.com/102573818/226439808-f68c4cf6-43f4-41ed-a12f-25714af14197.png)


    ## **with responsive**
![img1](https://user-images.githubusercontent.com/102573818/226439976-67b6d28b-23bf-463f-b61a-973954cc4afc.png)

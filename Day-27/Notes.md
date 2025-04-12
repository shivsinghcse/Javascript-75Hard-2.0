# Tailwind CSS

- Tailwind is css library/framework.
- Tailwind provides utility first classes.
- CDN (Content Delivery Network)
- Link CDN in your html file.
- CDN load in the browser cache. No you can use tailwind.
- For every property tailwind provide classes.
- Color varient starts from 50 - 950
- `White` and `Black` color does not have varient.

## Tailwind classes for the CSS properties
- background : `bg-color_name-varient`
- text-color : `text-color_name-varient`
- width : `w-1`, range goes from 1 to 96. 1 = 4px, 2 = 2*4 (8px), 96 = 384px
    - For customize width we use `[]` eg: `w-[480px]
    ```css
        w-px = 1px
        w-full - 100%
        w-6/12 - 50%
        w-fit - fit-content
    ```
- height : `h-1`  
    - h-px
    - h-5    1-96
    - h-full  -100% 
        - It works in only two conditions
            - position should be absolute or relative
            - container must have some height
    - h-screen - 100vh
    - h-fit - fit-height

- font-weight : 
    - font-medium
    - font-semibold
    - font-bold

- text-align
    - text-center    
    - text-left    
    - text-right    
    - text-justify    
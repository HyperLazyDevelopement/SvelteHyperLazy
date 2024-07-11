# SvelteHyperLazy
A **SEO** and **UX** improving package desired for **Svelte**; Allow to lazy load every html content semlessly regardless to initial page open

## Keynote
"Load what is important first, rest after"

## Explaination
Every page content is load to viewport before whole page has been successfully loaded. Such behaviour result in:
1. Greatfull initial page load time what directly impact **SEO**,
2. **SEO** - your page has worst loading times than your comps
3. **UX** - Not loaded e.g: fonts before user see page content

### So?
By our package you can improve: **SEO**, **UX** due to: Every page element is attach to, in defined by you order after page has been loaded. The ___order___ is a startegy which you predefine durning developement stage and this can be:
* every - every element is attached to your page after intial load has finished
* spill - element is shown when user see on screen an anchor (replacement element on the same spot with lowwer size - by default indicate loading),
* clay - element is shown when user see on screen prior element; You specify which element it's

**Anecdote:** The whole working behaviour can be copmared to **atomic skytower on damp field**, to be on 2nd pitch you need to be on 1st pitch first, thereby to reduce weight momentum in **atomic tower** 2nd pitch is built after visited 1st pitch, in such a manner reducing likeness of collapse under the ground -> this is how **SvelteHyperLazy** works

# cpnt262-achievement-6

## Maryam Khan

## Vue Components

- [GH repo](https://github.com/maryambkhan/cpnt262-achievement-6)
### Code Journal

- Yesterday when i was working in lab time i ran into an
  error it was becouse of `eslint`. I asked for help 
  and patrick helped me 
- Sloution was installing eslint 
  [eslint](https://eslint.vuejs.org/user-guide/#usage)
  for me this one worked:
     `npm install --save-dev eslint eslint-plugin-vue`
- So today i started new project and already installed eslint 
   i am hoping there is no problem.
- Plan:
  - Components:
    - TheHeader
    - TheNavBar
    - PageContent
    - PageContentHeader
    - TheFooter
- It was so good working in vue and using v-bind v-for and slot
  it took me whole lot of time learn becouse i did not had enough 
  practice before but after i inderstood why and how we use these
  it was amazing.
- I watched class video and followed the documents it helped.
- I have got plan data right know on page will do some more page level styling
  and try to use this : `<img :src="cat.photo" :alt="cat.description" />`
- I had realy hard time working with new syntax but todays work helped me alot.
- It was so much fun working today i saw what can do and what i need to to more
  and working team was a learning process too.
- I have added footer herosection image thats what i did in the morning too.
  i did everything in steps started with simple compnents and then render them on 
   html page and then applied props,slot and v-bind.
- I uced color gradient that i learned today too.

### Notes

- Slot:
    This allows you to create space inside a component for extra content to be added in specific uses
    In your component, you use a v-slot to tell the component what to do with the extra info

- V-for:
`<ul>
  <li v-for="hero in heroes" :key="hero.id">
  {{ hero.name }}
  </li>
</ul>`

- v-bind: `<img :src="cat.photo" :alt="cat.description" />`
   This is one of the most important. it allows you to bind data to html properties such as src in an img tag


### Attributions

- [Pexel](https://www.pexels.com/photo/purple-fireworks-effect-1190298/)
- [Vue Js](https://vuejs.org/guide/essentials/list.html)
- [Eslinter](https://eslint.vuejs.org/user-guide/#usage)
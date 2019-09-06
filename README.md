# vue-chatkit
chat-room-based-on-vuejs

----

# Install


### Install Vue-CLI(Vue-Command-Line)
> npm i @vue/cli

### Create Project
> vue create vue-chatkit

```
(Manually select features: Babel, Router, Vuex, Linter)
Use history mode for router? Yes
Pick a linter / formatter config: Basic (The First Options)
Pick additional lint features: Lint on save
Where do you prefer placing config for Babel, PostCSS, ESLint, etc.? In dedicated config files
Save this as a preset for future projects? (y/N) N
```

----

### Create Directories and files

```
mkdir src/assets/css
mkdir src/store

touch src/assets/css/{loading.css,loading-btn.css}
touch src/components/{ChatNavBar.vue,LoginForm.vue,MessageForm.vue,MessageList.vue,RoomList.vue,UserList.vue}
touch src/store/{actions.js,index.js,mutations.js}
touch src/views/{ChatDashboard.vue,Login.vue}
touch src/chatkit.js

rm src/components/HelloWorld.vue
rm src/views/{About.vue,Home.vue}
rm src/store.js
```

----

### Install Dependencies

> npm i @pusher/chatkit-client bootstrap-vue moment vue-chat-scroll vuex-persist

- @pusher/chatkit-client, a real-time client interface for the ChatKit service
- bootstrap-vue, a CSS framework
- moment, a date and time formatting utility
- vue-chat-scroll, which scrolls to the bottom automatically when new content is added
- vuex-persist, which saves Vuex state in browser's local storage



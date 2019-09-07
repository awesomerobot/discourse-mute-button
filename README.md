# discourse-mute-button

This is a simple theme component for Discourse that adds an explicit mute toggle under the topic timeline. The button toggles between `mute` and `normal` tracking statuses. 

![29%20PM|541x500,75%](https://assets-meta-cdck-prod-meta.s3.dualstack.us-west-1.amazonaws.com/original/3X/b/5/b5d4221019c6e37e143c675e2a02b18ecb372a05.png) 


:question:  https://meta.discourse.org/t/how-do-i-install-a-theme-or-theme-component/63682


That's all it does!  If you don't care about the other tracking types you can hide that now-redundant button with some CSS



```css
.timeline-container 
.timeline-footer-controls 
button.dropdown-select-box-header {
    display: none;
}
```

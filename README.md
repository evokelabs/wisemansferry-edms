Remove !important from _visible in node_modules/foundation-emails/scss/components/_visibility.scss to prevent responsive issues.
line 9:

.hide-for-large {
display: none !important;
}


to become:
.hide-for-large {
display: none;
} 



>>
Update these two for melon.

node_modules\inky\lib\ componentFactory.js
node_modules\inky\test\ components.js

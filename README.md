Remove !important from _visible in mode_modules/foundation-emails/scss/components/_visibility.scss to prevent responsive issues.
line 9:
.hide-for-large {
display: none !important;
}

to become:
.hide-for-large {
display: none;
} 

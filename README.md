# New Atlas [Copenhagen] Zendesk theme

This theme lightly modifies the default 'Copenhagen' theme, mainly to hide comments.  

There's a feature request open to permit this functionality without editing the theme, but in my estimation, it's unlikely that it will be implemented: https://support.zendesk.com/hc/en-us/community/posts/207523518-Add-Ability-to-Globally-Turn-Off-Article-Comments?page=1#community_comment_360001714348.

I'm not updating the version defined in the manifest when I make changes - I suggest we use that to track changes in the original 'Copenhagen' theme. 


## BG Image

For reference, the BG image (in `.hero`) is 300px in height across all breakpoints, and is set to `background-size: cover;`, shrinking to the centre. 

The image credit is defined in the bottom of style.css.


## Deploy

- `git archive --format zip --output ~/Downloads/newatlas-copenhagen.zip master`
- https://newatlas.zendesk.com/theming/workbench > Import

The new theme will overwrite the old one, so long as the name defined in the manifest matches.

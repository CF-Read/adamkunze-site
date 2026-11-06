# Change log for adamkunze.com


Every change to the site is recorded here: what changed, why, and how to undo it.


## 2026-11-05 - Bandsintown tracking added to fan links
- **Changed:** index.html. The Bandsintown buttons now use Bandsintown's documented sign-up addresses, which include the artist's Bandsintown API key (app_id), so sign-ups are credited to this site. The key is public by design and is not repeated here.
- **Button wording:** "Come to my city - request a show" is now "Request a show near you".
- **Unchanged:** Facebook link; plain HTML and CSS, no JavaScript.
- **Phone numbers:** Bandsintown collects them on its own sign-up page because the setting is on in Bandsintown for Artists. Nothing is stored on this site.
- **Undo:** revert the commit "Update Bandsintown links in index.html" in GitHub history.
- **Tested:** the Request a show link loaded Adam's Bandsintown sign-up form (no data submitted).

## 2026-11-05 - Fan links added
- **Changed:** index.html. Added three link buttons under the name: "Come to my city - request a show" (Bandsintown Play My City), "Follow on Bandsintown", and Facebook.
- **Links:** Bandsintown artist page https://www.bandsintown.com/a/15673286 ; Facebook page https://www.facebook.com/people/Adam-Kunze/61590355832638/
- **Technical:** plain HTML and CSS only, no JavaScript, no third-party scripts, no forms stored on the site. Fan sign-ups happen on Bandsintown.
- **Not done yet:** links do not include a Bandsintown API key (app_id), so Bandsintown cannot attribute sign-ups to the site. Add later if a key is obtained.
- **Undo:** revert the commit "Add navigation links to index.html" in GitHub history.


## 2026-10 - Name-only landing page
- Initial commit: name-only page, no JavaScript.


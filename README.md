For the blog site, use this to test locally:

cd C:\Users\Adam\Documents\pretense.adambaker.org
bundle exec jekyll serve


But you just upload the code to GitHub, and it builds it automatically. _site is purely local.


Customization:
https://github.com/jekyll/minima
Note this may not be applicable to GitHub Pages, I'm not sure.

Commit source:

cd C:\Users\Adam\Documents\pretense.adambaker.org
git add .
git commit -m 'update'
git push


Publish:
cd C:\Users\Adam\Documents\pretense.adambaker.org\_site
git add .
git commit -m 'update'
git push



get the paths for all minima files:

bundle info --path minima 
C:/Users/Adam/.local/share/gem/ruby/3.2.0/gems/minima-2.5.1

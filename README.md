# NodeSchool Perth

[![Join the chat at https://gitter.im/nodeschool/perth](https://badges.gitter.im/join chat.svg)](https://gitter.im/nodeschool/perth)

This is the repository for the Perth (Western Australia) chapter of NodeSchool for organising learning events.

# Information

To find out more about NodeSchool, please head over to the main site.

http://nodeschool.io

If you are interested in getting involved, don't hesitate to get in touch.
We also have a Gitter channel, so drop by and say hello!

https://gitter.im/nodeschool/perth

# Contact

- [@nii236](http://github.com/nii236)
- [@miqid](http://github.com/miqid)

# Spinup Instructions

```
brew install hugo
git@github.com:nodeschool/perth.git
cd perth
hugo server -w
```

Go to [localhost:1313]()

# Deployment to gh-pages branch

```
hugo
git add .
git commit -m 'commit message'
git push origin [branch]
git subtree push --prefix public origin gh-pages
```

Go to [nodeschool.io/perth]()

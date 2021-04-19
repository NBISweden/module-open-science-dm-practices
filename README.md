# Open Science and FAIR
The instructional content is an adaptation of previous works as detailed in [LICENSE.md](LICENSE.md). 

# To build this lesson
## Install dependencies
```
conda env update -n name-of-your-env -f environment.yml
conda activate name-of-your-env
gem install bundler
bundle install
```

## Build lesson
```
conda activate name-of-your-env
bundle exec jekyll build
```

## Preview lesson locally
```
$ conda activate name-of-your-env
$ bundle exec jekyll serve
```

# Beta Lambda Chapter of Alpha Omega Epsilon at Lehigh University
Welcome! We are using Github pages to host our website. The theme we used is the Event Jekyll Theme. This is a theme that is designed to be used for conference and event purposes. The index page is a modification and built on top of [Agency Jekyll Theme](https://github.com/y7kim/agency-jekyll-theme).

## Files Structure
- The main stylesheet, `agency.css`, is stored `/css/2016_style`. Both `2016` and `2017` are sharing the same stylesheet.
- In `/css/2016_style/img` you will find where the pictures in `/2016` are stored at. You will find the images of sisters, exec, recruitment, etc in `/css/2017_style/img`. This setup is to ensure that we can easily move from year to year by creating new folders.
- `_2016_pages` and `_2017_pages` are the folders that store subpages.
- `_2016_data` and `_2017_data` are the folders that store each sections in home page. Those sections are can be removed by removing or commenting out the `include` code in `_layout/2016_home.html` or `_layout/2017_home.html`.
- `_data/twenty_16/` and `_data/twenty_17/` contains `data` files for sisters, faqs, home about section data, alumni, etc. The data file is in the format of `.yml`. The reason why the folders are named `twenty_16` and `twenty_17` are due to liquid syntax will throw errors if the name contains integer. 
- In order to view PDF correctly, sharing setting in Google Drive must set to "Public on the web".

## Documentation
- This link contains more documentation on how to edit everything: https://docs.google.com/document/d/1M_AHzHvoCBMqXrCQmqqYj3yAszgNcc5ujw2fXkr17PY/edit?usp=sharing 

## Enjoy!

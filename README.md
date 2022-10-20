# THINGS IN HERE

## GEMS

```
gem "sassc-rails"
gem 'haml'
gem 'simple_form'
gem 'devise'
```
- devise set for turbo, rails 7
- from: https://dev.to/efocoder/how-to-use-devise-with-turbo-in-rails-7-9n9

## MODELS
- devise user
- user has many notes

## OTHER
- scss with master global variables
- css for background images

```
background-image: url(image_path("welcome_banner_image.jpg"));
```

- different root path for logged in

```
  authenticated :user do
    root 'notes#index', as: "authenticated_root"
  end
```
# jQuery Gravatar

## Usage

Without options:

    $('body').append($.gravatar('zachleatherman@gmail.com'));

With options:

    $('body').append($.gravatar('zachleatherman@gmail.com', {secure: true,
                                                             rating: 'pg'}));

## Options

* size: size of the gravatar
* rating: rating of the gravatar g (default), pg, r, x
* image: default image url
* secure: serve https gravatar

## License

Licensed under the WTFPL (http://sam.zoy.org/wtfpl/)
